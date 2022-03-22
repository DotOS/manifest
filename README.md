# DotOS 6.x - Android 12
<p align="center">
<img src="https://raw.githubusercontent.com/DotOS/resources_drawables/master/dot11/dot_main-banner.png" > 
</p>

## Supported Devices and Downloads :- https://www.droidontime.com/devices

Downloading Source Code:
========================

To get started with the building dotOS for your device, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository, use a command like this:

```bash
repo init -u https://github.com/DotOS/manifest.git -b dot12.1
```

then to sync up:
================

```bash
repo sync
```

> To speed syncs, pass the -c (current branch) and -jthreadcount flags.
> Also to suppress output, pass the -q (quiet) flag.
Compilation of DotOS:
====================

From root directory of Project, perform following commands in terminal to start Compilation.

#### Building DotOS
```bash
# Initialize the environment with the envsetup.sh script:
source build/envsetup.sh
# lunch your device (codename)
lunch dot_<devicecodename>-userdebug
# start compilation for your device
make bacon
```
-----------------------------------------------------------------------------