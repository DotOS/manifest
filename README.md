<p align="center">
<img src="https://github.com/DotOS/manifest/blob/dot-o/dot.png" > 
</p>

--------------------------------------------------------------

 Dot OS Oreo
 ==========


 Credits
 =======
 * [**JDCTeam**](https://github.com/AOSP-JF-MM)
 * [**AospExtended**](https://github.com/AospExtended)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**TeamSubstratum (Theme Engine)**](https://github.com/Substratum)


-----------------------------------------------------------------------------


 Getting Started
 ==============

To get started with the building process, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository, use a command like this:

```bash
    repo init -u git://github.com/DotOS/manifest.git -b dot-o
```

Then to sync up:

```bash
    repo sync  -f --force-sync --no-clone-bundle
```

Additionally, you can define the number of parallel download repo should do:

```bash
    repo sync -f -jX --force-sync --no-clone-bundle  ( X is the number of parallel download repo should do choose depending on your cpu )
```

----------------------------------
 
 Compilation of Dot OS
 ==================

From root directory of Project, perform following commands in terminal


```bash
	. build/envsetup.sh
   
        lunch dot_<codename>
   
	brunch <codename>
```


<p align="center">
<img src="https://github.com/DotOS/manifest/blob/dot-n/dotlogo.png" > 
</p>

--------------------------------------------------------------------------------------------------------------------------

For maintainership & to submit patches refer [**HERE**](https://github.com/DotOS/android_vendor_dot/blob/dot-o/README.md) 

--------------------------------------------------------------------------------------------------------------------------



