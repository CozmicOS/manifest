CozmicOS
===========

Getting started
---------------

To get started with Android/CozmicOS, you'll need to get familiar with [Source Control Tools](https://source.android.com/setup/develop).

To initialize your local repository using the CozmicOS trees, use a command like this:
```
repo init -u https://github.com/CozmicOS/platform_manifest.git -b a15 --git-lfs
```
Then to sync up:
```
repo sync -j$(nproc)
```
