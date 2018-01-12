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
DotOS poject is an open source, any patches/contributions are always welcome !

To begin with, you need to login to our code review system at [dotOS Code Review](https://gerrit.droidontime.com)

We support login using Google Oauth or Github Oauth provider, which means if you have either of account you can login to gerrit by that account.
It is important that you set the USERNAME in your account on gerrit. If you have logged in using Github account then your Github USERNAME will be used as gerrit USERNAME automatically. Else you can set unique username in `Profile` section of gerrit account Settings.

The next step is to add your SSH key to your gerrit account.

Refer the Github guide on [how to generate SSH key](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/)

Add the generated SSH key (the contents of id_rsa.pub file) to your gerrit account in `SSH Public Keys` section.



You can upload the patches/contributions for review process using following procedure:

```
git clone PROJECT
```
For Example -  git clone http://gerrit.droidontime.com/DotOS/android_packages_apps_Settings 
```
cd CLONED_DIRECTORY 
```

Make the changes you wish to add for review and execute following commands,
```
git add -A
git commit -m "commit message"
```
Commit message should be clear, well written and easy to understand.

If you have satisfied with the changes you made then you can upload the patchset to gerrit.
```
git push ssh://USERNAME@gerrit.droidontime.com:29418/PROJECT_NAME HEAD:refs/for/dot-o
```
Here the PROJECT_NAME is the path to repository on gerrit. You can find the PROJECT_NAME by navingating to the `Projects` section on gerrit. 

For example - DotOS/android_packages_apps_Settings 

It is recommended that you commit your several relevent patches in to one single commit.

Squash multiple commits using this command: 
```
git rebase -i HEAD~<# of commits>
```
If you are going to make extra changes to an existing patch, Don't start a new patch, instead
```
git add .

git commit --amend
```
and simply push the changes to gerrit
 
Gerrit will recognize it as a new patchset in an exisiting commit.

To view the status of your and/or others patches, visit [dotOS Code Review](https://gerrit.droidontime.com)

If you encounter any issues, feel free to contact us on our [Telegram channel](https://t.me/dotos). We will be happy to assist you !
