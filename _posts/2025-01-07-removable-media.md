---
title: Removable media
Author: Morten Harding
date: 2025-01-07
layout: post
---

### Can I use a Zip drive with System 6 and/or as a boot disk?

The short answer is "Yes." The longer, more in-depth, useful answer is "Yes, provided that you get the right driver and don't use the disk with later versions of the driver on different Macs.

> 
> As far as booting off a Zip, you need driver 4.2. Be sure and use a Zip
> disk that has NOT been used under a newer Iomega Zip driver or it won't
> boot the [computer] but it will work as a hard drive. You'll have to
> reformat it under Zip Tools 4.2 or earlier if you want it to be your boot
> Zip disk.


### Can I use HD floppies in an 800K drive?

While it's physically possible to do it, those of us with a great deal of experience with Macs almost universally recommend against it. If you absolutely need an 800K disk and only have 1.4MB floppies available, you can force a 1.4MB disk to be an 800K disk by taping over both sides of the hole opposite the write-protect tab. THIS IS ONLY A TEMPORARY SOLUTION. THE DATA ON DISKS FORMATTED LIKE THIS WILL NOT USUALLY SURVIVE FOR LONG. UNDER NO CIRCUMSTANCES SHOULD YOU USE FLOPPIES FORMATTED LIKE THIS FOR STORING DATA LONGER THAN A FEW WEEKS. Don't say I didn't warn you...

Tom Lee of Stanford has graciously provided the following explanation:

