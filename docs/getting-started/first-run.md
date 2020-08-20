---
title: Running PhotoDemon for the first time
nav_order: 3
parent: Getting started
---

## Running PhotoDemon for the first time

The first time you run PhotoDemon, there may be a short delay as Windows performs a security scan.  (This is standard behavior on Windows 10; Microsoft calls this feature [Microsoft Defender SmartScreen](https://docs.microsoft.com/en-us/windows/security/threat-protection/microsoft-defender-smartscreen/microsoft-defender-smartscreen-overview).)  PhotoDemon has no control over this behavior, so please be patient as Windows "does its thing."

Once the scan finishes, Windows will raise a warning window.  On Windows 10, it looks something like this:

*Screenshot TBD*

To run the application, you will need to click the *instructions forthcoming*.

Note that these steps are only required the **first** time you run PhotoDemon.  

*(One exception is when running PhotoDemon from a portable drive or SD card.  If you remove the drive or card from your PC, Windows may raise these security prompts again if the device is re-inserted.)*

## What are PhotoDemon's minimum system requirements?

There are none.  (Seriously!)

PhotoDemon will run on any Windows PC built in the past 20 years.  All it requires is an up-to-date copy of Windows XP or later.

As with any app, more memory and a faster processor will provide a smoother experience, but no matter how old your Windows PC is, PhotoDemon can run on it.  We still regularly test on ancient PCs to make sure of this!

## What does PhotoDemon try to access on my PC?

To run properly, PhotoDemon needs access to one, possibly two locations:

1) Its own folder, so it can store things like your program preferences and settings.  Program updates (if you enable them) will also be downloaded here.
2) A temporary folder for storing Undo/Redo data (which can be located inside the same folder as (1), if you want).  

By default, PhotoDemon stores your program preferences and settings inside a /Data subfolder in the same folder as PhotoDemon.exe.  

Also by default, PhotoDemon will use the system's recommended temp folder (typically a folder like `C:\Users\[your username]\AppData\Local\Temp`) for Undo/Redo data.  You can set your own location from the `Tools > Options` menu.

PhotoDemon automatically erases all of its data from this temporary folder whenever the app is closed.






[Continue to TBD](./)
