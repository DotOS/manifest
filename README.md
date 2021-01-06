

```bash
    repo init -u git://github.com/dotos-test/manifest.git -b dot11
```

Then to sync up:-
================

```bash
    repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

Start the build:-
=================

```bash
  . build/envsetup.sh
  lunch dot_<devicecodename>-userdebug
  make bacon -jx
```
Our Gerrit:-
=================
https://review.droidontime.com/
