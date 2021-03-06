# emax64
Emacs for w64

Clean and optimized build of Emacs for Windows x86-64 systems.
Compiled with support for: jpg/jpeg, gif, png, tiff, xpm and more.
ImageMagick 7 support compiled, binaries, and libraries included.

Get binaries here: https://github.com/m-parashar/emax64/releases

emax64-20180302
---------------

* 64-bit Windows build of Emacs 26.0.91. DLLs included.
* Patched with ImageMagick 7 support. Binaries and libs included.
* PDF-TOOLS (epdfinfo.exe) included.
* Features[1]: "XPM JPEG TIFF GIF PNG RSVG IMAGEMAGICK SOUND NOTIFY ACL GNUTLS LIBXML2 ZLIB TOOLKIT_SCROLL_BARS MODULES THREADS LCMS2"
* Optimized clean build. Options[2]: "--without-compress-install --without-dbus --with-modules 'CFLAGS= -O2 -pipe -s -g0' 'LDFLAGS= -s '"[3]
* Built and tested on a clean Windows 10 system.
* addpm modified to not create/update any registry HOME entries. It only creates shortcuts as it should.

* [1] C-h v system-configuration-features
* [2] C-h v system-configuration-options
* [3] DEBUG build options: "--without-compress-install --without-dbus --with-modules 'CFLAGS= -O2 -pipe -static -g3'"


**Installation:**

* Unpack the 7z binary archive, preferably in C:\ root directory.
* Double-click the addpm.exe file in emacs\bin to create shortcuts.

**OPTIONAL:**

* Download and unpack emax.7z into your HOME directory. Usually C:\Users\<username>\AppData\Roaming
* emax.7z is an environment to make your Emacs experience a little more tolerable on Windows.
* It includes a very basic dotfile along with BusyBox 64-bit, some MinGW packages, SSH, W3M, and some other GNU tools to help you start right away.

![emax64 on Windows 10](https://i.imgur.com/ZAKxAF7.png)
