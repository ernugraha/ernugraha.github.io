---
layout: post
title: Installing Raspberry Pi OS WIP
subtitle: How to install default OS for Raspberry Pi
tags: [raspberry-pi, linux, operating-system]
comments: true
mathjax: false
author: ernugraha
---

{: .box-note}
Tested on Raspberry Pi 5 Model B, should work on CM5, 500, and Pi 4


## Introduction

Perhaps some of you are still confused about how to install the Raspberry Pi operating system on the Raspberry Pi itself. So, I'll teach you in this article.

### Table of Content

- [Installing Pi Imager](#installing-pi-imager)
- [Flashing Images](#flashing-images)
- [Customize the OS](#customize-the-os)


## Installing Pi Imager
1. Navigate to [this](https://www.raspberrypi.com/software/) website (click it)
2. Download the latest version as an AppImage. Make the AppImage executable.
3. Run AppImage as root
4. Launch.

## Flashing Images
1. In the **Device** tab, select your Raspberry Pi model from the list. Select **Next.**

2. In the **OS** tab, select **Raspberry Pi OS (64bit)**
<img src="/assets/img/os/pi/img1.png" alt="drawing" width="200"/>

3. Connect your preferred storage device to your computer. For example, plug a microSD card in using an external or built-in SD card reader.

4. In the **Storage** tab, select the device to write image to it. Select **Next**

{: .box-warning}
**Warning:** If you have more than one storage device connected to your computer, be sure to choose the correct device! You can often identify storage devices by size. If you’re unsure, disconnect other devices until you’ve identified the device you want to image. Imager warns you if you attempt to overwrite a system drive on your computer. 

## Customize the OS

<details markdown="1">
<summary>Sources</summary>
https://www.raspberrypi.com/documentation/
https://www.raspberrypi.com/documentation/computers/os.html
</details>
