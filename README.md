# ARMWin10-VM-GUI
ARM64 Win10 Virtual Machine GUI launcher for better user experience developed by pifan.

This GUI launcher is only intended to be used with Pifan Aarch64 Debian 64bit OS. 

Never tested on any other OS, so no guarantee it will work.

如果你是中国用户，且看不懂英文指南，不要为难自己，直接打开下方的三个链接

# Video and Detailed instruction(only avaliable in Chinese)
https://mp.weixin.qq.com/s/ZfwQTo6FSc9jWamr939LgA

https://mp.weixin.qq.com/s/L2JLcZfPc3j7pqCiboUWKA

https://www.bilibili.com/video/BV1CK4y1v7CW

# Installation Guide

```
# prep your system and clone the repo
sudo apt-get update
sudo apt-get install git python3-tk
sudo apt-get upgrade
git clone https://github.com/pifan-open-source-community/ARMWin10-VM-GUI.git
cd ARMWin10-VM-GUI 

# you may use one of two commands to install main package on your prefrence, first one recommended
sudo apt-get install ./win10_arm_launcher.deb
# or
sudo dpkg -i ./win10_arm_launcher.deb

```

# Operate Guide

You will have a freshly created short cut on your desktop if everything works correctly.

Open your main folder(e.g /home/pi)

Place the .Vhdx virtual disk file under pifan_win10_vm folder.

You may download virtual disk file from https://share.weiyun.com/OxyvofvS

it's about 30GB in size after extractiton, so make sure you have plenty space left on your SD card

After doing these, double click icon on desktop and enjoy the user-friendly interface. Interface is avaliable in English.


# Participated Member in this project

Yike Chen(@PatrickChenHZ)  Developer of GUI, Idea.

YiZhu Wang（@aiminick） Scipt and system environment optimization.
