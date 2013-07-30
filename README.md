ANDROID-KERNEL-QX1
==================

ANDROID-KERNEL-QX1 by leolas (www.freaktab.com)
This sources must work in all devices, but QX1 is a little special device and need some changes in /arch/arm/mach-rk3188/board-rk3188-box.c to make wifi and BT work, so if you have a different device I suggest change this file for /arch/arm/mach-rk3188/board-rk3188-box.c.STOCK and compile the kernel using this one, I commented all my aditions to make WIFI and BT work in QX1, and probably it will not work in other devices. So take care of that. Of course those kernel sources are in development and I take no responsability if you use them.

New Repository started at 30-july-2013.
Cloned from https://github.com/linuxium/3188-SRC-AP6210 Thanks to linuxium for upload it to his github. And Andykirby from rickomagic forum (http://www.rikomagic.co.uk/forum/viewtopic.php?f=13&t=4696&sid=00ece4d9b66cd4130d765de8f6d6010b)
Thanks to Sam321(www.freaktab.com) he kindly shares the code for OC located in arch/arm/board-rk3188-box.c
Thanks to thesawolf(www.freaktab.com) he helped me with some tips and give some of the io schedulers in his github(https://github.com/thesawolf/android_kernel_rockchip_rk3188)
Thanks to Galland (http://hwswbits.blogspot.com.es/) I get a lot of tips from his blog and I merged some stuff of his github(https://github.com/Galland/Linux3188)
Thanks to omegamoon(http://www.omegamoon.com/blog/) for his tips and I take some stuff from his github(https://github.com/omegamoon)
Thanks to Alok and the picuntu development team. They do so much work with this tvsticks and give me a lot of tips
Thanks to phjanderson(www.freaktab.com) he found a fix for video skiping issue in rk3188 and some tips that make the things easier.

30/07/2013
Initial commit.
By default this sources are designed to run a bit OC in CPU (1800) and RAM(720), you can control the OC and Voltage in /arch/arm/mach-rk3188/board-rk3188-box.c
TUN module compiled in kernel.
