---
title: Install PhotoDemon
nav_order: 2
parent: Getting started
---

## Installing PhotoDemon

This page is a little silly, because PhotoDemon is a [portable application](https://en.wikipedia.org/wiki/Portable_application).  **It doesn't need to be installed!**

Instead, after [downloading the program](./download-photodemon), you just need to extract all files from the .zip file.  The easiest way to do this is by right-clicking the file you downloaded, then clicking `Extract all...` on the popup menu.

*Screenshot TBD*

Once PhotoDemon and its support files finish extracting, double-click the PhotoDemon.exe file (with the little camera icon) to start the application.

## Where should you extract PhotoDemon's files?

Anywhere you want, with one exception.

Most users extract PhotoDemon to an easily accessible location on their PC.  This might be your `Desktop` folder, `Documents` folder, or `Downloads` folder.  

Some users prefer to go truly portable by extracting PhotoDemon to a USB drive or SD card.  This is 100% okay.  PhotoDemon works just fine on removable media!

The one place you **should not** extract PhotoDemon is to **a system folder that requires administrator rights**.  This includes folders like `C:\Windows\` and `C:\Program Files\`.  

To protect your PC, Windows aggressively locks down operations in these folders.  Programs are not allowed to operate in these locations without raising User Access Control (UAC) prompts, like this:

*Screenshot TBD*

One of the key features of portable apps like PhotoDemon is that they *never* require administrator access.  In fact, PhotoDemon's developers explicitly designed it to require *minimal* access to your PC - both for your peace of mind, and theirs!  

So please, do not place PhotoDemon in restricted system folders.  

## I extracted PhotoDemon to a folder on my PC, but the application won't start.  What's wrong?

Here are a few things to double-check.

1) You did read the section just above this one, right?  The one about never running PhotoDemon from a restricted folder?  (Just checking!) 
2) Did you extract `PhotoDemon.exe` *and* the other files in the downloaded .zip?  You need to extract the /App subfolder too - it contains things like language files and visual themes, which PhotoDemon requires to run.
3) Did you use 3rd-party software to extract things from the .zip file?  (An application like WinZip, for example?)  3rd-party programs have their own settings, and they can incorrectly modify the folder structure embedded in PhotoDemon's .zip file.  If you don't see an /App subfolder next to PhotoDemon.exe, you should re-extract the application using Windows itself, not a 3rd-party app.

In our experience, 99.9% of startup problems are caused by the three issues above. If you've verified all those and PhotoDemon still doesn't start, try downloading it one more time.  (Maybe something went wrong with your Internet connection, and the file didn't download correctly.)  If that still fails, please [get in touch](https://photodemon.org/about/) so we can investigate.

[Continue to Running PhotoDemon for the first time](../first-run)
