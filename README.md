# appimage-manager

A CLI app to manage your AppImage collection.

## Installation 

```shell script
sudo wget https://github.com/AppImageCrafters/appimage-manager/releases/download/v0.1.0/app -O /usr/local/bin/app
sudo chmod +x /usr/local/bin/app
```

## Usage
```shell script
Usage: app <command>

Flags:
  --help     Show context-sensitive help.
  --debug    Enable debug mode.

Commands:
  search <query>
    Search applications in the store.

  install <target>
    Install an application.

  list
    List installed applications.

  remove <id>
    Remove an application.

  update [<targets> ...]
    Update an application.

Run "app <command> --help" for more information on a command.
```
