## ghostscript

Ghostscript is an interpreter for PostScript and Portable Document Format (PDF) files.

### Installing Ghostscript on Linux

Ghostscript uses the common configure, build and install method common to many modern software packages. In general the following with suffice to build Ghostscript:
```
./configure
make
```
and then it may be installed in the default location with:
```
make install
```
This last command may need to be performed with super user privileges.

You can set the installation directory by adding `--prefix=path` to the configure invocation in the first step. The default prefix is `/usr/local`, which is to say the gs executable is installed as `/usr/local/bin/gs`.

A list of similar configuration options is available via `./configure --help`.
