# mate-terminal

A fork of the mate-terminal emulator (1.23.0).

## How to build

```
$ ./autogen.sh
$ ./configure \
    --prefix=/usr \
    --sysconfdir=/etc \
    --disable-static --localstatedir=/var --with-gnu-ld
$ make
$ src/mate-terminal
```
