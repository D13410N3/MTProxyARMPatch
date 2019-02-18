# MTProxyARMPatch
Patch for running MTProto on ARM (including MIPS)


1) clone this: https://github.com/TelegramMessenger/MTProxy

2) Install required depencies (view README.md)

3) Go to MTProto directory

4) Import arm.patch

5) Execute this:

make clean

patch -p1 < arm.patch

make && cd objs/bin


6) Continue usual setting - https://github.com/TelegramMessenger/MTProxy#running
