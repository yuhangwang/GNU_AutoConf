# GNU_AutoConf
**GNU AuoConf: an extensible package of M4 macros that produce shell scripts to automatically configure software source code packages**


This is an unofficial verbatim redistribution of the binary&source form of the GNU Autoconf under its open source license (GPL 2.0) terms (see the LICENSE file).

This redistribution is under the same license as the original.

Please visit the official website for more details: http://www.gnu.org/software/autoconf/autoconf.html

## Download
You can download the compiled binary files at the [release page](https://github.com/yuhangwang/GNU_AutoConf/releases).

## Compilation notes
### Compilation environment
* CentOS 6.6
* x86_64 architecture
* Compiler: gcc version 4.4.7 20120313 (Red Hat 4.4.7-11)

### Compilation steps
#### Version: 2.64 (2009)
```bash
wget http://ftp.gnu.org/gnu/autoconf/autoconf-2.64.tar.gz
tar xvf autoconf-2.64.tar.gz
mkdir build_autoconf-2.64
cd build_autoconf-2.64
../autoconf-2.64/configure --prefix=/home/steven/install/autoconf/2.64
make -j16
make check -j16 | tee QualityVerification.txt
make install
```

#### Version: 2.69 (2012)
```bash
wget http://ftp.gnu.org/gnu/autoconf/autoconf-2.69.tar.gz
tar xvf autoconf-2.69.tar.gz
mkdir build_autoconf-2.69
cd build_autoconf-2.69
../autoconf-2.69/configure --prefix=/home/steven/install/autoconf/2.69
make -j16
make check -j16 | tee QualityVerification.txt
make install
```

### Quality verification
See the "QualityVerification.txt" for the output of "make check".
