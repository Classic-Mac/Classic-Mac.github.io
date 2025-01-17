---
title: Hard-disks
Author: Morten Harding
date: 2025-01-07
category: Jekyll
layout: post
---

### SCSI ID on internal HD

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


### The HD won't show up consistently?

Your drive probably isn't terminated properly. If you've enabled the termination jumper but it still isn't working, you probably are one of the unlucky few that has a drive with no termination resistors. The only thing you can do if you can't track down the resistors (which is, unfortunately, likely, though you can try here and hope they're the right ones for your drive) is to put an inline pass-through terminator on the drive. Unfortunately, I don't have a good source for these, so you'll have to ask the list.

It might also be worth having a look at KBase Article 9387, which is all about connecting SCSI devices to your Mac. It contains lots of helpful, basic information and some good troubleshooting advice.

### Termination resistors

Termination resistors are little yellow or black (usually) things about 5mm tall, 25-30mm wide, and about 2mm thick with eight or ten pins sticking out the bottom. They're used on SCSI hard disks to terminate the bus if the termination on the HD is enabled (usually with a jumper labelled 'TE'). They can usually be found in groups of two or three near the SCSI connector, on the controller board of the drive. If they're missing (you'll probably see a row of empty pin holes), you might have the problem described in 2.2.5 above.

