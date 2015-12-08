# Getting Started
---------------

To get started with this ROM, you'll need to get
familiar with [Git and Repo](http://source.android.com/download/using-repo).

To initialize your local repository use a command like this:

    repo init -u git://github.com/nfxosp/platform_manifest.git -b nfx-4.4.4

Then to sync up:

    repo sync

Then to build:

     cd <source-dir> && ./build/envsetup.sh && brunch <device_name>
     
     EG: cd /Volumes/android/aosp && ./build/envsetup.sh && brunch hammerhead
