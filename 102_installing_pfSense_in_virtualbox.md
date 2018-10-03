# Installing PfSense In VirtualBox
1. [Download the CD Image from this site](https://www.pfsense.org/download/)
2. Create a new Virtual Machine
3. Open pfSense's VM settings
4. In the network tab change the following settings
    * Enable Network Adapter 1 & 2
    * Set "Attached to" to NAT on adapter 1 and Internal Network on adapter 2
    * Remember the Internal Network name (default is intnet)
5. Open the settings of the VM you want to use to acces pfSense's dashboard (if you don't have a VM go through [Virtualisation 101](https://github.com/Opensource-Academy/virtualisation/blob/master/101_virtual_machines_with_virtual_box_and_xubuntu.md))
6. In the network tab set "Attached to" to Internal Network on adapter 1
7. Check if the name matches the internal network name of the pfSense VM
8. Start pfSense's VM and resume like a normal installation

Now you can acces pfSense's network and its dashboard on the other VM you installed.
