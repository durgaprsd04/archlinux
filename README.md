archlinux
=========

An installation guide for arch linux. This is quite a similar to what you could get in any site and is always gonna be the same. There is nothing new in this guide. But I have gone through a lot of wikis so that you don't have to if you want to install arch linux. 
                    First let me brief you with arch philosophy.Any ubuntu or Linux Mint user might have come across system monitor and all those processes running in them at least one time in their entire period of usage.But none bothered to ask do we really need all these programs. And it is quite surprising to know that ubuntu comes with a lot of software that many of us won't be using. So what is the point of having it installed in the first place. Ubuntu is a good distro for starters , but if you want control over your system and want to make things minimalistic arch is the distro for you.
                    I am going to give you a brief guide on installing arch both for offline users and online users . This is just briefed up so that you could remember all this while installing arch and never think of using a pc or instruction.
First we need to create a create a bootable disk and then start with it , using a command dd.
dd bs=4M if=/source/file/iso of=/dev/sdb && sync ( this is in my case, you could find your device using lsblk )
Now we have a bootable medium and you could log in to the bootable shell. From there you can partition and then find a suitable partition to install the media and start installation.The above given step is for a usb device.For CD's you have to have other instructions.
                    Just remember the following steps properly. First you need to partition your disk properly . This might be a litte difficult . So you have to get familiar with the utilities cgdisk or fdisk.
