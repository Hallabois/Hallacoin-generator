# Building and Installing
1. Varmista, että cpp-compileri on asennettu, ubuntulla asenna libtool: ```sudo apt-get install libtool```
2. follow the instructions for your system in ```hallacoin/doc/build-{insert your OS here}```
- [Linux](https://github.com/Hallabois/Hallacoin/blob/master/doc/build-unix.md)
- [Windows](https://github.com/Hallabois/Hallacoin/blob/master/doc/build-windows.md)
- [Mac](https://github.com/Hallabois/Hallacoin/blob/master/doc/build-osx.md)

## Raspberry pi
Käytä linuxin ohjeita, mutta ```./configure```:n sijaan käytä ``` ./configure CXXFLAGS="--param ggc-min-expand=1 --param ggc-min-heapsize=32768" --enable-cxx --without-gui --disable-shared --with-pic --enable-upnp-default --disable-wallet --with-boost-libdir=/usr/lib/arm-linux-gnueabihf```
