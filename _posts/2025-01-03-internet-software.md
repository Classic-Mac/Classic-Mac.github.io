---
title: Internet Software
Author: MORTEN HARDING
date: 2025-01-03
category: Jekyll
layout: post
---


### How can I get my old Mac online?

Funny you should ask. JAG has a tutorial which tells exactly how to do it.


### How do I get an old Mac set up for e-mail?

It's not too difficult but it does require some knowledge. The following procedure was written assuming that 
1. you already have another Macintosh that has access to the WWW and 
2. you have at least a Mac Plus.

In order to get any Mac online for at least e-mail access, you'll need at least System 6.0.5, 2MB of RAM, two 800K floppy drives or a hard disk and an 800K floppy drive, and some sort of modem, preferably 14.4 or faster.

Now that you have the necessary connection software installed, you need an e-mail client. Eudora 1.3.1 is probably the best e-mail client for System 6 Macs. Directions for configuring Eudora are available at SIU. If you're running System 7 or higher, you can use Eudora 1.5.5.

- [Download Eudora 1.3.1](ftp://ftp.qualcomm.com/eudora/eudoralight/mac/english/1.3system6/eudora131.hqx)
- [Eudora config](http://www.infotech.siu.edu/maconline/Eudora131.html)
- [Download Eudora 1.5.5](http://www.rtis.com/nat/user/toolbox/oldmacs/Eudora_155.sit.hqx)

Marshall Lewis also pointed out that by getting the Felix's Emailer disk image, you can get a Mac with a HD floppy drive on-line as long as it has at least 2MB RAM.


### How do I get an old Mac set up for WWW access?

You can pretty much follow the directions above for getting a Mac set up for e-mail; however, I highly recommend that any Mac to be used for browsing be running at least System 7 and have 8MB or more of RAM. While somewhat more difficult, you can certainly browse the Web with a browser like MacWeb 1.00A3.2 on a 68000-based Mac such as a Plus, SE, or Classic. Don't expect to be able to do much; MacWeb likes to freeze early and often.

iCab is far and away the best browsing option for most people on 68K Macs now, except for the 68000-based Macs, which can't use it. Any other 68K Mac running at least System 7 can and should use iCab, which is light on RAM usage, very fast, and supremely configurable. Two tips: load up on RAM to the extent possible and put the browser's cache on a RAM disk for best speed, and turn off multiple connections in the Preferences for maximum stability.

Netscape 2.0.2 is probably the next-best choice for most browsing needs on a 68030 or lower. You'll also probably want the Netscape Defrost extension, which helps Netscape freeze less often, as well as the Netscape 2.02 Update. 

A lot of older browsers, including Netscape 2.x and 3.x, have a problem with expired security certificates; you won't be able to use them to connect to secure sites any more.

### What browsers can I use on my Mac, and what are their features?

There's a 68K browser profile page with specs on most 68K-compatible browsers, including information on support for plug-ins, JavaScript, Java, secure browsing, minimum Mac OS requirements, RAM and HD requirements, and CPU requirements. It also has download links for the browsers profiled.

- [iCab](http://www.icab.de/)


## Browsers for Low-End Macs

This is, as always, a work in progress but is reasonably comprehensive as far as I currently know. I've included browser versions that I and others deem most significant and most useful; this generally means there are significant advantages too sticking with the version listed and not upgrading to the next version in certain situations. If, for some reason, you need a version of a browser that is not listed here or if any of these links are broken, I recommend you check out Gamba's "Where to Download Browsers" page. Alternate download links for most IE versions can be found here, and some alternate links for older Netscape versions are here.

⊞ table ⊞

Browser Version Support for: Minimum CPU Minimum
Mac OS RAM/HD
(MB) Notes:
Plug-Ins JavaScript Java Encryption
Netscape 2.02 Y Y N 40-bit (1) 68020 7.0• 4/2.5 10, Taming NN2
3.04 Y Y Y 128-bit (1) 68020 7.0• 9/5 10
4.08 Y Y Y 128-bit 68020 7.1 (2) 8/8
Internet
Explorer 2.1 Y Y N 40-bit (1) 68030 7.1 4/2.5
3.01 Y Y Y (7) 40-bit (1) 68030 7.1 4/8
4.01 Y Y Y 128-bit (1, 8) 68030 7.1 4/22 10
MacWeb 1.00A3.2 N N N none 68000 7.0• 2/1
1.1.1E N N N none 68000 7.0• 2/1.5
2.0 N N N none 68000 7.0• 2/1.2
MacLynx 2.7b1 N N N none 68030 7.0• 2/2
CyberDog 2.0 Y (3) N Y (4) 40-bit 68030 7.1 8/14 5
iCab 2.8.2 Y Y Y 128-bit 68020 7.0• (6) 5/5
MacWWW 1.0.3 N N N none 68000 6.0.8 1.5/0.5 9

(1): Browser security certificates have expired; these browsers are now useless for secure browsing. (See also Note 10.)

http://home.earthlink.net/%7Egamba2/browsers.html  Gamba's "Where to Download Browsers" page
http://helpdesk.uvic.ca/how-to/support/mac/msiexpl.html  helpdesk.uvic.ca/how-to/support/mac/msiexpl.html
http://www.cnss.swt.edu/download/mac.htm  www.cnss.swt.edu/download/mac.htm
ftp://archive.netscape.com/archive/navigator/2.02/mac/Netscape2.02Installer.hqx Netscape2.02Installer.hqx
http://home.earthlink.net/%7Egamba2/tamingNN.html  Taming NN2
ftp://archive.netscape.com/pub/navigator/3.04/shipping/english/mac/68k/navigator_complete/netscape3.04_US.bin netscape3.04_US.bin 3.04
ftp://archive.netscape.com/pub/communicator/4.08/english/mac/68k/navigator_standalone/Nav4.08_US_68K.bin Nav4.08_US_68K.bin  4.08
ftp://ftp.usm.edu/pub/mac/internet/ie/68k/ie21_68k.hqx ie21_68k.hqx 2.1
ftp://ftp.videon.ca/pub/mac/Ie301m68.hqx Ie301m68.hqx  3.01
ftp://ftp.innet.net/pub/.0/msdownload/ie401/rtw/mac/en/IE401F68.BIN IE401F68.BIN 4.01
ftp://ftp.pacifier.com/pub/mac/tcpip/macweb-10a32-fat.hqx macweb-10a32-fat.hqx 1.00A3.2
ftp://ftp.uconn.edu/pub/mac/internet(info-mac)/web/mac-web-111e.hqx mac-web-111e.hqx 1.1.1E
ftp://ftp.lri.fr/pub/sri.ucl.ac.be/WWW/MacWeb/MacWeb2.sit.hqx MacWeb2.sit.hqx 2.0
http://www.lirmm.fr/%7Egutkneco/maclynx/maclynx_en.html  MacLynx
http://www.cyberdog.org  CyberDog
http://www.cyberdog.org/dogbones/#apple cyberdog.org/dogbones/#apple
http://www.icab.de/  iCab
ftp://ftp.netgate.net/pub/mac/net/www/other/MacWWW1.03.hqx  MacWWW1.03.hqx

(2): Ignore installation warnings but make sure you have the CFM-68K Runtime Enabler 4.0, ObjectSupportLib 1.2 (included with CFM-68K download), Drag Manager 1.1 (included in 7.5.x and up), and Thread Manager (included in 7.5.x and up) extensions installed.

(3): Requires Internet Plugin Viewer.

(4): Requires Apple's Macintosh Runtime for Java 2.0.

(5): Requires OpenDoc.

http://ftpmirror.your.org/pub/misc/apple/ftp.apple.com/developer/Development_Kits/CFM-68K_4.0_SDK.sit.hqx  CFM-68K Runtime Enabler 4.0
http://ftpmirror.your.org/pub/misc/apple/ftp.apple.com/developer/Development_Kits/Macintosh_Drag_-_Drop.sit.hqx  Drag Manager 1.1
http://ftpmirror.your.org/pub/misc/apple/ftp.apple.com/developer/Development_Kits/Thread_Manager.sit.hqx  Thread Manager
http://www.cyberdog.org/dogbones/#apple  Internet Plugin Viewer
http://www.cyberdog.org/dogbones/#apple  OpenDoc.

(6): Requires Drag Manager 1.1 and Thread Manager extensions for pre-System 7.5 installations. See iCab site for more details.

(7): Requires separate installer for Java

(8): Requires separate installer for 128-bit encryption.

(9): Will not access FTP sites or .shtml pages. Only usable for .htm(l) and .txt viewing.

http://ftpmirror.your.org/pub/misc/apple/ftp.apple.com/developer/Development_Kits/Macintosh_Drag_-_Drop.sit.hqx  Drag Manager 1.1
http://ftpmirror.your.org/pub/misc/apple/ftp.apple.com/developer/Development_Kits/Thread_Manager.sit.hqx  Thread Manager
ftp://ftp.crihan.fr/pub/mactools/Ie301jva.hqx  separate installer for Java
ftp://ftp.fu-berlin.de/unix/security/replay-mirror/mirror/ftp.microsoft.com/MS-IExplorer-v40/Mac-MSIE-401-128-Bit-Installer.hqx  separate installer for 128-bit encryption.

(10): If you are comfortable doing some modifications, the following directions from a now-dead page on Thawte.com explain how to update the security certificates for Y2K compliance:

> 
> ---------------------------------------------------
> People running 3.x generation browsers can upgrade their security to the
> same level as that supported by 4.0 generation browsers. The process takes
> about 2 minutes and ensures that your browser works with the tens of
> thousands of Thawte certified secure servers out there, well into the next
> century. You only need to do this once for your browser to be updated
> permanently. If you have already done so, then you can ignore this page!
> 
> 
> Netscape Navigator 3.x
> With Netscape Navigator 3.x you must first delete the old root and then
> install the new one. To do so, follow these quick steps:
> 1. Choose Options, Security Preferences.
> 2. Select the "Certificate Authorities" tab.
> 3. Find the entry marked "Thawte Server CA". Delete that certificate.
> 4. Close that dialog box.
> 5. Now point your browser at http://www.thawte.com/serverbasic.crt and
> accept the new root certificate. You will be asked for a nickname, use
> "Thawte Server CA". This certificate is identical to the last one, except
> that it is valid till 2020 and is the same as the certificate in
> Communicator 4.x.
> 
> 
> Microsoft Internet Explorer 3.x
> Even though the versions of IE 3.x that ship with the Thawte root (should
> be IE 3.01 and IE 3.02) use the old root, they are _not_ affected by the
> expiration in July, because that browser does not check root expiration
> dates, only cert expiration dates. If you see an error message when you
> try to connect to a Thawte secure site with IE 3.x, it can probably be
> fixed by following the steps below. This only works on IE 3.x on Windows95
> or NT 4.0.
> 1. Point your browser at http://www.thawte.com/serverbasic.crt
> 2. Choose "Open File" if you are asked, then "Accept and Enable", "OK". 3.
> Now restart IE. You should now have a "Thawte Server CA" entry that is
> valid till 2020.
> 
> If you have the old root and want to roll it over for completeness you can
> do that too by following these steps.
> 1. Choose View, Options, Security, Sites.
> 2. Look for the entry called "Thawte Server CA". It may or may not be
> there, depending on your precise browser version and upgrade history. If
> it is there, click on it, then click on "Delete". Else, continue at 3.
> 3. Click on OK.
> 4. Now point your browser at http://www.thawte.com/serverbasic.crt
> 5. Choose "Open File" if you are asked, then "Accept and Enable", "OK". 6.
> Now restart IE. You should now have a "Thawte Server CA" entry that is
> valid till 2020.
> 
> 
> Mac IE 4.x
> The version of IE 4.x for the Macintosh (no other platform) ships with
> both the old and the new roots. To get it to work, you need to delete the
> old root. In your security preferences, find the Thawte Server CA roots
> that expired in 1998 (there should be two of them). Delete them. If you
> are asked for a password, leave it blank. Do NOT delete the newer roots
> which expire in 2020. You will now be able to connect cleanly.
> ---------------------------------------------------

