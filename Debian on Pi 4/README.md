# Scripts to Assist in Booting Vanilla Debian 11 (or later) on your Pi 4

<!-- I just like to write code/automate things/automate my writing code. And I like to help people. I also like to try and accomplish both at the same time. -->


## EZ Mode

If you aren't 100% sure what you're doing or have never done this before, this is the script for you. Probably. At least once.

This script downloads the ISO and RPi UEFI firmware files for you, and does the rest. You simply need to provide the path of the device you will be making the bootable with. **This script will delete all partitions on the device you specify, so make sure you back up anything you don't want to lose.**

###### How to Use This Script

Just run it: `./ezasdebianpi`

It will prompt you for the necessary info accordingly.

#### Post-Install

There are a few post-install tweaks that the script can't do for you, so don't forget to take care of them. Namely, disabling the 3 GB RAM limit in your UEFI settings on your Pi 4, so that you can use all 4 or 8 GB of your Pi 4.

#### Further Reading

The guide I followed initially (author is Akeo, and the guide is pretty thorough): https://www.raspberrypi.org/forums/viewtopic.php?t=282839