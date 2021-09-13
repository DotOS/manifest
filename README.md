
<p align="center">
<img src="https://raw.githubusercontent.com/DotOS/resources_drawables/master/dot11/dot_main-banner.png" > 
</p>

Supported Devices and Downloads :- https://www.droidontime.com/devices
=========

-----------------------------------------------------------------------------

<p align="center">
<img src="https://raw.githubusercontent.com/DotOS/resources_drawables/master/dot11/dot5-2-wide.png" > 
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
