# bootstrap-playbox

Contains yaml script to spinup a playbox instance in OpenStack cloud custimized to my needs.

By default this provisions a 4G RAM Ubuntu trysty instance. 

`heat stack-create -f heat-template.yaml okanbox`

**NOTE:** Update default value for `floating_network_id` after cloning. 
