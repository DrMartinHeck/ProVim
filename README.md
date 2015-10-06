ProVim
======

Repository to hold dotfiles and scripts specific to ProVim

#Martin's comments:
After copying the fonts to .fonts in my home directory
I was able to use "fc-cache -fv" to install the fonts.
They became active only after restart of the X-server, e.g. restart.

Some plugins use cmake. There can be problems with the compiler version.
The following lines helped me to tell cmake, which compiler to use.

export CC= /.../gcc-4.5.2/bin/gcc/gcc
export CXX=/.../gcc-4.5.2/bin/gcc/g++
