ThinkingBridge
===========


Getting Started
---------------

To get started with ThinkingBridge, you'll need to get
familiar with [Git and Repo](http://source.android.com/download/using-repo).

To initialize your local repository using the ThinkingBridge trees, use a command like this:

    repo init -u git://github.com/DJBhardwaj/platform_manifest.git -b jb-mr1

Then to sync up:

    repo sync


Building
--------

Now run our build script:

    ./build-tb.sh -device-

example:

    ./build-tb.sh mako
