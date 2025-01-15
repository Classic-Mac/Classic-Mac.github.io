---
title: Startup keys
Author: Morten Harding
date: 2025-01-02
category: Jekyll
layout: post
---

Macintosh Startup Key Combinations

A Mac does several checks when it is first powered on. One of the first things it does is scan the keyboard bus (ADB) for any signals. Certain keys will cause various actions to be taken. Note: command (cmd) is the same as the Apple key, option (opt) is the same as the alt key.

### When the computer is first powered up:

| Key combinations        | Describtion                                                               |
|-------------------------|---------------------------------------------------------------------------|
| cmd-opt-P-R             | Zap PRAM. Causes computer to reboot.                                      |
| cmd-opt-X-O             | Boot from ROM (Mac Classic only). Boots from copy of System 6.0.3 in ROM. |
| cmd-opt-A-V             | Reset AV monitor and force it to be recognised as such.                   |
| cmd-opt-T-V             | Force 660AV or 840AV to use TV connected to the AV jacks as the monitor.  |
| cmd-opt-shift-delete-(#)| Boot from SCSI ID #                                                       |
| R                       | Force PowerBook to reset screen.                                          |
| C                       | Boot from Apple-brand CD-ROM drive.                                       |
| hold mouse button       | Eject bootable floppy and boot from the SCSI bus.                         |
|-------------------------|---------------------------------------------------------------------------|

### Before the happy Mac first appears:

| Key combinations | Describtion                                                                      |
|------------------|----------------------------------------------------------------------------------|
| Command          | Boot with virtual memory off (System 7 - Mac OS 9.x only).                       |
| shift            | Boot with Extensions, Control Panels, and Startup Items disabled and VM.         |
| space            | Open Extensions Manager (System 7.5.x and higher only) on boot.                  |
| others           | Check documentation for third-party extensions and control panels.               |
|------------------|----------------------------------------------------------------------------------|

### Immediately after the "icon parade" finishes:

| Key combinations | Describtion                                                                      |
|------------------|----------------------------------------------------------------------------------|
| cmd-opt          | Rebuild desktop database file.                                                   |
| shift            | Disable Startup Items only.                                                      |
| option           | Start Finder with no open windows.                                               |
|------------------|----------------------------------------------------------------------------------|

For shortcuts to use in the Finder once the Mac is booted, check out the Finder Shortcuts file in the Help menu.

### Other useful shortcuts/undocumented:

| Key combinations | Describtion                                                                      |
|--------------------------------------------|--------------------------------------------------------|
| cmd-opt while opening Memory control panel | Turn off RAM tests (Mac OS 8.5 - 9.x only).            |
| cmd-power key                              | Generate non-maskable interrupt, which will drop you   |
|                                            | into the built-in debugger or Macsbug (if installed).  |
|                                            | Type 'g' and press return to continue.                 |
| cmd-opt while opening Chooser              | rebuild Chooser's cache.                               |
|--------------------------------------------|--------------------------------------------------------|

