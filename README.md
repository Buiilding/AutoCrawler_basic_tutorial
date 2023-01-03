# AutoCrawler_basic_tutorial

Git clone auto crawl image is an automated tool for finding images by keywords.

# Step 1 : Download git 

For Windows : https://github.com/git-for-windows/git/releases/download/v2.39.0.windows.2/Git-2.39.0.2-64-bit.exe

For Mac : 

Homebrew
Install homebrew if you don't already have it, then:
$ brew install git

MacPorts
Install MacPorts if you don't already have it, then:
$ sudo port install git

Xcode
Apple ships a binary package of Git with Xcode.

Binary installer
Tim Harper provides an installer for Git. The latest version is 2.33.0, which was released over 1 year ago, on 2021-08-30.

Building from Source
If you prefer to build from source, you can find tarballs on kernel.org. The latest version is 2.39.0.

Installing git-gui
If you would like to install git-gui and gitk, git's commit GUI and interactive history browser, you can do so using homebrew
$ brew install git-gui

For Linux :

 apt-get install git
For Ubuntu, this PPA provides the latest stable upstream Git version

 add-apt-repository ppa:git-core/ppa # apt update; apt install git
Fedora
 yum install git (up to Fedora 21)
 dnf install git (Fedora 22 and later)
Gentoo
 emerge --ask --verbose dev-vcs/git
Arch Linux
 pacman -S git
openSUSE
 zypper install git
Mageia
 urpmi git
Nix/NixOS
 nix-env -i git
FreeBSD
 pkg install git
Solaris 9/10/11 (OpenCSW)
 pkgutil -i git
Solaris 11 Express
 pkg install developer/versioning/git
OpenBSD
 pkg_add git
Alpine
$ apk add git
Red Hat Enterprise Linux, Oracle Linux, CentOS, Scientific Linux, et al.
RHEL and derivatives typically ship older versions of git. You can download a tarball and build from source, or use a 3rd-party repository such as the IUS Community Project to obtain a more recent version of git.

Slitaz
$ tazpkg get-install git

# Step 2 : Open terminal 

 1: Create a new folder named datatools

 2: cd , forward to the datatools driver

 3: download the link below

-  https://github.com/YoongiKim/AutoCrawler.git

Command : git clone pip https://github.com/YoongiKim/AutoCrawler.git

- Once you have done that, a Folder named AutoCrawler can be seen

# Step 3 : Install all of the requirements.txt

- Command : pip install -r requirements.txt 

# Step 4 : Hop into VScode 

- Open AutoCrawler folder

- Open keywords.txt

- Enter the keyword that you want the tool to autosearch and press save

# Step 5 : Hop back into terminal and run main.py

- Command: python main.py

