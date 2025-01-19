---
title: Graphics hw
Author: Morten Harding
date: 2025-01-06
category: Jekyll
layout: post
---

### Can the Apple 8*24GC acceleration be enabled under Mac OS 7.6 and later?

Yes. Though Apple doesn't support it. The ATI Graphics Accelerator extension will allow the 8*24GC to work fully under Mac OS 7.6 and later if the Mac has been upgraded with a PowerPC accelerator. The ATI extension is written in PPC-native code and does nothing on pure 68K Macs.


### How can I fix my Compact Mac's video problem?

There are several known problems with the video in the 128/512/Plus and in the SE or SE/30. If you get a checkerboard pattern or a thin vertical or horizontal line but everything else seems OK, try removing the ROM and RAM chips, cleaning the contacts on them with a vinegar and salt solution (or a lemon juice and salt solution), and reseating the chips. Make sure you also check to see if the ROMs are inserted the correct way. (Backwards ROMs can cause this too.) If that doesn't work, try re-soldering the analog board connections at C1, J1, and L2. For a good soldering iron to use, see Question 2.8.8 in the Miscellaneous section. While it doesn't have full instructions for all repairs, S. Hamada's site for repairing the SE/30 has useful information for the SE and SE/30 analogue board repairs.


### What monitors will work with my IIci/IIsi?

The IIsi and IIci, which have the same video subsystem, cannot drive a standard VGA monitor. However, any monitor supporting a 67Hz refresh rate, sync-on-green, and the proper horizontal and vertical refresh rates will work. This includes many Sony monitors and the Apple Portrait Display. Apple's multisync monitors such as the Multiple Scan 15 do NOT support sync-on-green, and will not work properly with the built-in video. The Apple Two-Page Display is also incompatible with built-in video on these two Macs.

Some Mac-to-VGA monitor adapters can properly separate the sync signals of monitors that do not sync on green, thus enabling otherwise incompatible monitors to be used with the IIci or IIsi (at a price, usually around US$50).


### I have a dead CRT in my Mac. What other Macs can I steal a CRT from to fix it?

The 128, 512, Plus, SE and SE/30 share a common CRT.

The Classic and Classic II (and their Performa variants) share a common CRT. The CRT itself is the same as that used in the Plus, but the yoke assembly is different, so swapping a CRT from a Classic to a Plus/SE/etc. or vice versa is much more difficult and complex than swapping from a Classic to a Classic II. Also, swapping yokes will usually necessitate adjustment of the analogue board to get the image properly centered and sized.

The Color Classic, Color Classic II, and their Performa variants share a common CRT.

The LC/Performa 520, 550, and 57x models all share a common CRT.

The LC/Performa 58x models share a common CRT.


### Why is there a big black border around my monitor's image?

That's there for a reason. Earlier (read: before the mid-1990s) CRTs had problems with maintaining a sharp focus all the way to the edge of the monitor and distortion due to the curve of the CRT face. Leaving a black border around the image helps reduce these problems by eliminating the area of the CRT where they occur. However, a lot of people don't like that border (or the slight problems don't bother them). The surest way to remove it is to get inside the monitor and adjust the image height and width pots, but this is 1) dangerous for the inexperienced, 2) often difficult, and 3) may result in damage to your computer or monitor over time. (The black-and-white Compact Macs are particularly susceptible to damage if improperly adjusted.) With that in mind, there are a couple of software utilities that may, in some cases, help you out. MonitorExpander 1.01 and MaxAppleZoom 1.44 work with certain Apple-branded NuBus video cards to trick the cards into displaying a higher resolution than "normal" and/or by allowing a scrolling virtual portrait mode. They do NOT support any Macintosh's built-in video.
