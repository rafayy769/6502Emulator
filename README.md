# 6502 Emulator

A TUI based simple 6502 emulator, written in C.

## Run

`ncurses` is a dependency, you can install it with:
```bash
$ sudo apt-get install libncurses5-dev libncursesw5-dev
```
In order to build the project, run:

```
$ make
```
The emulator can then be executed as follows:
```
$ ./bin/emulator.out
```

### Loading a custom program

By default, the emulator loads `example.bin`. A custom binary can be loaded as follows:

```
$ /bin/emulator.out path/to/binary
```