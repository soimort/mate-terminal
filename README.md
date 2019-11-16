# mate-terminal

A fork of the [mate-terminal](https://github.com/mate-desktop/mate-terminal/tree/1.20) emulator (1.20.0).

## How to build

```
$ ./autogen.sh
$ ./configure \
    --prefix=/usr \
    --with-gtk=2.0 \
    --sysconfdir=/etc \
    --disable-static --localstatedir=/var --with-gnu-ld
$ make
$ src/mate-terminal
```
