# Kitten-Linux
The official repo for Kitten Linux
WARNING: KITTEN LINUX IS STILL IN HEAVY TESTING. I DO NOT KNOW WHAT WILL HAPPEN IF YOU PLUG THIS IN A REAL COMPUTER AND NOT QEMU. YOUR PC ARCHITECTURE NEEDS TO BE x86_64/AMD64.

Thank you for checking out Kitten Linux! Kitten Linux is designed to be incredibly light weight (requires a minimum of 75 mb of ram to function decently, though 100mb+ is recommended). It has all the basic things; It has a working graphical environment (Fluxbox), a terminal and a functioning browser (Only basic HTML websites like wikipedia. websites such as youtube probably will not work. here is basically every extra terminal based application it has:

Nano, chocolate-doom, tcc, sudo, zip and bzip2

How to use it:
(requires qemu)
So you are going to download the source code. put it in whatever directory you want, unzip it, then you are going to open your terminal and navigate to:
/kitten-linux/buildroot-2026.08
once you are in that directory in the terminal, run:
qemu-system-x86_64 -hda output/images/disk.img -m 512M
And it should launch!
Once you select kitten linux in the grub menu it will load it, You will have to press enter once it stops loading and then you will see
kitten-linux login:
type root and press enter. You will now be greeted by a cute kitten wallpaper. right click to see what applications u can launch Happy exploring!
