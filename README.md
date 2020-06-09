# virtualbox-utils
Utility scripts for VirtualBox


### Note 
For create/recreate VM functions, it is assumed that the provided ISO file contains either a kickstart or a preseeded ISO image that power offs after installation is complete..


```
Usage: 
        vm-manager (-c|-r) VM_CONFIG_FILE | -l VM_TO_BE_CLONED_NAME VM_NEW_NAME | -d VM_NAME | -h

        -c Create VM
        -r Recreate VM.  Existing VM will be delete.
                         Running VM will be forcefully shutdown & deleted
        -l Clone VM
        -d Delete VM.    Running VM will be forcefully shutdown & deleted
        -h Show this usage text
```
