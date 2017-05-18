

### Only limited instructions are provided here. For 
detailed instruction please refer [User guide 
](http://multibootusb.org/page_guide/)

What is multibootusb?
---------------------

MultiBootUSB is a cross platform* software/utility to create 
multi boot live Linux on a removable USB disk.
It is similar to UNetbootin but many distros can be 
installed, provided you have enough space on the disk.
MultiBootUSB also provides an option to uninstall distro(s) 
at any time, if you wish.

* Only works on windows and linux

## What does multibootusb do?

MultiBootUSB allows you to do the following:

1.  Install multiple live Linux and other Operating Systems 
to a USB disk and make it bootable without erasing existing 
data.
2.  Ability to uninstall installed OS later.
3.  Write ISO image directly to a USB disk (you can think of 
GUI for Linux `dd` command).
4.  Boot ISO images directly without rebooting your system 
using QEMU option.
5.  Boot bootable USBs without rebooting your system using 
QEMU option.
6.  Boot USB on UEFI/EFI system through GRUB2 bootloader 
(limited support).

## Websites:
* http://multibootusb.org/
* http://multibootusb.org/page_download/
* https://github.com/mbusb/multibootusb
* https://aur.archlinux.org/packages/multibootusb/

## Does it actually work?
* Absolutely!  At least when using ArchMan KDE
    * Translated to English: http://bit.ly/2qUpzIQ
    * SourceForge Project: 
https://sourceforge.net/projects/archman-os/files/
    * Original Turkish: http://archman.org/
* Anywhere else?
    * Haven't tried yet


## Installation:

* On Windows:
    * The windows version of multbootusb is not a standalone 
program. You need to install it on windows after download. 
Download the latest 
    precompiled setup binary (.exe) file from 
     [here](http://multibootusb.org/page_download/)
     * The installation is fairly simple. Double click on 
the executable and follow the onscreen instructions.

* On Linux:

    **Using binary method:**
    
    * Download the installation and source files for various 
distros from 
    [here](http://multibootusb.org/page_download/)
    * Use your favourite package manager to install 
multibootusb.
    
    **Using source code method:**
    
    * The install.py script provided with multibootusb 
should take care of all dependencies and install 
multibootusb.
    Assuming you have downloaded the package named 
**multibootusb.tar.gz** in your home directory, issue the 
following commands to install multibootusb:

```sh
    tar -xf ./multibootusb.tar.gz
    cd multibootusb
    chmod +x ./install.py   
    sudo ./install.py
``` 

---


How to uninstall?
-----------------
You can uninstall multibootusb at any time using the 
"uninstall.py" script provided with multibootusb.

```
cd multibootusb
chmod +x ./uninstall.py
sudo ./uninstall.py
```

For the rest of operations you can refer to the 
[Guide](http://multibootusb.org/page_guide/) section of 
[http://multibootusb.org](http://multibootusb.org) 

Website:
--------

http://multibootusb.org


Development:
-----------

https://github.com/mbusb/multibootusb

Help:
-----

Use Github issue service at 
[https://github.com/mbusb/multibootusb/issues](https://github.com/mbusb/multibootusb/issues) 
for help and issues.    

Contributor(s)
--------------
Ian Bruce  
LiQiong Lee  
Alin Trăistaru (alindt)   
and many others who have given their valuable bug report/ 
feedback.

Author(s)
---------
MultiBootUSB is brought to you by Sundar and co-authored by 
Ian Bruce.

Forked:
Ev - koesherbacon

