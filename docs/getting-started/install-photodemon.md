---
title: Install PhotoDemon
nav_order: 2
parent: Getting started
---

## Installing PhotoDemon

This help page is a little silly, because PhotoDemon is a **[portable application](https://en.wikipedia.org/wiki/Portable_application).**  It doesn't need to be installed!

Instead, after [downloading the program](./download-photodemon), you simply need to extract all program files from the .zip file you downloaded.  The easiest way to do this is by right-clicking the downloaded file, then selecting `Extract all...` from the popup menu.

*Screenshot TBD*

Once PhotoDemon and all of its support files have been extracted, click on the extracted PhotoDemon.exe file (with the little camera icon) to start the application.

## Where should I extract PhotoDemon's files?

Anywhere you want, with one exception.

Most users extract PhotoDemon's files into an easily accessible location on their PC.  This might be the Desktop folder, the Documents folder, or the Downloads folder.  

Some users prefer to go truly portable with PhotoDemon, by extracting it to a USB drive or SD card.  This is 100% okay.  PhotoDemon was designed to work just fine on removable media.

The one place you should **not** extract PhotoDemon is to a **system folder** that requires **administrator rights**.  This includes folders like `C:\Windows\` and `C:\Program Files\`.  

For security reasons, these system folders are strictly locked down by Windows.  Programs are not allowed to modify them without prompting you with a User Access Control (UAC) prompt, like this:

*Screenshot TBD*

One of the key features of portable apps like PhotoDemon is that they *never* require administrator access to run.  In fact, PhotoDemon's developers explicitly designed the app to require as little access to your PC as possible - both for your peace of mind, and theirs!  

To run properly, PhotoDemon only needs access to one, possibly two locations:

1) Its own folder, where it stores things like your preferences and program settings.  Program updates are also downloaded here.
2) Optionally, a temporary folder (which can be located inside the same folder as (1) if you want).  

A temporary folder is required for per-session data like Undo/Redo data.  By default, PhotoDemon will use the current user's temp folder (typically a subfolder in `C:\Users`), but you can set your own location from the `Tools > Options` menu.

PhotoDemon automatically erases all of its data from this temporary folder whenever the app is closed.




[Continue to Running PhotoDemon for the first time](./first-run)
