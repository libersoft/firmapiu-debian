FirmaPiù Debian
======
FirmaPiù Debian is a repository of debian packages linked to FirmaPiù software, it contains
* __firmapiu__, a metapackage installing everything needed
* __firmapiu-gui__, the GUI for the firmapiu-daemon, written in Python v3.4
* __firmapiu-daemon__, the daemon using firmapiu-lib, written in Java
* __firmapiu-lib__, the library providing all the classes needed to handle the cards and to operate on them, written in Java
* __firmapiu-cli__, CLI interface to the daemon, written in Java
* __smartcard-driver__, a simple script that downloads and installs the libraries needed to use Incard/Oberthur and Athena smartcard and depends on OpenSC and ACS ACR38U to support other models

The repo doesn't contain the packages themselves, instead it provides the debian folder for every project so it's enough to download the software, put it in its own folder and simply launch `debuild`
