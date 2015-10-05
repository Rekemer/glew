GLEW - The OpenGL Extension Wrangler Library

  http://glew.sourceforge.net/
  https://github.com/nigels-com/glew

[![Build Status](https://travis-ci.org/nigels-com/glew.svg?branch=master)](https://travis-ci.org/nigels-com/glew)

If you downloaded the tarball or zip archive from the GLEW website,
you just need to:

  Unix:
    * make
    * sudo -s
    * make install
    * make clean

  Windows:
    use the project file in build/vc12/

If you wish to build GLEW from scratch (update the extension data from
the net or add your own extension information), you need a Unix
environment (including wget, perl, and GNU make).  The extension data
is regenerated from the top level source directory with:

  make extensions

An alternative to generating the GLEW sources from scratch is to
download a pre-generated (unsupported) snapshot:

  https://sourceforge.net/projects/glew/files/glew/snapshots/

Travis-built sources are also available:

  https://glew.s3.amazonaws.com/index.html