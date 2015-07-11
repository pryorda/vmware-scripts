# vmware-scripts
To use these scripts you will need run sudo pip install pyVmomi
###### snapshot-vm.py
This script is will create, remove, or revert a snapshot.


``user@host:~/vmware-scripts$ ./snapshot-vm.py -h
Usage: snapshot-vm.py -h

Options:
  -h, --help            show this help message and exit
  -v VCENTER, --vcenter=VCENTER
                        -v vcenter-ip or dns name
  -p PASSWORD, --password=PASSWORD
                        -p vcenter-password
  -u USER, --user=USER  -u vcenter-user
  -m VM, --vm=VM        -m virtual-machine
  -o OPERATION, --operation=OPERATION
                        -o create, remove, or revert
  -n SNAPNAME, --name=SNAPNAME
                        -n snapshot-name
  -d DESCRIPTION, --description=DESCRIPTION
                        -d description``

