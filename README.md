# Drivepak

Wrapper for the `flatpak` command line that lets you easily choose between a system flatpak installation or an flatpak installation on an external drive.

## Quick Start

**THE DEFAULT INSTALLATION FOLDER IS `/media/roberto/HomePartition`**. See [Changing installation folder](#changing-installation-folder).

```console
# ./drivepak system install <flatpak.app> # install on system
# ./drivepak external install <flatpak.app> # install on external drive
```

## Changing installation folder

Just create a file inside your `.config` folder called `drivepak_external_hd` containing the path to the installation folder.
