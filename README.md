AOKP_Vigor
==========

Manifest for HTC Rezound needed for building AOKP

To initialize your local repository using the Vigor Device trees, run:

    repo init -u https://github.com/VigorAOKP/aokp_manifest.git -b jb-mr1

Then to sync up:

    repo sync

To avoid conflicts remove this directory:

    device/htc/vigor/overlays/packages/Settings

Then on to build:

    . build/envsetup.sh && brunch vigor

Enjoy!
