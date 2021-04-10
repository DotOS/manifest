
<p align="center">
<img src="https://github.com/DotOS/resources_drawables/blob/master/dotOS-5-githubBanner.png?raw=true" > 
</p>

Downloads:
=========

[![Download dotOS 5.x - P](https://img.shields.io/sourceforge/dt/dotos-downloads.svg)](https://sourceforge.net/projects/dotos-downloads/files/latest/download)

-----------------------------------------------------------------------------

<p align="center">
<img src="https://github.com/DotOS/resources_drawables/blob/master/dot5-release_banner.png?raw=true" > 
</p>

Downloading Source Code:
========================

To get started with the building process, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository, use a command like this:

```bash
repo init -u git://github.com/DotOS/manifest.git -b dot11
```

Then to sync up:
================

```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

Compilation of DotOS:
====================

From root directory of Project, perform following commands in terminal to start Compilation.


```bash
source build/envsetup.sh
lunch dot_<devicecodename>-userdebug
make bacon
```
-----------------------------------------------------------------------------


Some Important Links:-
============
* [**Website**](https://www.droidontime.com)
* [**Telegram Public Chat**](https://t.me/dotos)
* [**Telegram Channel**](https://t.me/dotOSchannel)
* [**Facebook Page**](https://www.facebook.com/dotosofficial)
* [**Twitter**](https://twitter.com/dotosofficial)
* [**PayPal**](https://www.paypal.com/paypalme/MOHANCM)


• For maintainership & to submit patches refer [**HERE**](https://github.com/DotOS/android_vendor_dot/blob/dot11/README.md)

• Submit your All patches through our [**Gerrit Code Review**](https://review.droidontime.com)

• Help us on translation through our [**Crowdin**](https://translations.droidontime.com)


-----------------------------------------------------------------------------

Credits:
=======
 * [**AOSP**](https://android.googlesource.com)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**DirtyUnicorns**](https://github.com/dirtyunicorns)
 * [**PixelExperience**](https://github.com/PixelExperience)


<p align="center">
<img src="https://github.com/DotOS/resources_drawables/blob/master/DOT5.png?raw=true" > 
</p>
