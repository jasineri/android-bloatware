# Android Bloatware
Android phones come with lots of unwanted bloatware apps. An easy uninstall option however remains unavailable.

Fortunately its possible to remove/deactivate the apps without root using ADB commands.
The shell script `android-cleanup.sh` takes care of removing of presumably safe to remove apps.

If however something goes wrong, then the rollback script `android-rollback.sh` helps out.

# Supported Platforms

The files, though are shell scripts, renaming it to batch files could make in run with Windows too

# prerequisite

1. Platform tools added to your PATH (more on that could be Googled)

Platform Tools' binaries could be retrieved from [here](https://developer.android.com/studio/releases/platform-tools)

# Installation and usage

git clone https://github.com/jasineri/android-bloatware
cd android-bloatware
bash android-cleanup.sh

# Footnotes

The whole process is pretty straightforward and safe in all ideal cases.
If however something goes wrong, then the rollback script `android-rollback.sh` is always there to undo everything. 

