# RAY-OS
RAY OS v1.0
An operating system written by a 12-year-old in pure x86 assembly
https://img.shields.io/badge/100%2525-ASM-red
https://img.shields.io/badge/Size-32KB-blue
https://img.shields.io/badge/Linux_Killer-300%252B_MB-green
https://img.shields.io/badge/Age-12-yellow

What Is This?
This isn't just an OS. This is a statement.
While other 12-year-olds play Fortnite, I write operating systems in assembly.
While Linux weighs 300+ MB, my system fits in 32 KB.

Features
Full bootloader (512 bytes, bootsector)

Graphical interface (Mode 13h, 320x200, 256 colors)

Multitasking (Mac OS 7-style windowing)

File system (FAT16 file reading)

Network stack (NE2000/RTL8139/Intel Pro100 drivers)

USB driver (keyboard support)

Hardware monitoring (CPU temperature, fan speeds)

Real-time clock (with blinking colon!)

Drag & drop interface

Web browser (HTTP client, page loading)

Tech Stack
text
Language:    Pure x86 Assembly (FASM style)
CPUs:        Pentium 4 (478) - Core 2 Duo (775)
Memory:      640KB enough (real mode operation)
Video:       VGA Mode 13h
Storage:     FAT16 on USB/HDD
Network:     Ethernet (3 card types supported)
How to Run
On real hardware (recommended):
bash
# 1. Write to USB
dd if=rayos.img of=/dev/sdX bs=512

# 2. Insert into Pentium 4
# 3. Witness history
In emulator (for the weak):
bash
qemu-system-i386 -hda rayos.img -vga std -m 64M
Screenshots
how i can get a screenshot from my os?
text
[COMING SOON]
(Actual photos from a real P4 monitor)
Other Projects (Relevant Because Context)
Built MOS 6502 motherboard (CPU from 1975!)

Constructed satellite with rocket engine (H₂ + O₂ = 🚀)

Assembled 7 PCs since age 10 (Pentium to Ryzen)

Proficient in welding and soldering (microchips to metal structures)

Bill Gates wrote back (yes, that one)

"But Why?"
Because I can

Because 12 is a good age for ambitious goals

Because assembly is poetry

Because why the hell not?

Coded to:

The Caretaker (5 full listens of Stage 6, I'm fine)

Daft Punk (for robotic coding sessions)

Author
I'm 12 years old.
Yes, seriously.
No, I'm not lying.

Try running it on actual Pentium 4 hardware

Don't ask for systemd support (it's a feature, not a bug)

P.S. Oh.... just wait this is a experemtal version and mouse, this green lines is a small bug im so sorry.
