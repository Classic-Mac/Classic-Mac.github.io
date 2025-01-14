---
title: Other logic board
Author: Morten Harding
date: 2025-01-09
category: Jekyll
layout: post
---

### How do I overclock my Mac?

Not all Macs can be overclocked, but most Macs after the IIx can be. Marc Schrier's web site is the definitive Mac clock-chipping resource on the WWW.


### My Mac says the date is 1904 (or 1956) and keeps resetting itself to that date when I turn it off. I keep losing other settings, too, such as AppleTalk network settings. What's wrong?

You have a dead PRAM battery. See next question (below) for instructions on how to replace it.

There were three different types of PRAM batteries used in Macs. The Plus (and earlier Compacts) used a 4.5V alkaline battery that is very similar in appearance to a AA battery. The Eveready part number for this battery is 523. Equivalents are ANSI 1306AP, IEC 3LR50, NEDA 1306AP, Panasonic PX21, and Varta V21PX. (Thanks, Sp00ky.)

http://homepage.mac.com/schrier/mhz.html  Marc Schrier's web site

In the UK, you can get these at Battery.co.uk for 6 UKP. Radio Shack has them in the US for $8 plus shipping (or a special order at a store). If anyone has a better US source for these, I'd love to know. Note that this battery is now discontinued and is becoming increasingly difficult to find. Marten van de Kraats has reported success with a Varta 4102 4.5V battery about the size of a cigarette pack, which obviously requires slight modification to work but should last nearly indefinitely. Two other possible sources (for the Eveready 523), which should be available worldwide, are Dial-A-Battery (US$5.14 for the battery, excluding shipping) and Exell Battery.

The 57x, 58x, 63x, and later Macs based on their motherboards used a 4.5V square battery, Rayovac part number 840 or 841. Other World Computing stocks these for US$9 each. Pidrus has them for $10.99, and Mac-Battery has them for $9.44. In Canada, CanadaRAM stocks them for C$20. You can also remove the connector from your old battery and solder it to a 3-AA battery holder so you have a homemade 4.5V battery that costs about US$1.50 to replace.

Most other Macs used a 3.6V, 1/2AA lithium battery, which is readily available at many vendors. You can get these batteries at Radio Shack (in the US) for about $10. Mac Batteries has them on-line for about $6.50 each (quantity pricing applies). MCM Electronics have the elusive solder-type Mac II and early SE batteries for just $6.25 each. If you need several, get them online - it'll be significantly cheaper. (If the links at MCM are broken, go to MCM's web site and enter "3.6V" in the Search field.) All Electronics has the batteries with a 1995 date code for $1.50 each or $1 each in quantity. They have a 10-year shelf life, so this shouldn't be a problem in most cases.

If you buy your battery somewhere other than the above vendors, the 3.6V 1/2AA specification should be sufficient to get the proper part. Note that if you're buying Maxell batteries, part number ER3S is what you want, NOT the ER3, which is about five millimetres too long. (Thanks for the correction, John V.)

