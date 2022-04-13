# usbtv-2.1-k4x
Fushicai USBTV007 Driver for CentOS 8 (including audio)

This is a simple modification of the Linux Kernel GPL licensed driver for the fushicai USBTV007 video capture device suitable for use with CentOS 8 (kernel 4.x), including the capture of audio and video. No attempt was made to make this software robust to buffer overflow errors, etc, so use on an unprotected network at your own risk!

Download source to /usr/src/usbtv-2.1. Then install using dkms: dkms install usbtv/2.1. Note: Due to the fragility of dkms, you may need to rerun the install command (possibly with --force) after every kernel upgrade.

A version for versions of CentOS 7.0/1/2 is available at https://github.com/tmcqueen-materials/usbtv-2.0-k3x
