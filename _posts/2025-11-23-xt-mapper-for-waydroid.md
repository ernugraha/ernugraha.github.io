---
layout: post
title:  "XtMapper for Waydroid"
description: this article explains about xtmapper for waydroid.
---
Many people who install Waydroid are confused when playing Android games. How can they control their games when their computer isn't a touchscreen? The solution is to use XtMapper by Xtr126. However, many people are also confused as to why it doesn't work, such as not receiving any input from the keyboard. Therefore, I wrote this article for those of you who are confused about how to set it up.

# Table of contents
- [What you need](#what-you-need)
- [nstallation of XtMapper](#installation-of-xtmapper-apk)
- [Flash the OS](#flash-the-os)
- [Final](#final)
- [Source](#image-source)

# What you need
- of course waydroid itself
- XtMapper apk (install to your waydroid)
- cage-xtmapper

# Installation of XtMapper apk
This is important because many people forget to install this when trying to do what this docs teaches, namely they run cage-xtmapper without the xtmapper APK itself which causes this to happen.

```error: No XtMapper installation found.```

To overcome this, you need to download this apk first.

### [Download by clicking here](https://github.com/Xtr126/XtMapper/releases)

Select the latest version. Once you've downloaded it, do one of these things:

### From waydroid
If you download the apk in Waydroid, just open the apk.

### From the desktop
If you downloaded it from your desktop, run this command:

$```cd Downloads #locate your download location```
$```waydroid app install XtMapper*.apk```

After that, go to the next step.

# Install the cage xtmapper

### Step 1
Download v0.2.0 - For modern distros with wlroots v0.18 or newer - Ubuntu 25.04 (plucky), Debian Sid, Arch, Fedora, Alpine

    curl -fOL --retry 3 --retry-delay 3  "https://github.com/Xtr126/cage-xtmapper/releases/latest/download/cage-xtmapper-v0.2.0.tar"

Download v0.1.5 - For slightly older distros with wlroots v0.17.x - Ubuntu 24.04 (noble), Debian 13 (Trixie)

    curl -fOL --retry 3 --retry-delay 3  "https://github.com/Xtr126/cage-xtmapper/releases/latest/download/cage-xtmapper-v0.1.5.tar"

### Step 2
To install from the downloaded tarball:

```    tar xvf cage-xtmapper*.tar
    cd /usr/local/bin
    sudo install -Dm755 ./cage_xtmapper /usr/local/bin/
    sudo install -Dm755 ./cage_xtmapper.sh /usr/local/bin/ ```

## After that
run the cage-xtmapper by

$```/usr/local/bin/cage_xtmapper.sh```