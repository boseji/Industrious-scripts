MDP430-GCC-BUILD
================

This script helps to install the latest version of the MSP430 GCC compiler as well as LTS releases.
Iterative builds for updates is possible.

Here are the list of Assumption that this script would make in order work:

 *   The installation is default in the directory '$HOME/local/msp430gccinstall'. However this can be modified if desired at compile-time

 *   After installation the downloaded files and directories are not removed. Its up to the user to do as they please.

In case the build fails additional dependencies need to installed manually or added to this script.

## Pre-Built Image

 * [Not available yet !]()
 MSP430 GCC compiler on Ubuntu 12.04 - i386. This would install the compiler at `./local/msp430gccinstall`

This Image need to extacted at the User root `~` and `.bashrc` file needs to modified for adding MSP430 GCC to path.

For this add the following line into the `.bashrc` file:

`export PATH=$PATH:$HOME/local/msp430gccinstall`

