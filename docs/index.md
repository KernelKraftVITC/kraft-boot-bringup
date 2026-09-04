---
author: Sanidhya Sharma
updated: 2026-09-04
---

# M1: Boot & Bring-up

Take the machine from power-on to a running 64-bit kernel that can print to the screen and serial port, and react to a keypress. This is the foundation every other module depends on.

## Core objectives

- Toolchain and repository / build setup
- Boot via Limine into 64-bit long mode
- Framebuffer and serial output
- GDT and TSS
- IDT and exception handling
- PIC / APIC and timer interrupt
- Keyboard driver

## Architecture

Pending implementation details.

## References

- [OSDev Wiki — Bare Bones](https://wiki.osdev.org/Bare_Bones)
- [OSDev Wiki — Limine Bare Bones](https://wiki.osdev.org/Limine_Bare_Bones)
- [OSDev Wiki — GDT](https://wiki.osdev.org/GDT)
- [OSDev Wiki — IDT](https://wiki.osdev.org/IDT)
- [OSDev Wiki — APIC](https://wiki.osdev.org/APIC)
- [Linux kernel source — arch/x86/kernel/head_64.S](https://github.com/torvalds/linux/blob/master/arch/x86/kernel/head_64.S)
- [Linux kernel source — arch/x86/kernel/idt.c](https://github.com/torvalds/linux/blob/master/arch/x86/kernel/idt.c)
- [Linux From Scratch — cross-toolchain chapters](https://www.linuxfromscratch.org/lfs/view/stable/)

The LFS link is for its cross-toolchain chapters specifically — directly relevant to the "toolchain and build setup" submodule, even though the rest of LFS builds userland, not a kernel.
