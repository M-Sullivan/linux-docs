# reflector

[Home](../README.md)

## Installation

```bash
$ sudo pacman -S reflector rsync curl
```

## Prep
```bash
$ sudo cp /etc/pacman.d/mirrorlist /etc/pacman.d/mirrorlist.bak
```

## Run
```bash
$ sudo reflector --latest 20 --protocol https --sort rate --save /etc/pacman.d/mirrorlist 
```

