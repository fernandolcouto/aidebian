## VirtualBox

At the time of writing these notes (2021/04), the stable version of Debian is 10.9 "*Buster*" and the *Sid* version, or *Testing* (equivalent to Beta), is "*Bullseye*".

The Debian wiki page contains instructions for both versions. The procedure for the *Testing* version is shown below.

Add the "**contrib**" and the "**non-free**" components to **/etc/apt/sources.list**:


** deb http://httpredir.debian.org/debian/ sid main contrib non-free**

Packages for VirtualBox are not available in Debian 10 "*Buster*".  
So, You can install Virtualbox either using Lucas Nussbaum's repository or Virtualbox's official third-party repository.  

**Source:**


* [Wiki Debian / VirtualBox](https://wiki.debian.org/VirtualBox)
