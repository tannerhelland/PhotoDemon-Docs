---
title: Download PhotoDemon
nav_order: 1
parent: Getting started
---

## Downloading PhotoDemon

Before using PhotoDemon, you first need to download it!  The latest PhotoDemon release can always be downloaded at [photodemon.org/downloads](https://photodemon.org/download/).

Two versions of the application are always available: a **stable release**, and a **nightly release**.

(If a new stable release is imminent, a **beta release** may also be available.  A beta release is a nightly release that has been aggressively tested, and we think it's ready to become the new stable build.  If you find a beta release available for download, consider trying it and providing us with your feedback!)

## Stable releases 

Stable releases are the "safest" version of PhotoDemon.  They have been aggressively tested by many developers and users, and they do not ship with any known bugs.

You can [download the latest stable release here](https://photodemon.org/download/).

## Nightly releases

Every night, a new *Nightly* release is built from PhotoDemon's current source code.  Nightly releases often contain new tools, effects, and user-interface improvements, but because they are constantly evolving, they may contain bugs or regressions.

You can [download the latest nightly release here](https://photodemon.org/download/).

## Which version should you download?

It's really a matter of personal preference.

If you prize **stability** over cutting-edge features, download the **stable** version.

If you prize **cutting-edge features** over stability, download the **nightly** version.  

Importantly, if you are ever unhappy with either version, **please [let us know](https://photodemon.org/about/)**!  We want PhotoDemon to provide a great experience for everyone, and we can't do that if users don't tell us when they're unhappy.

## Switching between PhotoDemon versions

Because PhotoDemon is a *portable application*, you can download and keep as many different copies as you want.  (For example, PhotoDemon's developers keep dozens of different copies on hand, ranging from the program's first release to its latest nightly build.)

So don't feel "trapped" into using a single version of the program.  If you want, download the latest stable build *and* nightly build.  After trying them, keep whichever one you like best!

If you only have a single copy of the program on hand, you can also switch between stable and nightly builds using the `Tools > Options > Updates` dialog.

*screenshot TBD*

These settings tell PhotoDemon which versions it can update to.  You can change these settings at any time.  

If you are currently using a stable build, and you change this setting to `stable, beta, and developer builds`, PhotoDemon will update to the latest nightly build the next time it checks for updates.  (*When* it checks for updates is controlled by the other setting on this page.  You can also force the program to check for updates by clicking the `Help > Check for updates` menu.)

If you are currently using a nightly build and you want to switch back to the last stable release, please note that PhotoDemon will *stop* downloading nightly build updates - but it *won't* download a stable release until it finds one that is *newer* than the current nightly build.

Said another way, PhotoDemon *never* updates to an older version of itself.  This is for stability reasons - when using a nightly build, new tools and features are saved to the program's settings files.  If PhotoDemon were to download an old version of itself - one that doesn't understand those new settings and features - it might become unstable, defeating the entire purpose of using a stable build in the first place.

So if you're currently using a nightly build and you want to return to the last stable build, you will need to manually download the last stable release from [photodemon.org](https://photodemon.org/download/).

## When do we ship new stable releases?

Several times a year (ideally), PhotoDemon's developers stop adding new features and spend a few weeks aggressively testing the current nightly release.  This is accompanied by a [public beta](https://en.wikipedia.org/wiki/Software_release_life_cycle#Beta) that anyone can download to help with the testing.

Once all known bugs are resolved, that nightly build gets promoted to the new stable build.

The biggest variable in shipping new stable releases is actually... users like you!  The more people download and use PhotoDemon's nightly builds, the faster bugs and problems get resolved.  If PhotoDemon's developers have to do all the testing themselves, it takes much longer to ship a new stable release.

[Continue to Installing PhotoDemon](./install-photodemon)
