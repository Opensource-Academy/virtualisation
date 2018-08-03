# Virtualisation 101 - Virtual machines with Virtual Box and Xubuntu

## Virtual machines

Virtual simply means: not physical. You could think of 'virtual' as meaning 'not real', but 'not physical' is a better way of looking at it.

A virtual computer is referred to as a 'virtual machine' or 'VM'. The computer might not be a real physical machine, but that does not change the fact that it is a real working computer; this is why 'not real' is slightly too strong as a definition.

Virtual machines allow running several 'computers' on a single physical machine, making it easy to, for example, run several operating systems at once, on a single box.

## Virtual box: the computer
VirtualBox is a program that allows you to run a virtual machine on your computer.

The virtual machine is a seperate computer on your computer, it has it's own hard drive and changes made inside the virtual machine are only applied there.

With VirtualBox you can run a Linux or Windows computer on your Linux, MacOS or Windows machine.

### VirtualBox installation
General downloads page: https://www.virtualbox.org/wiki/Downloads

Download the correct version for your operating system.

## Xubuntu: the operating system
After installing VirtualBox on your machine, you can download a Xubuntu installation dvd image. An image (often referred to as 'iso', because of it's file extension `.iso`) is a digital copy of the contents of a CD or DVD.

Xubuntu 64 bit iso: http://nl.archive.ubuntu.com/ubuntu-cdimage-xubuntu/releases/18.04/release/xubuntu-18.04-desktop-amd64.iso

### Xubuntu installation
While you are downloading the xubuntu .iso you can prepare a new virtual machine. Launch VirtualBox if you have not already done so and click the 'new' button. Follow the set up assistant to set up your new VM. Be sure to select 'Ubuntu' as the operating system.

Once the iso has finished downloading, start your machine and use the pop up window to select the iso you just downloaded. From here on, the installation will resume like on a physical machine.

If you have never installed Xubuntu before, you will find that the installation is quite straightforward, because you are on a VM, once you started the VM and just wait for a few seconds, you should be greeted by either the Xubuntu Desktop with an installer icon on the desktop, or an installer window. The installer should be straightforward from here on. Most default values should be fine for you.

```
   Copyright 2018 Opensource Academy

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
```
