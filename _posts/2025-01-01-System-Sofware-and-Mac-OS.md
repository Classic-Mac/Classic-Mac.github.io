---
title: System Software and Mac OS
Author: Morten Harding
date: 2025-01-01
category: Jekyll
layout: post
---


### What version(s) of the Mac OS will run on my Mac?


The Apple Museum at Bott has a page of version history on the very early Mac OS versions.

- [A page of version history](http://applemuseum.bott.org/sections/os.html)

### What versions of the Mac OS are available online?

Various versions of the Mac OS from System 6 to Mac OS 7.5.5 are available for free online. All versions linked here are North American English versions unless otherwise indicated. If you need a non-English version, try searching Apple's Software Updates (but don't hope for much before System 7.5). French- and German- localised versions of system software prior to System 7 is available here. They also have English versions of most revisions of the OS before System 7. KanjiTalk, the Japanese version of the Mac OS, is available in pre-System 7 form here. Most System versions prior to 6.0 WERE available here, which still has many links to System software downloads but no longer hosts any of them. Early in 2001, Apple changed their licencing structure to cause the removal of all System Software prior to 6 from legal distribution. For more information, see Stuart Bell's Low End Mac article.

System versions 6.0.1, 6.0.2, 6.0.4, and 6.0.7 are no longer available from Apple, but it's not a big deal - System 6.0.8 will work just fine for most System 6.x installations. If you really need an earlier version of 6.x (possibly due to size constraints), well, they're there for you to get. System 7.0 is available direct from Apple.
System 7 Tune-up (HIGHLY recommended with the above two System versions) is available direct from Apple.

System 7.5.3 is available direct from Apple as a 19-part download (NOT disk images) requiring approximately 40MB of disk space. The Network Access Disk, a commonly requested item, can be found here.
System 7.5.5 Update (highly recommended for the above) is available direct from Apple.

