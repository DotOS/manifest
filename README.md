-----------------------------------------------------------------------------

<p align="center">
<img src="https://raw.githubusercontent.com/samgrande/manifest-1/dot-p/Untitled-1.png" > 
</p>
<p >
<img src="https://raw.githubusercontent.com/samgrande/manifest-1/dot-p/Untitled-3.png" > 
</p>

-----------------------------------------------------------------------------

Downloads:
=========

[![Download dotOS 2.x - O](https://img.shields.io/sourceforge/dd/dotos-2-x.svg)](https://sourceforge.net/projects/dotos-2-x/files/latest/download)

[![Download dotOS 2.x - O](https://img.shields.io/sourceforge/dw/dotos-2-x.svg)](https://sourceforge.net/projects/dotos-2-x/files/latest/download)

[![Download dotOS 2.x - O](https://img.shields.io/sourceforge/dm/dotos-2-x.svg)](https://sourceforge.net/projects/dotos-2-x/files/latest/download)

[![Download dotOS 2.x - O](https://img.shields.io/sourceforge/dt/dotos-2-x.svg)](https://sourceforge.net/projects/dotos-2-x/files/latest/download)

Credits:
=======
 * [**AOSP**](https://android.googlesource.com)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**DirtyUnicorns**](https://github.com/dirtyunicorns)
 * [**AospExtended**](https://github.com/AospExtended)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**ABC**](https://github.com/ezio84?tab=repositories)

-----------------------------------------------------------------------------

Getting Started:
==============

To get started with the building process, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository, use a command like this:

```bash
    repo init -u git://github.com/DotOS/manifest.git -b dot-p
```

Then to sync up:
================

```bash
    repo sync -c -jx --force-sync --no-clone-bundle --no-tags
```

Additionally, you can define the number of parallel download repo should do:

```bash
    repo sync -f -jX --force-sync --no-clone-bundle --no-tags ( X is the number of parallel download repo should do choose depending on your cpu )
```

Compilation of Dot OS:
====================

From root directory of Project, perform following commands in terminal


```bash
source build/envsetup.sh
lunch dot_<devicecodename>-userdebug
make bacon
```
-----------------------------------------------------------------------------


• For maintainership & to submit patches refer [**HERE**](https://github.com/DotOS/android_vendor_dot/blob/dot-p/README.md)

• Submit your All patches through our [**Gerrit Code Review**](http://gerrit.droidontime.com)

• Help us on translation through our [**Crowdin**](https://translations.droidontime.com)



Some Links:-
============
* [**Website**](https://www.droidontime.com)
* [**Google Plus**](https://plus.google.com/communities/101137692192340076065)
* [**Telegram Public Chat**](https://t.me/dotos)
* [**Telegram Channel**](https://t.me/dotOSchannel)
* [**Facebook Page**](https://www.facebook.com/dotosofficial)
* [**Twitter**](https://twitter.com/dotosofficial)

<p align="center">
<img src="https://raw.githubusercontent.com/samgrande/manifest-1/dot-p/Untitled-4.png" > 
</p>