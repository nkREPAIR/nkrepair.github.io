---
title: "GNU/Linux"
---

**[Home](./index.md) $\bull$ [FOSS Library](../categories/foss_l.md) $\bull$ [GNU/Linux](./categories/gnu_linux.md) $\bull$ [Windows](./categories/windows.md) $\bull$ [Electronics](./categories/electronics.md) $\bull$ [IT Tech](./categories/it_tech.md)**

## GNU/Linux

### For you GNU-comers

| HowTo                             | Hardware          | Software |
| :-------------------------------- | :---------------- | :------- |
| Installing Linux                  | Steam Deck        | FOSS_L   |
| Windows to Linux Transition Guide | Framework Devices |          |
| MacOS to Linux Transition Guide   |                   |          |
| Debloat Ubuntu Derivatives        |                   |          |
| PiHole Unbound                    |                   |          |
| Disable Snap and use Flatpak      |                   |          |
| Virtualization Guide              |                   |          |



### What is GNU/Linux and where does it get its name?

GNU/Linux is a family of open-source Unix-like operating systems based on the Linux kernel and the GNU system software.

Richard Stallman, the founder the GNU Project and the Free Software Foundation sought to create an free alternative to Unix but was missing the kernel, the foundational software of which an operating system runs. Linux was Linus Torvalds’s working name for his own operating system that combined his proprietary kernel with the GNU system. Mr. Torvalds later “liberated” his kernel. Combining the Linux Kernel and the GNU system resulted in a system the was GNU/Linux or GNU/Linux. The *GNU/Linux* or the *GNU+Linux* name was shortened to Linux overtime, depriving the GNU project of their credit.

 **TL;DR: Give [credit](https://www.youtube.com/watch?v=UK52v6bCPvg) where credit is due!**



> I'd just like to interject for a moment. What you’re referring to as Linux, is in fact, *GNU/Linux*, or as I’ve recently taken to calling it, *GNU plus Linux (GNU+Linux*). Linux is not an operating system unto itself, but rather another free component of a fully functioning GNU system made useful by the GNU corelibs, shell utilities and vital system components comprising a full OS as defined by POSIX.
>
> ​	– In [Memery](https://copypasta.fandom.com/wiki/An_interjection) of Richard Stallman, *Linux and the GNU System*

> Many computer users run a modified version of the GNU system every day, without realizing it. Through a peculiar turn of events, the version of GNU which is widely used today is often called “Linux”, and many of its users are not aware that it is basically the GNU system, developed by the GNU Project. There really is a Linux, and these people are using it, but it is just a part of the system they use.
>
> There really is a Linux, and these people are using it, but it is just a part of the system they use. Linux is the kernel: the program in the system that allocates the machine’s resources to the other programs that you run. The kernel is an essential part of an operating system, but useless by itself; it can only function in the context of a complete operating system. Linux is normally used in combination with the GNU operating system: the whole system is basically GNU with Linux added, or GNU/Linux. All the so-called “Linux” distributions are really distributions of GNU/Linux.
>
> ​	– Richard Stallman, [Linux and the GNU System](https://www.gnu.org/gnu/linux-and-gnu.en.html)



### Outdated Arguements (For and Against using GNU/Linux)

- Free as in free beer!
	- Windows (Home and Pro) without a license (sorta) locks GUI customization and leaves a watermark
	- Otherwise, Windows is fully functional
- Terminal scary
	- Linux GUI apps have come a long way and for the home user, there are plenty of GUI applications
	- Even if you need the terminal, someone somewhere on the Internet has had your problem before and should provide the relevant commands or instructions you need.



### Why one should use GNU/Linux

- **No built in adware!**
  - Not only is GNU/Linux free of charge, it does so without adware built into the OS.
    - Like stated previously, Windows is also technically free to use with the only benefits of paying for the license being customizing the GUI and removing the watermark.
      - HOWEVER, paying for a license does not prevent adware from being installed.
        - Windows Pro N is a special version to comply with EU regulations. 
- **Software Management**
	- Instead of scouring the web for software and running potentially malicious installer, Linux distributions use package managers to manage software installations from software repositories and app stores. 
		- GNU/Linux did app stores before before app stores were mainstream
- **Virtual Desktops!**
  - While Windows and MacOS also have virtual desktops, GNU/Linux did it first (Windows in 2014, MacOS in 2007, and Linux in 1990) and does it better.
  - The advantage of GNU/Linux’s virtual desktop is that it is more polished and integrated into the desktop environments compared to Windows and MacOS. See our guide [here](./virtual_desktops.md)!
  	- Yet another feature GNU/Linux did before the mainstream.
- **Efficient**
	- GNU/Linux is highly modular, allowing it to run on anything from supercomputers to the inexpensive IoT devices. This modularity allows GNU/Linux to breathe new life into otherwise aging hardware.
- **Stable**
  - Windows Update breaking your stuff?
  	- GNU/Linux will politely tell you there are software update available but won’t download or install without your consent.
- **Open Source**
  - Many eyes on the source code means it is less likely for anything malicious to slip through
  	- See this [article](https://www.theverge.com/2021/4/30/22410164/linux-kernel-university-of-minnesota-banned-open-source) about how the University of Minnesota got banned from submitting patches to the Linux kernel because someone decided to play around.
  - If a maintainer abandons a projects, or changes its [purpose](https://blog.centos.org/2020/12/future-is-centos-stream/), the project can be forked and maintained as it once was.

### Why one should not use Linux

- ##### Hardware Compatibility
	
	- While many devices are designed with PnP drivers, some hardware require special drivers before use
		- Before switching, research will need to be done in order to determine if your hardware has compatible drivers.
		- If a driver does not exist, whether it be the manufacturer not providing GNU/Linux drivers or the community not having reverse-engineered drivers , then GNU/Linux will not work for you.  
	
- **Software Compatibility**

	- Many professional proprietary software (MS Office Suite, Adobe Creative Suite, etc) does not exist on GNU/Linux because the userbase is tiny (~2% on desktop at the time of writing). 
		- While open alternatives exist, these may not be sufficient substitutions.
	- Games with unsupported launchers, DRM, and/or highly invasive anti-cheat software (Riot's Vanguard, Activision’s RICOCHET, etc) do not work on GNU/Linux.
		- While dual booting, virtualizing Windows, and WINE are workarounds, they can bring their own set of issues. 

