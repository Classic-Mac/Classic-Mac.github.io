---
title: Networking
Author: Morten Harding
date: 2025-01-04
category: Jekyll
layout: post
---

### How can I get files from my PC to my Mac?

Most Macs that can run System 7.1 or higher will also work with PC Exchange, which will allow PC-formatted disks to be read in both the floppy and external drives such as Zip drives. If you need a copy of PC Exchange and don't want to download all 40MB or so of the System 7.5.3 Unified Release, you can get a copy of PC Exchange 1.0.4 via FTP. (Use a real FTP client if your web browser doesn't work.) However, if you don't have this option, there are a few ways you can get your PC to write Mac-format disks. Probably the best site on this topic is located here. It lists different programs for reading and writing HFS (the native Macintosh format) disks on a PC. Of those, TransMac ($64 shareware) is probably the best. The PC program can be found here and will enable your PC to write HD Mac floppies. Note that PC floppy drives cannot write Mac-format 800K floppies due to physical differences in the read/write mechanisms, but with TransMac or a similar program, PCs can write 1.4MB Mac floppies.

When you download files that you'll want to transfer to your Mac, try, if possible, to download BinHex files. They're plain text and are less likely to get munged somehow during the transfer.

If you don't have any way of using floppies to transfer from one computer to another (i.e., you have only an 800K drive on the Mac), check out the excellent StarGate program for null modem transfers. It will take a tad bit more effort than floppies but it's a very nice program and works pretty well for transferring small amounts of data. (Large amounts of data don't send so fast over a 56Kbps link as you modem users may know.)


### How can I run a file server under System 6?

- [hfs](http://www.mars.org/home/rob/proj/hfs/)

The other option would be to track down AppleShare Server v2 or earlier, which will also run just fine on System 6 and runs much faster than System 7's built-in File Sharing.


### How can I connect a Mac running OS X to one running System 6?

Marten van de Kraats has posted the latest information from several sources on his System 6 Heaven.

- [System 6 heaven](https://machut.net/mirrors/system6heaven/)

### How can I share printers on my network?

Phil Beesley has written up a nice tutorial on how to use an OS X machine to share a printer on a network for the use of virtually any Mac. If you don't have an OS X box, one of your options is similar: you can use the instructions Phil outlines on almost any *nix distribution running on virtually any hardware. If you don't have an OS X or *nix box, you need a printer that can be shared by Mac OS-based means, which generally means any printer capable of using the LaserWriter 8 driver (basically all PostScript-capable laser printers) or an Apple StyleWriter of some sort, which can be shared using the Printer Sharing capabilities built into the OS. ImageWriters with a LocalTalk card can be shared; you'll need AppleShare Server or AppleShare Print Server to share an ImageWriter without a LocalTalk card. It isn't clear if non-Apple printers can be shared via these means or not using the Mac OS, though most will work with gimp-print on *nix systems as outlined in Phil's instructions.


### Can I net-boot my 68K Mac?

- [from the UMich archive](http://www.umich.edu/%7Earchive/mac/system.extensions/chooser/jcremote1.0a4.sit.hqx)

Yes, but only if you have an Ethernet card with one of two very rare third-party ROM upgrades. Both Sonic's The Diskless Mac and Mauswerks's BootToob used a ROM chip to replace the factory ROM chip in an installed Ethernet card. This new ROM would connect to the network at startup, load a boot image into RAM on the client Mac, disconnect from the network, and continue booting.

The original cost was $139-149 per client and required an AppleShare Server running MacTCP (or a UNIX server in the case of Sonic's tdM) on the network. When more ROM part number/ID information is available, it will be posted here; if you have any, e-mail me.


## Networking/Printing
### How can I network my Macs?

Funny you should ask. Low End Mac had a Mac Daniel column (awaiting other hosting) about this exact topic back in February of 2000. After you read that column, check out Three Macs and a Printer and The Mac 512 site's AppleTalk-ing page.


### What are the various types of Ethernet?

If I had a dollar for every time this came up in some form or another on the Vintage or Compact Macs lists, I wouldn't be sitting here writing this FAQ :) I'd be in Hawaii vacationing or something. Here's an overview.

There are four main types of Ethernet common in the Mac world. BaseT is based on a telephone-jack-like connector called an RJ-45 connector. The cabling is either Category 3 or Category 5. There are three subtypes of BaseT - 10BaseT, which operates at 10Mbps and can use either Cat 3 or Cat 5 (and is by far the most common type in the vintage Mac world); 100BaseTX, also known as Fast Ethernet, which operates at 100Mbps and requires Cat 5; and 1000BaseTZ, which is also known as Gigabit Ethernet and is unavailable in Nubus form (and thus isn't really applicable here). All forms of BaseT Ethernet networks require hubs of some sort. Hub-based networks such as these are known as star networks. For what it's worth, Farallon made a few 10/100BaseT Nubus cards but they're prohibitively expensive and can't fully utilise the bandwidth of 100BaseT Ethernet due to the slow bus speeds and OS limitations of older Macs.

http://www.atpm.com/network/index.html  Three Macs and a Printer
http://www.mac512.com/appletal.htm  AppleTalk-ing

Base2 is a coaxial cable-based network. The cables look like really thin cable TV cables, which give rise to the common name "Thinnet." Base2 Ethernet operates only at 10Mbps and does not require hubs. Macs with 10Base2 Ethernet cards can be daisy-chained together with T-connectors and terminators on each end of the network. 10Base2 networks are limited to 30 devices and 189 metres of cable, whereas BaseT can be used with any number of devices and, with repeaters, can be used with virtually no limits on cable length.

AUI is an acronym for Attachment Unit Interface and is commonly confused with a monitor port, as the ports are both DB-15 female ports. If you see a DB-15F port next to a coaxial or RJ-45 plug, however, DO NOT plug a monitor into it. If you plug a monitor into the port, you will probably fry the Ethernet card to the point of actually burning the connectors! Native AUI cabling is very rare (read: nonexistent). It is most commonly used with a transceiver of some sort, usually either to 10Base2 or 10BaseT. AUI operates only at 10Mbps.

AAUI is the fourth and final common type of Ethernet found on Macs. It stands for Apple AUI, a proprietary version of AUI that Apple developed to be somewhat smaller and more compact than AUI. The connector is only found on the motherboard of some later Centris and Quadra machines and early Power Macs and on a few Apple Ethernet cards and has a 14-pin connector a little less than an inch wide. It requires a transceiver to either 10BaseT or 10Base2 and operates only at 10Mbps.

There is one other type of Ethernet which was never used directly on an Ethernet card. 10Base5 is like a very thick version of 10Base2 (thus the nickname "Thicknet"). It requires an AUI transceiver, uses a large, thick coaxial cable and enormous connectors and operates only at 10Mbps.


### Is there any way I can use an HP LaserJet II or similar printer with my Mac?

Yes. You need Chuck's Printer Driver and an ImageWriter I cable (or similar cable, but NOT a Mac modem cable, which will not work). Make sure the baud rate, stop bits, parity, and such are set in both Chuck's Printer Driver and on the printer itself. This setup should work with virtually any Macintosh with a standard serial port. It will also likely work with some other similar printers, provided that both the printer and driver are set up properly.


### How can I find the MAC address of my Ethernet card?

If you have a computer that supports Apple System Profiler, that can tell you. If not, download the Apple LAN Utility from Apple's FTP site and use that. It will get your MAC address whether or not you are on a network and whether or not a transceiver (if necessary) is connected to your card or Mac.


### Is there a limit to LocalTalk network length?

Yes. LocalTalk networks constructed with Apple-proprietary cables can only be up to 1000 feet (about 305 metres) in length. With repeaters, this can be extended to the length allowed by the repeater (which varies). If you use PhoneNet in a trunk configuration with 22 AWG wire, you can make a LocalTalk network up to 4000 feet (1220 metres), and with standard modular phone cord, you can make one up to 2000 feet (610 metres). Again, this can be extended if necessary with repeater devices.


### Can I use LocalTalk Bridge to get my LocalTalk Macs on the Internet?

Yes and no. First of all, LocalTalk Bridge will not route TCP/IP in any way, shape, or form. You need to get a product like IPNetRouter or Vicomsoft Internet Gateway to do that, or a hardware MacIP router like a Cayman GatorBox or Farallon StarRouter. However, if you have several Macs that aren't Ethernet-capable (or don't have an Ethernet card) and you want to put them on the Internet (and you don't have a hardware MacIP router), you will need LocalTalk Bridge. Set up your Ethernet network first, get your router or router software up and running, and then hook your LocalTalk devices up - through LocalTalk Bridge, running on an Ethernet-capable Mac - to the router.

Now for a very brief explanation of this. LocalTalk Bridge will only route AppleTalk packets, not TCP/IP or anything else. Your router software (and some hardware routers) encapsulates the TCP/IP packets inside AppleTalk packets, which allows LocalTalk Bridge to properly pass the TCP/IP traffic to and from the Internet. The LocalTalked Macs take these AppleTalk packets (using MacIP as their connection method) and "unwrap" the data.


### What printers would be good for my 68K Mac?

I firmly recommend any of the Apple-branded LaserWriters for any purpose but colour printing. Even printers as old as the LaserWriter and LaserWriter Plus are still quite viable printers, if a tad slow these days. If you absolutely need colour printing, you might want to check out an older HP DeskJet or a used Colour StyleWriter. For further information, Low End Mac's Chris Lawson also has a Mac Daniel article (awaiting other hosting) on choosing a good printer.