> 
> To clear up the persistent confusion and superstition about 800K vs.
> 1.44MB media, here's the correct story: There is about a ten percent
> difference in the magnetization thresholds (called "coercivity") for the
> two media, with the 800K stuff having the lower value. If you want to get
> technical, 800K media have a nominal coercivity of 650 oersteds, versus
> 720 - 730 oersteds for 1.4MB media. So, 800K drives may find it difficult
> to write on 1.44MB media. However, ten percent is not a large difference,
> and in fact, is about the same as normal variations within a batch from a
> given manufacturing run. Plus, coercivity varies with temperature, too.
> So, the two media are not as wholly incompatible as lore has it.
> 
> However, if a 1.4MB disk has ever been written on by a 1.4MB drive (and
> this includes formatting), an 800K drive's weaker write fields may not be
> strong enough to reliably over-write the existing data, and you'll have
> flaky behavior (particularly if you're unlucky enough to have a drive with
> write currents at the low end of the spec, trying to write on a floppy
> with coercivity at the high end of spec). But if the floppy is virgin,
> you'll rarely see any problems at all. You can "re-virginize" floppies if
> you have a good demagnetizer handy.
> 
> Now, if you go the other way, by melting or punching (don't drill!) an
> extra hole to trick drives into thinking an 800K floppy is really 1.4MB,
> there's no problem with the drive's ability to flip magnetizations
> properly. However, the higher density is achieved by packing adjacent bits
> more tightly together on a given track (but the number of tracks per side
> is the same -- 80 -- for 400K/720K/800K/1.4MB media), and the lower
> density media may not have fine enough particles to do the job well (and
> the lower magnetic field strength of those particles further degrades
> margin). That's why many advise against doing this operation.
> 
> Since both media types are readily available (the 800K stuff is the same
> as 720K media from the PC world, but you'll have to reformat as Mac if
> they come preformatted, as they usually do nowadays), there's no real
> reason to do any of these things. But, every once in a while, you'll find
> these hacks useful in an emergency.


### Can I use HD floppies on my Mac II, SE, Plus, or earlier machine?

Some SEs support HD floppies out of the box, as indicated by "Superdrive" or "FDHD" (which stands for Floppy Drive, High Density) on the front of the case. (Note, however, that a very few SEs with the Superdrive or FDHD faceplate may have a motherboard inside them which does NOT support HD floppies because someone swapped out the original motherboard. I have seen one such SE and it was because I pulled the motherboard for use elsewhere.) The Mac II requires a ROM upgrade to support HD floppies. This ROM upgrade essentially makes it a IIx. The SE without HD floppy support can be upgraded with new ROMs and a new SWIM chip to support HD floppies.

The Plus can use (though not boot from) HD floppies via the Applied Engineering AE HD+ external floppy drive and the proper drivers, or with an Iomega "Floptical" SCSI drive. The Iomega drive cannot read or write 800K Mac-formatted disks, though it can read and write 720K DOS-formatted disks and 1.4MB floppies of either Mac or PC format, in addition to Iomega's special 21MB "Very High Density" diskettes. The Iomega drive is bootable if you use the 21MB floptical disks, but cannot boot from standard floppies. I know of no way to enable HD floppy support on a 128K, while the 512K and Ke may be able to use the AE HD+ drive as well.

Please note: simply plugging an external HD floppy drive into the floppy port on these Macs will NOT give you HD floppy support. The support depends on the ROMs and SWIM chip (and, obviously, the presence of a HD floppy drive). ROM/SWIM upgrades for an SE or Mac II can occasionally be found on eBay, but your best bet is to get an SE Superdrive/FDHD motherboard or a IIx motherboard and simply replace the old motherboard. (The SE can also be upgraded to an SE/30 motherboard, which will not only get you HD floppy support but also a 16MHz 68030 processor, FPU, and support for up to 128 MB RAM.)

If you need the ROM part numbers to check whether your SE has been upgraded or not, please visit the Mac SE Support Pages, where the full part numbers for both 800K and FDHD ROMs are listed.


### Can I use a non-Apple CD-ROM drive with my Mac?

Sure can. However, if you have a Mac (or System version) that won't work with the Apple 5.3.1 drivers, you'll probably have to use a third-party driver (such as Intech's SpeedTools or FWB CD-ROM Toolkit) with it. There's a page on MacMad (dead as of May '02) that has lots of helpful CD-ROM information that you might want to check out too. If you're using System 7.5 or higher, you can use the 5.3.1 driver, available from the JMUG Driver Museum, or you can use the ResExcellence hack on v5.4.2 of the driver (extractable from the Mac OS 8.1 Update). (The ResExcellence hack also works on higher versions.)

Most non-Apple CD-ROM drives are bootable, despite what Apple may claim. As long as they're SCSI drives, simply hold cmd-opt-shift-delete immediately after startup and as long as there's a bootable CD in the drive and there isn't another bootable drive on the SCSI bus (other than your normal boot drive), it will boot from the CD-ROM. The Apple-ROMed drives (generally Matsushita/Panasonic or Sony mechanisms) simply allow you to boot using the "C" key on startup. The C key trick does not, as is commonly thought, require a Mac that originally shipped with a CD-ROM drive; the Color Classic at least is known to work using the C key to boot from CDs with an Apple-branded drive.


### How do I figure the speed of an Apple CD-ROM from its model number?

The table below provides information most Apple SCSI CD-ROMs.

⊞ table ⊞

Model Speed Int/Ext Caddy/Tray
CD SC 1x external caddy
1200i 8x internal tray
CD 150 1x external caddy
300 2x external caddy
300i 2x internal caddy
300e 2x external tray
300i Plus 2x internal tray
600i 4x internal tray
600e 4x external tray


### How can I tell if a floppy drive is 800k or 1.44MB?

There are two ways. The first, and easiest, is to look at the bottom of the drive. It will say 2MB on the bottom of the drive if it's a HD floppy drive. The second, which is easier if you can't open the computer up, is to look for the three microswitches in the front of the drive. There are two on the right and one on the left in a HD drive and there is one on each side in an 800K drive.


### Will this external floppy work on my Mac?

If it's a 5.25" drive, DO NOT PLUG IT INTO YOUR Mac. You'll fry the Mac's floppy controller and probably the drive as well.
