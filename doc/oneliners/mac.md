# Mac One-Liners

## Updates

`softwareupdate(8)` – system software update tool

### List updates

```shell
% softwareupdate --list
```

Tested:

- MacOS Sequoia 15.3

### Install all applicable updates

```shell
% softwareupdate --install --all
```

Tested:

- MacOS Sequoia 15.3

## Property Lists

`plutil(1)` – property list utility

### Print plist in human-readable format

```
% plutil -p ${filename}
```

Tested:

- MacOS Sequoia 15.3

### Check plist for errors

```
% plutil -lint ${filename}
% plutil ${filename}
```

Tested:

- MacOS Sequoia 15.3
