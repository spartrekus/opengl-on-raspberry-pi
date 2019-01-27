# opengl-on-raspberry-pi

By default, opengl is not installed. 



ps aux | grep lx
pi         532  0.3  1.3  52504 12916 ?        Ssl  19:15   0:00 /usr/bin/lxsession -s LXDE-pi -e LXDE
pi         618  0.8  1.5  53768 14692 ?        S    19:15   0:01 openbox --config-file /home/pi/.config/openbox/lxde-pi-rc.xml
pi         621  0.0  1.1  43100 10980 ?        Sl   19:15   0:00 lxpolkit
pi         628  1.5  2.6 141120 24920 ?        Sl   19:15   0:02 lxpanel --profile LXDE-pi
pi         797  1.0  2.1  48040 19964 ?        Sl   19:15   0:01 lxterminal
pi        1327  0.0  0.0   4372   544 pts/2    S+   19:18   0:00 grep --color=auto lx

uname  -a
Linux linuxpitv 4.14.79-v7+ #1159 SMP Sun Nov 4 17:50:20 GMT 2018 armv7l GNU/Linux

cat /proc/cmdline 
8250.nr_uarts=0 cma=256M bcm2708_fb.fbwidth=1824 bcm2708_fb.fbheight=984 bcm2708_fb.fbswap=1 vc_mem.mem_base=0x3ec00000 vc_mem.mem_size=0x40000000  dwc_otg.lpm_enable=0 console=ttyS0,115200 console=tty1 root=PARTUUID=3a33776a-02 rootfstype=ext4 elevator=deadline fsck.repair=yes rootwait


I enabled the OpenGL with sudo raspi-config

It gives then 60 fps. 

