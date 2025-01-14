---
title: Graphics hw
Author: Morten Harding
date: 2025-01-06
category: Jekyll
layout: post
---

### What video cards work with what monitors?

There aren't many resources that explicitly state video card and monitor compatibility, but Gamba's video card-monitor matrix (mostly Apple-branded information) is a good place to start. Griffin Technology has a large database of monitors and video cards as well, and MonitorWorld has one too. The Apple KArchive has lots of Apple-specific information; see Gamba's page or question 2.1.11 for more information.


### Where can I get drivers for my video card?

The Mac Driver Museum has drivers for a lot of Mac video cards and other hardware. Gamba has some links to Radius, SuperMac, and E-Machines drivers at his site too.


### Can the Apple 8*24GC acceleration be enabled under Mac OS 7.6 and later?

Surprisingly enough, yes. Though Apple doesn't support it, Leon Sargent discovered that the ATI Graphics Accelerator extension will allow the 8*24GC to work fully under Mac OS 7.6 and later if the Mac has been upgraded with a PowerPC accelerator. The ATI extension is written in PPC-native code and does nothing on pure 68K Macs.


### How can I fix my Compact Mac's video problem?

http://ftpmirror.your.org/pub/misc/apple/Apple_Software_Updates/English-North_American/Macintosh/Misc/Graphics_Accelerator_1.0.7.sea.bin  ATI Graphics Accelerator extension

There are several known problems with the video in the 128/512/Plus and in the SE or SE/30. If you get a checkerboard pattern or a thin vertical or horizontal line but everything else seems OK, try removing the ROM and RAM chips, cleaning the contacts on them with a vinegar and salt solution (or a lemon juice and salt solution), and reseating the chips. Make sure you also check to see if the ROMs are inserted the correct way. (Backwards ROMs can cause this too.) If that doesn't work, try re-soldering the analog board connections at C1, J1, and L2. For a good soldering iron to use, see Question 2.8.8 in the Miscellaneous section. While it doesn't have full instructions for all repairs, S. Hamada's site for repairing the SE/30 has useful information for the SE and SE/30 analogue board repairs.

Hardy Menagh has compiled an up-to-date list of replacement analogue board parts for the Plus and earlier, based on Larry Pina's parts list in Mac Repair and Upgrade Secrets, and I have transcribed it into HTML format for easy consumption. If you have a Plus or earlier with analogue board problems, and you know what needs to be replaced, check the parts list for a source.


### What is the proper CRT discharge procedure for Compact Macs?

First, MAKE ABSOLUTELY SURE YOU ARE NOT GROUNDED. Neither Nathan Pralle, the pickle, Low End Mac, nor any other entity or individual other than the individual working on the CRT takes responsibility for any harm you may cause yourself by working with a potentially dangerous cathode ray tube.

To discharge the CRT, use either Apple's CRT discharge tool or make your own. To make your own, take an alligator clip with a 12" (30cm) lead and firmly attach it with some sort of conductive material to the shaft of an insulated screwdriver. Clip the alligator clip to the Mac's chassis, making sure the Mac is plugged in. Slowly slide the tip of the screwdriver underneath the red suction cup on the CRT until you hear a "pop," which indicates that the CRT is discharged.

Again, you, the individual, take full responsibility for any damage done to yourself or your possessions, but just as a small side note, I have worked on many compacts and have never discharged a CRT and have suffered no ill effects. Avoid the red suction cup and you'll probably be just fine.

The later-revision SE and all later Macs have self-discharging flyback transformers, so in most cases, discharging the flyback manually will accomplish nothing. The particularly anal-retentive individuals among the readers should still do it, though.


### What monitors will work with my IIci/IIsi?

The IIsi and IIci, which have the same video subsystem, cannot drive a standard VGA monitor. However, any monitor supporting a 67Hz refresh rate, sync-on-green, and the proper horizontal and vertical refresh rates will work. This includes many Sony monitors and the Apple Portrait Display. Apple's multisync monitors such as the Multiple Scan 15 do NOT support sync-on-green, and will not work properly with the built-in video. The Apple Two-Page Display is also incompatible with built-in video on these two Macs.

Some Mac-to-VGA monitor adapters can properly separate the sync signals of monitors that do not sync on green, thus enabling otherwise incompatible monitors to be used with the IIci or IIsi (at a price, usually around US$50).

### I have a dead CRT in my Mac. What other Macs can I steal a CRT from to fix it?

The 128, 512, Plus, SE and SE/30 share a common CRT.

The Classic and Classic II (and their Performa variants) share a common CRT. The CRT itself is the same as that used in the Plus, but the yoke assembly is different, so swapping a CRT from a Classic to a Plus/SE/etc. or vice versa is much more difficult and complex than swapping from a Classic to a Classic II. Also, swapping yokes will usually necessitate adjustment of the analogue board to get the image properly centered and sized.

The Color Classic, Color Classic II, and their Performa variants share a common CRT.

The LC/Performa 520, 550, and 57x models all share a common CRT.

The LC/Performa 58x models share a common CRT.

### Where can I get monitor port pinout information?

Hardware Tech Note #8 has pinouts for the early Apple video cards, the Macintosh LC, and the IIsi/IIci. The pinout for the standard Mac DB-15 video port is available in TIL Article 9089. (It says Quadra and Centris, but it applies to the LC series as well.)

### Why is there a big black border around my monitor's image?

That's there for a reason. Earlier (read: before the mid-1990s) CRTs had problems with maintaining a sharp focus all the way to the edge of the monitor and distortion due to the curve of the CRT face. Leaving a black border around the image helps reduce these problems by eliminating the area of the CRT where they occur. However, a lot of people don't like that border (or the slight problems don't bother them). The surest way to remove it is to get inside the monitor and adjust the image height and width pots, but this is 1) dangerous for the inexperienced, 2) often difficult, and 3) may result in damage to your computer or monitor over time. (The black-and-white Compact Macs are particularly susceptible to damage if improperly adjusted.) With that in mind, there are a couple of software utilities that may, in some cases, help you out. MonitorExpander 1.01 and MaxAppleZoom 1.44 work with certain Apple-branded NuBus video cards to trick the cards into displaying a higher resolution than "normal" and/or by allowing a scrolling virtual portrait mode. They do NOT support any Macintosh's built-in video.

### Where can I get CRT/video adjustment tools?

Radio Shack part numbers 64-2220 and 64-2223 should be enough to adjust nearly any CRT ever made, but unfortunately, both have been discontinued. Check your local Ratty Shark for stock; the catalog doesn't list these any more but individual stores often have one or two sets.

An alternative to the Ratty Shark set is this set, which costs US$13.97 and, according to Dan, is "pretty well made." A bit pricier, but probably worth it if you can't find tools elsewhere.

### What monitors will my Mac physically support?

http://www.umich.edu/%7Earchive/mac/system.extensions/cdev/monitorexpander1.01.sit.hqx  MonitorExpander 1.01
http://www.umich.edu/%7Earchive/mac/system.extensions/cdev/maxapplezoom1.44.sit.hqx  MaxAppleZoom 1.44

The ever-lovely Dana provided me with a link to KArchive article number 8300, which lists the maximum weight ratings of various desktop Mac cases.
