AOKP_Vigor
==========

Manifest for HTC Rezound needed for building AOKP

To initialize your local repository using the Vigor Device trees, run:

    repo init -u https://github.com/VigorAOKP/aokp_manifest.git -b jb-mr1

Then to sync up:

    repo sync

To build:

    . build/envsetup.sh && brunch vigor

Enjoy!
