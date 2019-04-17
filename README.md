# system_establishment

## xdg-user-dirs-gtk-update
```
$ LANG=C xdg-user-dirs-gtk-update
```

## Ctrl2Caps
https://qiita.com/hirooooooaki/items/f404e76c6f171769412a

## rosemacs
```
$ sudo apt-get install ros-$ROS_DISTRO-rosemacs
$ cp .emacs ~/
$ # rm -rf ~/.emacs.d
```
## C-space disable for Emacs
https://www.cs.gunma-u.ac.jp/~nagai/wiki/index.php?Ubuntu%2014.04%20%B1%D1%B8%EC%C8%C7%20%2864bit%29%20%A5%A4%A5%F3%A5%B9%A5%C8%A1%BC%A5%EB%B8%E5%A4%CB%C0%DF%C4%EA%A4%B7%A4%BF%A4%B3%A4%C8#w791eaa3

38

## show git branch in prompt
https://qiita.com/ryosukue/items/bc1eae639e3950790eb9
33m -> 34m (blue)

## cuda
https://qiita.com/JeJeNeNo/items/05e148a325192004e2cd

## ros
http://wiki.ros.org/kinetic/Installation/Ubuntu

## chainermn
https://qiita.com/pst-ic/items/e01033dee4d389df3a5e

## grub default change
http://komagawa292.net/20131103/grub2-default-os/

## pyenv
https://qiita.com/hashibiroko/items/60a685e50aebbde7f84e

## Thinkpad X1Carbon Gen6
```
$ sudo emacs /etc/default/grub
GRUB_CMDLINE_LINUX_DEFAULT="quiet splash psmouse.proto=imps acpi.ec_no_wakeup=1"

$ sudo update-grub2
$ sudo su
$ echo enabled > /sys/devices/platform/i8042/serio0/power/wakeup
$ sudo emacs /usr/share/X11/xorg.conf.d/10-evdev.conf
Section "InputClass"
    Identifier "Wheel Emulation"
    MatchProduct "PS/2 Synaptics TouchPad"
    Option "EmulateWheel" "on"
    Option "EmulateWheelButton" "2"
    Option "XAxisMapping" "6 7"
    Option "YAxisMapping" "4 5"
EndSection
```
https://senz.hatenablog.com/entry/2018/06/10/184327

https://hogepad.com/linuxubuntuthinkpad-x1-carbon-5th-2017%E3%82%92ubuntu%E3%81%A8%E3%83%87%E3%83%A5%E3%82%A2%E3%83%AB%E3%83%96%E3%83%BC%E3%83%88%E3%81%99%E3%82%8B1/

## Windowsからsambaが見えないとき
https://blog.makotokw.com/2017/12/26/windows10-samba-nas/
