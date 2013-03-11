SDCC-INSTALL
============

This script helps to install the latest version of the SDCC compiler

Here are the list of Assumption that this script would make in order work:

 *   The installation is always in the directory '$HOME/local/SDCC'

 *   All files are downloaded into '$HOME/local'
 
 *   Before and after installation the non required directory and files are removed

In case the build fails additional dependencies need to installed manually.

## Pre-Built Image

 * [Build Image available](https://github.com/AdharLabs/Industrious-scripts/tree/master/sdcc/sdcc-3.2.0-i386-ubuntu_12.04.tar.bz2)
for SDCC compiler on Ubuntu 12.04 - i386. This would install the compiler at `./local\SDCC`

This Image need to extacted at the User root `~` and `.bashrc` file needs to modified for adding SDCC to path.

For this add the following line into the `.bashrc` file:

`export PATH=$PATH:$HOME/local/SDCC`

