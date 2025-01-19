---
title: Expansion cards
Author: Morten Harding
date: 2025-01-10
layout: post
---

### The difference between LC and LC III PDS slots?

The LC PDS slot is shorter than the LC III PDS slot. The LC III PDS has a few extra pins in it which make the LC III PDS slot a 32-bit slot (whereas the LC PDS is a 16-bit slot). Most LC PDS cards will work just fine in an LC III PDS, but the few cards which do take advantage of the extra bus width of the LC III PDS slot will NOT work in an LC or LC II. Similarly, a very few cards developed for the LC PDS will not work in the LC III PDS slot.


### Mac expansion or upgrade slots

The Mac 128, 512K and Ke, and Plus have no expansion capabilities. Dove Enhancements, which is now defunct, made upgrades for the original Macintosh and the 512K and Ke which added various features such as RAM Disks, SCSI, and more RAM for the system. Dove upgrades are highly valued as collector's items now, along with the original Macintosh.

The SE has an SE PDS slot which is unique to the SE. SE Ethernet cards, probably the most common use for this slot, will NOT work in any other Mac, and no other Mac's Ethernet card will work in the SE. The same goes for any other SE expansion card - if the card came from anything besides an SE it won't work in an SE.

The Classic has an expansion slot which was used only for Apple's RAM Expansion Board to give the Classic more than 1MB RAM. No other cards were ever made for this slot.

The SE/30 and IIsi share a PDS slot known as the 030 PDS. Ethernet cards and monitor cards for either machine are interchangeable, but keep in mind that the SE/30 has an FPU on-board, which necessitated the removal of the Motorola 68882 FPU (if present) on the expansion card. IIsi Ethernet cards were probably the most common cards to have the FPU on them, so if you get an Ethernet card for an SE/30 that was in a IIsi, check it for an FPU first and remove it if present. The IIsi also had an option from Apple called the IIsi FPU/Nubus Adapter, which gave the IIsi a single Nubus slot and an FPU. With this adapter installed, any Nubus card can be used in the IIsi, though with a half-height hard drive, full-length Nubus cards will often not fit well. Accelerators generally require an adapter (usually included with the accelerator when bought new) to be used in the IIsi or SE/30.

The Classic II has a ROM/FPU Expansion Slot for which a few FPU cards were made, utilising 16MHz Motorola 68882 FPUs. The slot cannot be used for anything but an FPU card and is physically (but not electrically) similar to the Classic's RAM Expansion Board slot. The FPU boards can occasionally be found on eBay but are generally pretty rare.

The II series machines with the exception of the IIsi have 3 or 6 Nubus expansion slots which take any sort of Nubus card. The IIci has a PDS slot which supports a IIci PDS card. Many accelerators, most notably the Daystar PowerCache, Turbo040, and Turbo 601 cards, were designed for this PDS slot and require an adapter to be used in any other Macintosh. The IIci PDS slot was also used for the Apple 32K cache card that shipped in many later IIcis and was an option on the earlier models. The II and IIx have no PDS slot and are limited to the expansion capabilities of the six Nubus slots or a Daystar accelerator with the appropriate adapter. The IIfx has a PDS slot, but its PDS is unable to communicate directly with any Nubus slots, precluding the use of the PDS in the IIfx for accelerators. The IIcx has no PDS but can use a Daystar accelerator in much the same way as the II and IIx with the appropriate adapter. The IIvi and IIvx have three Nubus slots and a PDS slot which does NOT require an adapter to work with IIci-type accelerators.

Any 68K Mac with "LC" in the model name has either an LC (original LC and LC II) or LC III (LC III and later) PDS slot. See above for the differences.


### Daystar upgrades for Mac

http://www.mactcp.org.nz/ mactcp.org.nz several of his own drivers

The PowerCache was an '030-based upgrade containing 32K onboard L2 cache and with an optional (usually included) FPU at the same speed as the CPU, with speeds ranging from 25 to 50MHz. They were designed for the cache slot in the IIci and work in the IIci, IIvx, IIvi, and Performa 600 without an adaptor. Mac II, IIx, IIcx, IIsi, SE/30, and LC machines require adaptors to use the PowerCache line. Generally seen as a IIci, IIvx, SE/30, or IIsi upgrade though the occasional Mac II or LC-series machine has been upgraded too.

The Turbo 040 was an '040-based upgrade with speeds ranging from 25 to 40MHz. They can be used in the same models of Macintosh as the PowerCache line, with the adaptor requirements being the same as well. Most had an FPU but some LC040 (FPU-less) models were made.

The Value 040i was a 40 MHz '040-based upgrade for the 16-bit LC PDS Macs, which include the LC, LC II, Performa 400-430, and Color Classic. The Daystar brochure mentions nothing about compatibility with other Macs, but testing is pending.

The highly desirable Turbo 601 was a PowerPC 601-based upgrade for most of the same models as the PowerCache and Turbo 040, but the LC series, and Macintosh II and IIx can almost certainly not use the Turbo 601. I've seen one vague report of the Turbo 601 working in an SE/30, but third-party testing has been unable to replicate this success. Both 66 and 100MHz versions were made, all with 128K of L2 cache onboard. Most commonly seen as a IIci or IIvx/Performa 600 upgrade.

The PowerCard was a PowerPC 601-based upgrade for certain 68040 Macs that plugged directly into CPU socket. The original CPU then plugged into a socket on the PowerCard. PowerCards run at twice the original 040 speed.

The PowerPro was a PowerPC 601-based upgrade for 68040 Macs with a PDS connector. Adaptors are required for LC series (except the LC-style 040-based Macs, which can't accommodate a PowerPro) and "pizza box" Macs like the C/Q 610 and 660AV. Came in 66, 80, and 100MHz versions and most commonly seen in Q9x0 and "Wombat"-based machines (Q800, C/Q 650). The 66 and 80MHz versions generally have RAM expansion onboard and because of this, will not fit in the C/Q 610 or 660AV.

