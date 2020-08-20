---
title: Start PhotoDemon for the first time
nav_order: 3
parent: Getting started
---

## Start PhotoDemon for the first time

The first time you run PhotoDemon, there may be a short delay as Windows performs a security scan.  (This is standard behavior on Windows 10.  Microsoft calls this feature [Microsoft Defender SmartScreen](https://docs.microsoft.com/en-us/windows/security/threat-protection/microsoft-defender-smartscreen/microsoft-defender-smartscreen-overview).)  PhotoDemon has no control over this initial scan, so please be patient as Windows "does its thing."

Once the scan finishes, Windows may raise a warning window.  At the time of this writing, it looks something like this:

*Screenshot TBD*

To allow PhotoDemon to run, you must click the *instructions forthcoming*.

Note that these steps are only required the **first** time you run PhotoDemon.  After that, it will run without requiring a confirmation prompt.

## What are PhotoDemon's system requirements?

PhotoDemon doesn't have any system requirements.  (Seriously!)

It will run on any Windows PC built in the past 20 years.  All it requires is an up-to-date copy of Windows XP or later.

Like all photo editing software, more memory or a faster processor will help the program run more smoothly, but no matter how old your Windows PC is, PhotoDemon can still run on it.

Similarly, if you upgrade to a new PC, PhotoDemon will run just great on that, too.  Even better, you can copy your PhotoDemon folder between any Windows PCs - even different versions - without trouble.  This is what we mean when we say PhotoDemon is "100% portable."  No matter the Windows version, and no matter the underlying PC, PhotoDemon will always *just work.*

## When I run PhotoDemon, what will it access on my PC?

PhotoDemon requires access to two folders on your PC.

**1) A folder for persistent data**, where the program can store things like user preferences, recently accessed files, and tool settings.  By default, PhotoDemon uses the `\Data` subfolder wherever you extracted PhotoDemon.exe.  (So if you run PhotoDemon from `C:\PhotoDemon\`, your settings get saved to `C:\PhotoDemon\Data\`.)

**2) A folder for temporary data**, like Undo states while editing a photo.  By default, PhotoDemon uses the system temp folder (typically `C:\Users\[your username]\AppData\Local\Temp`).  You can change this location from the `Tools > Options` menu.  This data is erased when you close the application.

PhotoDemon keeps these two folders separate for performance reasons, but if you want, you can set them to the same folder and the program will still work just fine.

[Continue to Edit your first photo](./)
