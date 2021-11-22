# MTProxyARMPatch
Patch for running MTProxy on ARM (including MIPS)


1) Start installation - clone [this](https://github.com/TelegramMessenger/MTProxy)
2) Install required depencies (view README.md)
3) Go to MTProto directory
4) Import `arm.patch`
5) Execute this commands:
- `make clean`
- `patch -p1 < arm.patch`
- `make && cd objs/bin`

6) Continue [normal installation](https://github.com/TelegramMessenger/MTProxy#running)
