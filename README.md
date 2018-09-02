<p align="center">
<img src="https://github.com/DotOS/manifest/blob/dot-o/About.png" > 
</p>

--------------------------------------------------------------
 Dot OS 3.x - Android Pie
 ==========
 Credits:
 =======
 * [**LineageOS**](https://github.com/LineageOS)
 * [**DirtyUnicorns**](https://github.com/dirtyunicorns)
 * [**AospExtended**](https://github.com/AospExtended)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**ABC**](https://github.com/ezio84?tab=repositories)

-----------------------------------------------------------------------------
 Gerrit:
 ==============
 Submit your All patches through our [Gerrit Code Review](http://gerrit.droidontime.com/).
 Getting Started:
 ==============

To get started with the building process, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository, use a command like this:

```bash
    repo init -u git://github.com/dotos-pie/manifest.git -b dot-p
```

Then to sync up:

```bash
    repo sync  -f --force-sync --no-clone-bundle --no-tags
```

Additionally, you can define the number of parallel download repo should do:

```bash
    repo sync -f -jX --force-sync --no-clone-bundle --no-tags ( X is the number of parallel download repo should do choose depending on your cpu )
```
----------------------------------
 Compilation of Dot OS
 ==================

From root directory of Project, perform following commands in terminal


```bash
	source build/envsetup.sh
   
        lunch dot_<codename>
   
	brunch <codename>
```


<p align="center">
<img src="https://github.com/DotOS/manifest/blob/dot-n/dotlogo.png" > 
</p>

--------------------------------------------------------------------------------------------------------------------------

For maintainership & to submit patches refer [**HERE**](https://github.com/DotOS/android_vendor_dot/blob/dot-o/README.md)

--------------------------------------------------------------------------------------------------------------------------



