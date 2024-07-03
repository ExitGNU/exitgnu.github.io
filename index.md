# ExitGNU

This website was made to share alternatives to the GNU ecosystem and spread the word about Richard Stallman, the biggest monster in the free software community.

# Motivation

My personal motivation for doing this alternatives website is to spread the cause that [Richard Stallman is a **monster** who maliciously ignores human common sense, and his fanatics are pretending they didn't see that.](https://rms-open-letter.github.io/appendix), I (fluffeon) as a sexual abuse survivor and mental health activist, these statements are objectively inhuman and repulsive.

This isn't a biased statement, **this is a moral truth.** Rape can ruin someone's life and is the most vile form of endangerment to a person because it can traumatise someone for many years or even for life. Unfortunately, I passed through this and my life just became a lot more miserable and I got into very bad habits myself. Richard Stallman dessecrated and minimized this issue, and let's not forget that he called to abort fetuses with Down's syndrome which is bordering into eugenics at this point.

I will not support any software that comes from the Free Software Foundation, until RMS and all of his board of directors are removed from their positions. So, I made this website.

There are also practical reasons why you should probably consider avoiding GNU software:

* The GNU codebase is extremely unoptimised, messy and bloated even for normal desktops, in most cases it sacrifices portability to POSIX and embedded systems. [These poor design choices eventually backfired, because now glibc-based distributions have been struck with a critical SSH exploit.](https://www.upwind.io/feed/regresshion-rce-in-opensshs-server-on-glibc-based-linux-systems-cve-2024-6387)

* It does a lot of things at once and manages to be the best at none of them. 

* [Tivoization. Also most of it is licensed with the very controversial GPLv3 (and by extent, the same nuances also apply to the LGPLv3 despite allowing linking with proprietary programs).](https://www.youtube.com/watch?v=PaKIZ7gJlRU)

* It makes people build bad habits of accostuming to the GNU extensions, like Perl-specific constructs and GCC enhancements. This not only perpetuates the GNU ecosystem but it also sacrifices portability with everything else. A clear example of this is the GNU Compiler Collection and Bash, which extends way beyond POSIX.

Of course, you may have your own motivations for avoiding GNU software and you are very much welcomed to share them as well. I'm pretty sure I'm not alone in this.

# Alternatives to the GNU ecosystem

## Core Utilities

* [**Busybox**](https://www.busybox.net/) - BusyBox combines tiny versions of many common UNIX utilities into a single small executable. It provides replacements for most of the utilities you usually find in GNU fileutils, shellutils, etc. The utilities in BusyBox generally have fewer options than their full-featured GNU cousins; however, the options that are included provide the expected functionality and behave very much like their GNU counterparts. BusyBox provides a fairly complete environment for any small or embedded system.

* [**uutils coreutils**](https://github.com/uutils/coreutils) - uutils coreutils is a cross-platform reimplementation of the GNU coreutils in Rust. While all programs have been implemented, some options might be missing or different behavior might be experienced.

* [**Toybox**](http://landley.net/toybox/) - Toybox combines many common Linux command line utilities together into a single BSD-licensed executable. It's simple, small, fast, and reasonably standards-compliant (POSIX-2008 and LSB 4.1).

* **BSD coreutils** - The BSD coreutils are the utilities developed and used by various operating systems based on the Berkeley Software Distribution. These are included by default on BSD distributions and some Linux distributions like Chimera Linux.

## Shells

* [**Z shell (zsh)**](https://www.zsh.org/) - Zsh is a shell designed for interactive use, although it is also a powerful scripting language.

* **Busybox shell (sh)** - Included in Busybox.

* [**Debian Almquist shell (dash)**](http://gondor.apana.org.au/~herbert/dash/) - Dash is a POSIX-compliant implementation of ´/bin/sh´ that aims to be as small as possible. It does this without sacrificing speed where possible.

## Make Utilities

* [**BSD Make (bmake)**](https://www.crufty.net/help/sjg/bmake.html) - A portable version of NetBSD's make.

## Compilers

* [**Tiny C Compiler**](https://bellard.org/tcc/) - Tiny C Compiler (TCC) is a minimal C compiler that can compile x86 and ARM code. This is my personal recommendation.

* [**LLVM**](https://llvm.org/) - The LLVM Project is a collection of modular and reusable compiler and toolchain technologies. It is well-known as the backbone of [**Clang**](https://clang.llvm.org/), a C compiler.

Some programs won't compile well with TCC and/or Clang due to incompatible flags, different compiler interpretations of the code or in the case of Clang, produce wonky results. In practice, GCC and these compilers aren't perfect and you can be flexible with this.

You can help by making more programs get along with TCC! It's faster, portable, smaller and linking is quicker than GCC and Clang.

## C Libraries

* [**musl**](http://musl.libc.org/) - musl is an implementation of the C standard library built on top of the Linux system call API, including interfaces defined in the base language standard, POSIX, and widely agreed-upon extensions.

## Operating Systems

Here are free as in freedom non-GNU operating systems that respect your privacy.

### Linux

* [**Alpine Linux**](https://alpinelinux.org/) - Alpine Linux is a security-oriented, lightweight Linux distribution based on musl libc and busybox. Out of all of the non-GNU distributions that exist so far, this one is probably the most popular.

* [**Chimera Linux**](https://chimera-linux.org/) - Chimera is a modern and general-purpose non-GNU Linux distribution born from unhappiness with the state of other distributions. It's built around the core idea that a simple system does not have to require endless setup and customization to be practical.

* [**BlissOS**](https://blissos.org) - BlissOS is an Android-based open source OS that incorporates many optimizations, features, and that supports many more devices.

* [**Linux from Scratch**](https://www.linuxfromscratch.org/) - Feeling like binary distros are not enough for you? Linux from Scratch is a project that provides you with step-by-step instructions for building your own custom Linux system, entirely from source code. You can build non-GNU installation for your purposes and needs.

### BSD

* [**FreeBSD**](https://www.freebsd.org/) - FreeBSD is an operating system used to power modern servers, desktops, and embedded platforms.

* [**MidnightBSD**](https://www.midnightbsd.org/) - MidnightBSD is a BSD-derived operating system developed with desktop users in mind. It includes all the software you'd expect for your daily tasks — email, web browsing, word processing, gaming, and much more. 

**If you have the means and motivation, please help by making more distributions that don't depend on the GNU ecosystem or by helping the distros above with more packages or other activities.**

## Text Editor

As far as I know, there isn't a non-GNU implementation of Emacs.

# Suggestions

This is a community project! I know I talked a lot about myself here, but I don't want to be the only one yapping here. It would be very much appreciated if you help expand this site. You can suggest more alternatives, and other stuff. [Just open an issue or pull request!](https://github.com/ExitGNU/exitgnu.github.io)

