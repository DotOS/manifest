<p align="center">
<img src="https://github.com/DotOS/manifest/blob/dot-n/dotlogo.png" > 
</p>

## dotOS Oreo ##


Credits
-------
* [**JDCTeam**](https://github.com/AOSP-JF-MM)
* [**AospExtended**](https://github.com/AospExtended)
* [**LineageOS**](https://github.com/LineageOS)
* [**TeamSubstratum (Theme Engine)**](https://github.com/Substratum)


Getting Started
---------------

To get started with the building process, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository, use a command like this:

    repo init -u git://github.com/DotOS/manifest.git -b dot-o

Then to sync up:

    repo sync  -f --force-sync --no-clone-bundle

Additionally, you can define the number of parallel download repo should do:

    repo sync -f -jX --force-sync --no-clone-bundle    ( X is the number of parallel download repo should do choose depending on your cpu )

 Compilation Of Rom
 ----------------------------------

From root directory of Project, perform following commands in terminal

	. build/envsetup.sh
   
    lunch dot_$codename
   
	brunch $codename

<p align="center">
<img src="https://github.com/DotOS/manifest/blob/dot-n/dotlogo.png" > 
</p>

For maintainership refer [**here**](https://github.com/DotOS/android_vendor_dot/blob/dot-n/README.mkdn) 

## Submitting Patches ##
------------------
Our ROM is open source, and patches are always welcome!
You can send patches by using these commands:
    git clone <project>
    cd <project>
    <make edits>
    git add -A
    git commit -m "commit message"
    git push ssh://<username>@gerrit.droidontime.com:29418/<project> HEAD:refs/for/dot-o

Register at <gerrit.droidontime.com> and use the username that you registered there in the above command

Commit your patches in a single commit. Squash multiple commit using this command: git rebase -i HEAD~<# of commits>

If you are going to make extra additions, just repeat steps (Don't start a new patch), but instead of git commit -m
use git commit --amend. Gerrit will recognize it as a new patchset.

To view the status of your and others patches, visit [dotOS Code Review](https://gerrit.droidontime.com)