
This script will create 4 lxd instances called c1 c2 c3 c4 on a single computer.
The result may be used for creating a demo / teaching Cassandra ring setup.

Tested only on Ubuntu 16.04.

The script will also setup /etc/hosts and ssh with key auth so you can run from your host
    ssh root@c1 # or c2 c3 c4


I wanted to keep it clean and simple that's why it is a bit complicated to change those parameters,
for instance if you wish to have three or five LXD instances you will to change more than one file
from this directory. But it should be manageable.


