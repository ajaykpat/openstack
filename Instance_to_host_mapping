

#!/bin/bash

# To find instance to hostmapping in openstack.

for i in $(nova list | awk '{print $2}')
do
nova show $i | egrep "description|hostId"
done
