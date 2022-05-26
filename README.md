# mate-terminal

A fork of the [mate-terminal](https://github.com/mate-desktop/mate-terminal) emulator.

## Branches

- [master](https://github.com/soimort/mate-terminal/tree/master) (1.26)
- [1.20](https://github.com/soimort/mate-terminal/tree/1.20)

## Dependencies

- mate-common
- yelp-tools

## Features

- Hiding the close buttons of tabs.

## Future work

- Session management (restoring tabs).

## How to build

```
$ git submodule init
$ git submodule update --remote --recursive
$ ./autogen.sh --prefix=/usr --sysconfdir=/etc \
    --disable-static --localstatedir=/var --with-gnu-ld
$ make
$ src/mate-terminal
```
