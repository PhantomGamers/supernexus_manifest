SuperNexus Manifest
=================
=================

Getting Started
---------------

Please see the [Android source page](http://source.android.com/source/index.html) for building instructions.

To initialize your local repository using my trees, use the following command:

    repo init -u https://github.com/PhantomGamers/supernexus_manifest.git -b jellybean

Then to sync up:

    repo sync -j16

Building
--------

After the sync is finished, please read the [instructions from the Android site](http://s.android.com/source/building.html) on how to build.

Once you've read that, you can build with

    make otapackage
