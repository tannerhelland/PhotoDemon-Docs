---
title: Download PhotoDemon
nav_order: 2
parent: Getting started
---

## Downloading PhotoDemon

Before using PhotoDemon, you first need to download it!  The latest PhotoDemon release can always be downloaded at [photodemon.org/downloads](https://photodemon.org/download/).

Two versions of the application are always available for download: a **stable release**, and a **nightly release**.

(If a new stable release is imminent, you may also see a **beta release** available for download.  This is a nightly release that has been aggressively tested, and PhotoDemon's developers think it's ready to become the new stable build.  If you're lucky enough to see a beta release, please consider downloading it and providing us with feedback before we promote it!)

## Stable release 

Stable releases are the "safest" version of PhotoDemon.  They receive the most testing and do not have any (known) serious bugs.

You can [download the latest stable release here](https://photodemon.org/download/).

## Nightly release

Every night, a new *Nightly* release is automatically built from PhotoDemon's current development source code.  Nightly releases can contain new tools, effects, and user-interface improvements since the last stable release, but because they are constantly evolving, they may contain bugs or regressions.

You can [download the latest nightly release here](https://photodemon.org/download/).

## When do nightly releases turn into stable release?

Several times a year (ideally - sometimes it's less frequent), PhotoDemon's developers stop adding new features and spend a few weeks aggressively testing the current nightly release.  This is often accompanied by a [public beta release](https://en.wikipedia.org/wiki/Software_release_life_cycle#Beta) which anyone can download and join in the testing.

Once all known bugs are resolved and the build endures a series of stress tests, it gets promoted as a new stable build!

## Which version should you download?

The answer to this question is really a matter of personal preference.

If you prize **stability** over cutting-edge features, download the **stable** version.

If you prize **cutting-edge features** over stability, download the **nightly** version.

## Switching between PhotoDemon versions

Because PhotoDemon is a portable application, you can download and run as many different copies as you want.  (For example, PhotoDemon's developers use a huge folder tree of different software versions, ranging from its first release to its latest nightly build.)  So you don't need to feel "trapped" into using a single version of the program.  If you want, download both the stable and nightly build, and keep using whichever one you like best!

If you want to use a single copy of the program, you can switch between stable and nightly build using the `Tools > Options > Updates` dialog.

*screenshot TBD*

These settings tell PhotoDemon which versions of the program it should automatically update to.  You can change these settings at any time.  

If you are currently using a stable build, and you change this setting to "stable, beta, and developer builds", PhotoDemon will look for a new nightly build the next time it automatically checks for updates.  (This is controlled by the other setting on this page, or you can force it to check for updates by clicking the `Help > Check for updates` menu.)

If you are currently using a nightly build and you want to switch back to stable releases only, please note that PhotoDemon will stop downloading nightly build updates - but it will *not* download a stable release until it finds one that is *newer* than the current nightly build.

Said another way, the program will *never* download an older version of itself.  This is for simple stability reasons - when using a nightly build, many new settings and features get saved to the program's settings files.  If PhotoDemon were to download an old version of itself - one that didn't understand those new settings and features - it might become unstable, defeating the entire purpose of using a stable build in the first place.

So if you're currently using a nightly build and you want to return to the last stable build, you will need to manually download a copy of the last stable build.

[Continue to Installing PhotoDemon](./)
