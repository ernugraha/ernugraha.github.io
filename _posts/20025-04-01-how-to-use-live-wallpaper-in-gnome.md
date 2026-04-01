---
layout: post
title: How to install live wallpaper for Gnome
subtitle: Well, this might make your Gnome different.
tags: [operating-system, linux]
comments: true
author: ernugraha
---

{: .box-note}
Tested on Ubuntu 25.0 running GNome 49.

## Introduction

Live wallpapers (moving wallpapers) are used to enhance the visual aesthetics of a device, making it more dynamic, personal, and modern than static images. In this tutorial ill teach you how to install live wallpaper extension for GNome!

### Table of Content
- [Introduction](#introduction)
- [Set up the dependencies](#set-up-the-dependencies)
- [Flashing Images](#flashing-images)

## Set up the dependencies
1. Install this packages:
```
sudo apt install gnome-shell-extension-manager git meson ibgtk-4-media-gstreamer
```

2. Next, we will installling extension.

- For GNOME 45 and later
```
git clone https://github.com/jeffshee/gnome-ext-hanabi.git
```

- For GNOME 44 and earlier (are you still using it?)
```
git clone https://github.com/jeffshee/gnome-ext-hanabi.git -b legacy
```

3. Run the installation script
```
cd gnome-ext-hanabi
./run.sh install
```


After that, restart GNOME Shell.

## Setting up the extension

1. Open **GNOME Extension Manager**

<img src="/assets/img/os/gnome/live-wall/1.png" alt="extension" width="320"/>

2. Enable Hanabi Extension (the Live Wallpaper CORE)

<img src="/assets/img/os/gnome/live-wall/2.png" alt="extension-enable" width="320"/>

3. Choose your video wallpaper in the extension preference window

And DONE!!