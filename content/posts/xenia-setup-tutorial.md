---
title: "Xenia Setup - Tutorial"
date: 2023-01-16T13:21:08-05:00
draft: false
tags: [tutorials]
authors: ["HouseholdVTuber"]
---
<!--more-->
![The Xenia Logo](https://repository-images.githubusercontent.com/7550637/e819cd00-6d5a-11e9-9633-e837c2ffe515)

# Introduction
Hello and welcome to my little tutorial on setting up the "Xenia" Xbox 360 emulator! This article is intended to serve as a Getting Started guide, one which takes the least complicated path to running an acceptable 360 emulation experience on your PC.

## Step 1 - Download Xenia
Unless yours is a special circumstance outside the scope of this article, you'll want to download the latest release of Xenia for Windows. The project is ever-evolving and hosted on Github, so a direct link would likely be deprecated some time after this writing. You can most reliably download the latest release from the project's [Github repository](https://github.com/xenia-project/release-builds-windows). Scroll down to the contents of the README.md and you'll see a *Latest* hyperlink, pictured below:

![Link to Latest Xenia](https://i.imgur.com/rVfFcZS.png)

On the following page, click on the *xenia_master.zip* file link to start your download. The version tag at the top may differ from this screenshot, but don't be alarmed:

![Current Latest](https://i.imgur.com/opVzyCV.png)

## Step 2 - Unzip the xenia_master.zip contents
Once you've downloaded the latest *xenia_master.zip*, you'll need to extract its contents somewhere. Feel free to put these anywhere you want; in this case, I chose to make a "xenia" folder on the root of my C:\ drive:

    C:\xenia

![Xenia folder contents](https://i.imgur.com/3q1fKCQ.png)

Your folder doesn't have to be named "xenia" exactly, but its contents should look like this.

## Step 3 - The Optional, but Very Recommended Portable.txt
As of this writing, Xenia does not have a mature GUI. Most of the configuration is done through Notepad++, or whatever text editor you choose, and config files. And while it isn't required, Dear Reader, I advise you to add a "portable.txt" file to your xenia folder alongside those initial 3 files so that your folder structure looks like this:

![Xenia folder contents with Portable.txt](https://i.imgur.com/ytqRtpC.png)

You don't need to write anything into the file. As long as Xenia detects a *portable.txt* in its running directory, then it will publish your save files to a "content" subfolder in this directory (it will make this directory for you when you save something). By default it will try to save your games to that weird forest of app data in your user files; if you've used Windows a lot in the last decade, you'll know what I'm talking about. This can cause issues with certain games and, since Xenia doesn't actually "install" itself as an application or touch the registry anyway, I think it's cleaner to keep all of your Xenia stuff in one place.

## Step 4 - Find a game and launch Xenia!
This should be the part where I tell you that I can't actually link to the ISO or ROM images, but to test your Xenia setup, just grab the PAL Sonic the Hedgehog 2006 game .ISO from [The Internet Archive](https://archive.org/details/sonic-the-hedgehog-2006-xbox-360). This game's been delisted from every storefront and Sega seems content to keep it that way, and I trust Archive.org as a host. This page should have a link to download the 7Zip archive, pictured below:

![7Z Link](https://i.imgur.com/Bk90Buu.png)

If you don't already have 7Zip installed as an archive software, feel free to go download and install it from [7-zip.org](https://www.7-zip.org/). You may use any file archiver which supports the .7z extension, or source your own ISO. Though when it comes to finding this stuff, be wary of malicious sites. I can't assume responsibility for what happens to your computer if you download Crackdown.iso.exe from a malicious source!

However you go about it, make sure the .ISO image of the game you want to play is placed somewhere that Xenia can open it from (that means, outside of the 7z archive or any similar compression format). Now go ahead and double-click the *xenia.exe* in your xenia folder!

## Step 5 - Open your game ISO with Xenia
Xenia will open to a black screen.  Don't be alarmed, just click [File] along the top and then *Open...*

![Xenia Start Screen](https://i.imgur.com/Zv5iRty.png)

... This will open a Windows File Explorer window. Navigate to your .ISO image (in our case, *Sonic the Hedgehog [PAL][NTSCU].iso*) and click it.

## Step 6: Troubleshoot and Enjoy!

![Sonic Title Screen](https://i.imgur.com/HjihEPk.png)

... And there you go! This concludes the "Getting Started" tutorial, but I'll be adding random tips below to help resolve common issues. Assuming your PC has decent "gaming" specs (I'm sporting an old GTX 1070 myself), you shouldn't have to finangle much to get Sonic 2006 running well - or, as well as one can reasonably expect Sonic 2006 to run. You should notice drastically reduced loading times compared to the native hardware experience!

### Helpful Links
[The Xenia Project FAQ](https://github.com/xenia-project/xenia/wiki/FAQ)

[The Game Compatibility List](https://github.com/xenia-project/game-compatibility/issues)
* This list is especially helpful for troubleshooting specific games. Type the game's name into the search bar, click the result, and you'll likely find plenty of comments related to it. 