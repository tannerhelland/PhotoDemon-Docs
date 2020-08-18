---
title: Download PhotoDemon
nav_order: 1
parent: Getting started
---

## Downloading PhotoDemon

Before using PhotoDemon, you first need to download it!  The latest PhotoDemon release can always be downloaded at [photodemon.org/downloads](https://photodemon.org/download/).

Two versions of the application are always available: a **stable release**, and a **nightly release**.

*(If a new stable release is imminent, a **beta release** may also be available.  Beta releases are nightly releases that have been aggressively tested, and we think it's almost ready to become the new stable build.  If you see a beta release available for download, consider downloading it and providing us with any feedback you may have!)*

## Stable release 

Stable releases are the "safest" version of PhotoDemon.  They have been aggressively tested by PhotoDemon's developers and thousands of users, and they do not ship with any known bugs.

You can [download the latest stable release here](https://photodemon.org/download/).

## Nightly release

Every night, a new *Nightly* release is built from PhotoDemon's current source code.  Nightly releases often contain new tools, effects, and user-interface improvements, but because they are constantly evolving, they may contain bugs or regressions.

You can [download the latest nightly release here](https://photodemon.org/download/).

## When are new Stable releases uploaded?

Several times a year (ideally - sometimes it's less frequent), PhotoDemon's developers stop adding new features and spend a few weeks aggressively testing the current nightly release.  This is accompanied by a [public beta release](https://en.wikipedia.org/wiki/Software_release_life_cycle#Beta) which anyone can download to join in the testing.

Once all known bugs are resolved, that nightly build is promoted to the new stable build!

## Which version should you download?

It's really a matter of personal preference.

If you prize **stability** over cutting-edge features, download the **stable** version.

If you prize **cutting-edge features** over stability, download the **nightly** version.  

Importantly, if you are ever unhappy with either version, **please [let us know](https://photodemon.org/about/)**!  We want PhotoDemon to provide a great experience for everyone, and we can't do that if we don't know when users are unhappy.

## Switching between PhotoDemon versions

Because PhotoDemon is a *portable application*, you can download and keep as many different copies as you want.  (For example, PhotoDemon's developers keep dozens of different copies on hand, ranging from the program's first release to its latest nightly build.)  

So don't feel "trapped" into using a single version of the program.  If you want, download the latest stable build *and* nightly build.  After trying them, keep whichever one you like best!

If you only keep a single copy of the program, you can also switch between stable and nightly builds using the `Tools > Options > Updates` dialog.

*screenshot TBD*

These settings tell PhotoDemon which versions of the program are okay to update.  You can change these settings at any time.  

If you are currently using a stable build, and you change this setting to `stable, beta, and developer builds`, PhotoDemon will update to the latest nightly build the next time it checks for updates.  (*When* it checks for updates is controlled by the other setting on this page.  You can also force it to check for updates by clicking the `Help > Check for updates` menu.)

If you are currently using a nightly build and you want to switch back to the last stable release, please note that PhotoDemon will *stop* downloading nightly build updates - but it *will not* download a stable release until it finds one that is *newer* than the current nightly build.

Said another way, PhotoDemon *never* updates to an older version of itself.  This is for simple stability reasons - when using a nightly build, many new settings and features are saved to the program's settings files.  If PhotoDemon were to download an old version of itself - one that didn't understand those new settings and features - it might become unstable, defeating the entire purpose of using a stable build in the first place.

So if you're currently using a nightly build and you want to return to the last stable build, you will need to manually download the current stable release from [photodemon.org](https://photodemon.org/download/).

[Continue to Installing PhotoDemon](./install-photodemon)