http://www.battery.co.uk/  Battery.co.uk
http://www.radioshack.com/product.asp?cookie%5Ftest=1&catalog%5Fname=CTLG&category%5Fname=CTLG%5F004%5F000%5F000%5F000&product%5Fid=960%2D0357  Radio Shack
(thepickle@binhost.com  I'd love to know
http://www.dialabattery.com/  Dial-A-Battery
http://www.exellbattery.com/detail.asp?PID=A21PX  Exell Battery
http://eshop.macsales.com/Item_Specials.cfm?ID=2525&Item=MAC45V  Other World Computing
http://www.pidrus.com/batteries.html  Pidrus
http://mac-batteries.com/  Mac-Battery
http://www.ordersite.com/canadaram/batteries.html  stocks them
http://www.macbatteries.com/  Mac Batteries
http://www.mcmelectronics.com/Home/level_5.jhtml?PRODID=17379&SKUID=16624  the elusive solder-type Mac II and early SE batteries
http://www.mcmelectronics.com  MCM's web site
http://www.allelectronics.com/cgi-bin/category.cgi?category=160&item=LBAT-12AA&type=store  
All Electronics

Some people have had marginal success with using 3V CR2 lithium batteries designed for cameras, but Apple doesn't recommend this for one simple reason: they tried it and it wasn't sufficient. The early SEs and Mac IIs had 3V batteries in them and Apple received many complaints that the PRAM was resetting itself spontaneously after a year or two of use. They traced the problem to the 3V batteries and from that point on, used 3.6V batteries instead. If you want to use a 3V battery, go for it, but don't say I didn't warn you.


### How do I replace the PRAM battery in my Mac?

The Mac Battery Web Page has all the information you'll ever need on replacing PRAM batteries. A quick tip from Martin: apply a thin layer of Vaseline or similar petroleum jelly to the contacts when you replace the battery. It'll help prevent corrosion and marginally improves conductivity by lowering the resistance.


### What other logic boards will fit my Mac as an upgrade?

Mac logic boards come in a number of basic designs, or form factors. Form factors are named after the first computer that comes in that form factor. Logic boards of the same form factor will physically fit in each other's cases. An * indicates minor modifications may be needed to fit this board into a prior case or vice versa.

Logic board form factor "128" is common to the 128K, 512K, 512Ke, and Plus*.

http://www.academ.com/info/macintosh/  Mac Battery Web Page

Logic board form factor "SE" is common to the SE, SE FDHD, and SE/30.

Logic board form factor "II" is common to the II, IIx, and IIfx.

Logic board form factor "IIcx" is common to the IIcx, IIci*, Quadra 700*, IIvx*/P600*, IIvi*, Centris/Quadra 650*, and Power Macintosh 71xx*.

Logic board form factor "Classic" is common to the Classic and Classic II*/Performa 200*.

Logic board form factor "LC" is common to the LC, LCII/P40x/410/430, LCIII/P450, LCIII+/P46x, and Q 605/LC475/P47x. Note: if moving an LC II or higher motherboard into an LC, the LC's fan and speaker will have to be replaced with those from the motherboard donor machine. The LC uses a unique fan and speaker housing that is physically incompatible with the later motherboards.

Logic board form factor "IIsi" is unique to the IIsi.

Logic board form factor "Q900" is common to the Quadra 9xx series and Apple Workgroup Server 9150.

Logic board form factor "Color Classic" is common to the Color Classic/P250, LC5xx/P5xx (with exception noted below for 58x machines), Macintosh TV, and Color Classic II/P275.

Logic board form factor "C610" is common to the Centris 610 and 660AV, Quadra 610 and 660AV, and Power Macintosh 61xx*.

Logic board form factor "Q800" is common to the Quadra 8xx* and Power Macintosh 8xxx prior to the 8600. Worth noting: the Q800 motherboard is nearly identical to the Q650 motherboard with the only difference being a couple of resistors on the board.

Logic board form factor "Q630" is common to any Macintosh 63x or 640 machine, LC 58x/P58x, Power Macintosh 5xxx/P5xxx, and all Power Mac/Performa 6xxx-series (with exception noted above for 61xx machines).


### Can I use another Mac's power supply to replace/upgrade the one in mine?

The power supplies for Macs generally follow the logic board form factors given above; i.e., computers which share a logic board design generally share a power supply as well. There are a few exceptions, most notably in the 8xx(x) series machines.


### Why doesn't my Mac have any video output when I hook up a monitor?

The Quadra 605 and its LC and Performa variants (LC/Performa 47x) will fail to output a video signal when the PRAM battery dies (or if no PRAM battery is present, or if it's inserted the wrong way). A workaround is to turn it on with the power switch in the back, quickly turn it off, and turn it back on. While it isn't known for sure why this works, speculation is that a capacitor on the video circuitry is charged by the PRAM battery and flipping the switch allows the capacitor to charge without discharging as it normally would on startup. See above for where to get a new battery.

The Centris 610 and its later variants (C/Q 660AV, Q610, Power Mac/Performa 61xx) will also fail to output a video signal when the PRAM battery dies (or if no PRAM battery is present, or if it's inserted the wrong way). There is no known workaround for this problem; you'll have to replace the battery. See above for where to get a new one.

Any other Mac that fails to output video likely has some sort of hardware problem. Try a known-good monitor or video card and if that doesn't solve it, bring the problem to the lists.


### What the heck is that single slot that looks like a SIMM slot on my Mac's logic board?

The ROM SIMM slot is found on many early Macs. It was used for a ROM update that superceded the ROMs on the logic board. If your Mac works fine without it, leave the slot alone unless you want a dead Mac. If your Mac won't boot with the slot empty, you probably need a ROM SIMM (see note below). They are specific for each model of Mac and can occasionally be found on eBay. (These also make neat keychains if you have a spare one.)

Below is a table of ROM SIMM information for all Macs known to have a ROM SIMM slot:

⊞ table ⊞

Model ROM SIMM slot? Notes
II No has solder pads for one
IIx Yes required; no onboard ROM
IIcx/ci Yes some later IIcx have only solder pads
IIsi Yes very rare
IIfx Yes required; no onboard ROM
IIvx/vi/P600 No has solder pads for one
SE/30 Yes required; no onboard ROM
LC47x/Q605 Yes none known to exist
Q/C660AV Yes some have only solder pads
Q700 Yes none known to exist
Q9x0 Yes none known to exist
Q800 Yes none known to exist
Power Macintosh x100 Yes --

It has been speculated that the early-production IIcx and IIsi models may have had an error in their onboard ROMs and the ROM SIMM is required to correct this error. On later models, it was removed because the error was fixed, and this is the reason for the rarity of the ROM SIMMs on these two models.

For Mac II-series machines with ROM SIMM slots, check to make sure the W1 jumper is removed (if a ROM SIMM is installed) or installed (if the ROM SIMM slot is empty). If the jumper is incorrectly configured, the Mac will look for a ROM where there may not be one and will not boot. If the ROM SIMM slot is empty and the W1 jumper installed and the Mac still won't boot, make sure the onboard ROM chips are where they should be. If they are, try re-seating them.


### What does that strange error code under the Sad Mac mean?

There are several combinations of letters and numbers - way too many to list here. However, Larry Pina's Dead Mac Scrolls deals with some of them (mostly SE and earlier) and Apple has a reference, in MS Word format, that deals with many of them as well.


### Is there a good reference for my other 680x0 processor questions?

http://ftpmirror.your.org/pub/misc/apple/ftp.apple.com/developer/Tool_Chest/Testing_-_Debugging/Hardware_tools/Sad_Mac_Error_Codes_1.1.sit.hqx  a reference, in MS Word format

There is a Motorola 68K FAQ available from UAlberta. The two most common questions seen on the list are answered in the next question below.


### What sort of processor upgrades can I do to my Mac without an upgrade card?

You can get a 68010 for your 68000-based Mac; the '010 is pin-compatible with the 68000 and should drop right in. You CANNOT put a 68060 into a 68040-based Macintosh; the '060 is not entirely compatible with the Mac ROMs or the '040 instruction set and would require a major rewrite of a good deal of software in order to work properly. The '020 and '030 are NOT pin-compatible.

The 68882 FPU is pin-compatible with the 68881 and should be used instead where possible. Socketed 68882s are most often found on dead SE/30 and IIfx motherboards and on Daystar Digital PowerCache cards. The 68LC040, which shipped in most Performa and LC Macs with an '040 CPU, can be replaced with a full '040 without the LC designation, thus adding an FPU to the previously FPU-less Mac. A good source of these is a dead Quadra or Centris motherboard.

For more information about 68K pinouts, see the pinouts page of this FAQ (requires Internet connection; contains images).


### Where can I find pinouts for the various ports on my Mac?

ftp://bode.ee.ualberta.ca/pub/motorola/general/m68kfaq  Motorola 68K FAQ available from UAlberta
http://macfaq.org/hardware/pinouts.shtml  pinouts page of this FAQ

Apple has a Service Source PDF called "Ports and Pinouts" but most of us don't have access to Service Manuals. So check out this Hardware Tech Note, number 19. It has pinout information for most Mac ports. If that doesn't answer your question, maybe this German site will.

For more information about 68K pinouts, see the pinouts page of this FAQ (requires Internet connection; contains images).


### Why does my Mac keep restarting when I shut down?

The Mac IIcx/ci, IIvx/vi, Performa 600, Quadra 700, Centris/Quadra 650, and Power Mac 7100 had a rather nice feature designed for ease of use as servers: the power button can be locked in the in position so that when the power is interrupted, the Mac will restart automatically. To disable this feature (rather annoying if you don't want the computer running 24/7), simply take a flathead screwdriver and turn the power button in the back about a quarter-turn in either direction. The button will pop out and the Mac will no longer restart whenever it's shut down.

If you don't have one of the Macs with this power supply, then you likely have some sort of power supply problem and probably should replace your power supply. If that doesn't fix it, a logic board problem is likely.


### What's that J18 jumper on my LC475/Q605 motherboard?

http://developer.apple.com/technotes/hw/hw_19.html  Hardware Tech Note, number 19.
http://www.ccr-computerclub.de/lam2/inhalt.htm  this German site
http://macfaq.org/hardware/pinouts.shtml  pinouts page of this FAQ

With the jumper in place, your Mac will register a gestalt ID corresponding with the Q605. Without the jumper, it will register one corresponding with the LC475.


### What's that little red button on my Mac's motherboard?

That's the CUDA reset switch, which resets the PRAM if pressed. Don't press it unless you're prepared to deal with the consequences of an ordinary PRAM zap.