- [System_6.x, 7.0.x, 7.1, 7.5 and updates direct from Apple](http://ftpmirror.your.org/pub/misc/apple/Apple_Software_Updates/English-North_American/Macintosh/System/Older_System/)
- [System_7.5.5 and newer updates direct from Apple](http://ftpmirror.your.org/pub/misc/apple/Apple_Software_Updates/English-North_American/Macintosh/System/)
- [Utilities available from Apple](http://ftpmirror.your.org/pub/misc/apple/Apple_Software_Updates/English-North_American/Macintosh/Utilities/)

Mac OS 7.6.1 Update (requires Mac OS 7.6, recommended for all 7.6 users) is available direct from Apple.

Mac OS 8.1 Update (requires Mac OS 8, recommended for all 8.0 users) is available direct from Apple.

### Which version of the Mac OS is best for my Mac?

I'll try to give a very generally applicable recommendation here, but specific questions are beyond the scope of this FAQ. In general, if a Mac can run up to 7.6.1, 7.1 is the ideal version for it. If it can run up to 7.6.1 and you need the features in 7.5.x and up, use 7.6.1. Most stock Macintoshes, in my experience are at their fastest with the version of the OS one generation previous to the maximum supported on that machine. (I'm not counting 7.5.x and 7.6.x as different generations, since 7.6.x was essentially a bug-fix and PPC code update to 7.5.x.) Note that these recommendations DO NOT apply to Macs upgraded with a faster/newer processor.

If you have a 128K, 512K, or 512Ke, check out the link to System Software prior to System 6 and pick one of the Systems listed as being for the 128K-Plus (NOT the Guided Tour disks). Which one you use really depends on what features you need.

If you have a Plus, SE (any model), or Classic, use System 6.0.8 unless you absolutely need the features of System 7. Why? System 6 Heaven has a good explanation.

If you have any 020- or 030-based Mac, 7.1 is generally the best for it but 7.5.x/7.6.x will run acceptably well; major exceptions are the IIfx, which runs well all the way to 8.1, and the LCs (including the Classic II and Colour Classic) prior to the LC III, which should NOT use anything past 7.1 if you want to keep your sanity.

Quadras are fastest with Mac OS 7.1 plus the extras mentioned below, but if you need HFS Plus support or have a PPC card, use Mac OS 8.1.

### What the heck is all this System Enabler stuff?

System Enablers are pieces of software that add support for certain machines to the Mac OS. For example, the IIvx came out after System 7.1 was finalised, and thus support for the IIvx is not built into System 7.1. The Enabler 001 file adds this necessary support, and a Mac IIvx will not boot under System 7.1 without it. If your Mac shipped with an enabler (check out AppleSpec to see if it did), make sure you don't remove that file from the System Folder. If you have extraneous Enablers, however, you can safely remove them. Check out Apple TIL Archive articles 11491 and 21176, which describe the current version of every System Enabler needed (as well as revision history) for nearly all Macs, before removing any Enablers from your System Folder. Note: the LC III+ is not on the list but should be the same as the Performa 460.

### What am I supposed to do with these disk image things?

Those "disk image things" require you to use Disk Copy 4.2 or Disk Copy 6.3.3 (both available from Apple) to mount them. If you want to make floppies from them, use the "Make Floppy" command in Disk Copy after mounting an image from within Disk Copy. And please, read the Disk Copy README file. It's really not that hard to do.

- [Utilities available from Apple](http://ftpmirror.your.org/pub/misc/apple/Apple_Software_Updates/English-North_American/Macintosh/Utilities/)

### How can I get an OS on a Mac using only my PC?

It's reasonably common that someone gets an old used Mac and it has no operating system on it. Often, these people don't have anything other than a PC to access the Internet. As long as your Mac is an SE FDHD or Mac IIx or higher, you can use these directions compiled by Alex Harrington (aka "fastkeys") to get that Mac up and running. Due to irreconcilable physical differences in the floppy drives of PCs and Macs, a Mac 128, 512, Plus, original SE, or un-upgraded II cannot use this procedure. If you have one of these, you'll need to get a Mac that can read PC floppies or find someone willing to make floppies for you.


### Is there a list of startup key combinations and what they do somewhere?

Startup key combinations - like holding down the shift key to disable extensions in System 7 and higher - are pretty well documented on the 'Net. Since Charles Poynton's site has disappeared completely, I've written a derivative work myself, based on his page but focused more on 68K Macs.


### What are those "extras" I should add to System 7.1 to make it more like 7.5?

First, install System 7.1 Update 3. Once you've done, you want to get the CFM-68K Runtime Enabler 4.0, ObjectSupportLib 1.2 (included with CFM-68K download), Drag Manager 1.1, and Thread Manager. Make sure you install Finder 7.1.3 as well; it's in the Thread Manager package, inside the Finder 7.1.3 folder.

When you get those installed, restart and then install Open Transport 1.1 and 1.1.2.

- [System 7.1 Update 3](http://ftpmirror.your.org/pub/misc/apple/Apple_Software_Updates/English-North_American/Macintosh/System/Older_System/For_System_7.1.x/)
- [CFM-68K Runtime Enabler 4.0](http://ftpmirror.your.org/pub/misc/apple/ftp.apple.com/developer/Development_Kits/CFM-68K_4.0_SDK.sit.hqx)
- [Drag Manager 1.1](http://ftpmirror.your.org/pub/misc/apple/ftp.apple.com/developer/Development_Kits/Macintosh_Drag_-_Drop.sit.hqx)
- [Thread Manager](http://ftpmirror.your.org/pub/misc/apple/ftp.apple.com/developer/Development_Kits/Thread_Manager.sit.hqx)
- [Open Transport 1.1](http://ftpmirror.your.org/pub/misc/apple/ftp.apple.com/developer/Development_Kits/OpenTransport/OT1.1/OpenTransportInstaller.sea.hqx)
- [Open Transport 1.1.2](http://ftpmirror.your.org/pub/misc/apple/ftp.apple.com/developer/Development_Kits/OpenTransport/OT1.1.2/OpenTransportInstall.sea.hqx)

If you want the Mac OS 8 look, you can install the Appearance Manager, and for a hierarchical Apple menu, just copy over the Apple Menu Options control panel from a 7.5.x/7.6.x installation. WindowShade can be installed in a similar fashion.


- [Appearance Manager](http://ftpmirror.your.org/pub/misc/apple/ftp.apple.com/developer/Development_Kits/Appearance_SDK_1.0.4.sit.hqx)
