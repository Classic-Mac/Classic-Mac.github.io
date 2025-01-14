---
title: Hard-disks
Author: Morten Harding
date: 2025-01-07
category: Jekyll
layout: post
---

### What types of hard drives will work in my Mac?

Any half-height (or smaller), 50-pin SCSI hard disk will work in any 68K desktop Mac except for the 128 through Plus, which don't support internal HDs. The Plus can be hacked to support an internal hard disk, but I recommend against it because of heat and power supply issues.

The Mac II, IIx, and IIfx will support a full-height internal hard disk with a special bracket. Most Macs which support one internal HD will support two with the proper ribbon cable and power cable, but installing the second one can get really tricky, especially in the compacts. I don't recommend installing more than one HD internally in any compact because of power supply and heat issues.

Here's a brief table outlining the internal HD options for desktop Macs:

⊞ table ⊞

Model Maximum Size Notes
128K/512K/512Ke n/a no SCSI support
Plus n/a internal HD unsupported; can be hacked to support up to a 3.5" half-height drive
other Compacts 3.5" half-height rare brackets for SE and SE/30 allow for second 3.5" HH or smaller
II/IIx/IIfx 5.25" full-height or
up to 3 3.5" third-height requires special bracket(s) and new SCSI/power cable (for multiple drives)
IIcx/IIci/Q700 3.5" half-height
IIsi 3.5" half-height
IIvx form factor 5.25" half-height in CD-ROM bay; requires special bracket.
LC series 3.5" third-height
5xx series 3.5" half-height 58x Macs take IDE hard disks.
610/660 one 3.5" half-height and one 5.25" half-height in CD bay HD in CD bay requires special bracket and possibly new SCSI/power cables.
8xx up to three 3.5" half-height With CD-ROM drive, maximum number of HDs is two.
9x0 up to five 5.25" full-height Full-height drives may require special bracket.

### Why won't my Mac Plus see the external HD I use with my other Macs?

http://hyperarchive.lcs.mit.edu/HyperArchive/Archive/disk/apple-hd-sc-setup-735-patch.hqx  a patch for Apple HD SC Setup 7.3.5
http://www.euronet.nl/users/ernstoud/pub/lido756.hqx  here
ftp://ftp.media.mit.edu/pub/echalom/macstuff/MNU.sit.hqx  FTP here
http://www.macfaq.de/macfaqdaten/minifaqs/dspg.html  available here

The buffer on many older HDs is rather small, and the SCSI on the Mac Plus is quite slow. When these two factors are combined, it causes the HD to effectively be "too fast" for the Plus. To get around this, HDs for use with the Mac Plus were often formatted with a 3:1 interleave, which slowed down the data flying at the Plus enough so the Plus could handle it. If your external HD is an older unit and has only been used with Macs newer than the Plus, it probably has a 2:1 or 1:1 interleave and is too fast for the Plus. To remedy this, back up the HD and reformat it on the Plus (or on another Mac, as long as you can specify the interleave ratio). This will make the drive slow enough for the Plus (and probably won't impact its performance on other Macs too negatively). Most newer hard disks have enough cache so as to make interleave ratios irrelevant.


### How do I change the SCSI ID on my internal HD?

While the position of the jumpers varies from drive to drive, there is a basic pattern to the way jumpers are configured. (To find the specific location of the SCSI ID jumpers on your HD, check the manufacturer's web site.) The table below is the typical way hard disk manufacturers set the SCSI ID. Three jumpers, called J0, J1, and J2 here (though they likely aren't labeled on the HD) are used to set the SCSI ID. J0 represents a binary "ones" digit, or 2^0, which equals 1. J1 represents a binary "tens" digit, or 2^1, which is 2. J2 represents a binary "hundreds" digit, or 2^2, which is 4. The sum of the three jumpers is the resultant SCSI ID.

```
J0    J1    J2   SCSI ID
0 *                  
1 *            
2 *     *            
3 *      
4 *           *      
5 *     *      
6 *     *     *      
7 (reserved for motherboard) 
```

Some (though not many) manufacturers used a decimal jumper system, with the jumpers representing 1, 2, and 3 (instead of 1, 2, and 4). The jumpers sum to the SCSI ID just as they do above. The only advantage of this system is it makes it impossible to select SCSI ID 7, which is reserved for the Mac motherboard. However, the binary system makes more sense in the context of computers and is by far the dominant method of setting SCSI IDs.


### I've tried everything I know to get this HD to work but it just won't show up consistently. What's going on?

Your drive probably isn't terminated properly. If you've enabled the termination jumper but it still isn't working, you probably are one of the unlucky few that has a drive with no termination resistors. The only thing you can do if you can't track down the resistors (which is, unfortunately, likely, though you can try here and hope they're the right ones for your drive) is to put an inline pass-through terminator on the drive. Unfortunately, I don't have a good source for these, so you'll have to ask the list.

It might also be worth having a look at KBase Article 9387, which is all about connecting SCSI devices to your Mac. It contains lots of helpful, basic information and some good troubleshooting advice.


### What Macs can I use my serial-based Apple Hard Disk 20 with?

The Hard Disk 20, a hard disk that plugs into the floppy port on early Macintosh models, has built-in ROM support on the 512Ke, Plus, SE, Classic, IIci, and Portable. Other early Macs, such as the 512K, can use it if the HD20 INIT is installed on the boot disk. The Mac512 User Group has a page about the HD20, and Apple's TIL Archive article #4423 has a compatibility listing as well. Read Apple's TIL Archive article #6182 as well for important information about compatibility with later Macs.


### What the heck are termination resistors, anyway?

Termination resistors are little yellow or black (usually) things about 5mm tall, 25-30mm wide, and about 2mm thick with eight or ten pins sticking out the bottom. They're used on SCSI hard disks to terminate the bus if the termination on the HD is enabled (usually with a jumper labelled 'TE'). They can usually be found in groups of two or three near the SCSI connector, on the controller board of the drive. If they're missing (you'll probably see a row of empty pin holes), you might have the problem described in 2.2.5 above.


### Is there a limit to the size of the hard disk I can put in my Mac?

Yes, but it's probably not as low as you may have been told in most cases. This Mac Daniel article (awaiting other hosting) explains the situation.
