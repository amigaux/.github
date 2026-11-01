amigaux brings Commodore's Amiga UNIX to newer Amiga hardware: new kernels, loadable kernel modules,
drivers, firmware, install media and a package manager. Downloads and install guides are on
[amigaux.org](https://amigaux.org); everything we know about Amiga UNIX is in the
[grimoire](https://jusii.github.io/grimoire-amix/).

### Reporting a problem or asking a question

Everything goes to [amigaux/amix](https://github.com/amigaux/amix). If you are not sure which part
is at fault, report it there anyway; we pass it on.

- **A bug or an install problem:** [open an issue](https://github.com/amigaux/amix/issues/new/choose).
- **A question or an idea:** start a [discussion](https://github.com/amigaux/amix/discussions).
- **A machine or card we don't cover yet:** [open a hardware support request](https://github.com/amigaux/amix/issues/new?template=hardware_support.md).
  Check the [supported hardware](https://amigaux.org/hardware/) first.

A good bug report names the machine (or emulator and version), the accelerator and its firmware
version, the disk controller, the file you installed from, what you did, what you expected and what
happened, and a capture of the console or serial output.

### Where things live

| Repository | What belongs there |
|---|---|
| [amigaux/amix](https://github.com/amigaux/amix) | The system: the module system, drivers, the package manager, the packages, the build |
| [amigaux/amix-040-060-port](https://github.com/amigaux/amix-040-060-port) | The kernel on the 68040 and 68060 |
| [amigaux/amix-gayle-ide](https://github.com/amigaux/amix-gayle-ide) | The A4000 Gayle IDE driver |
| [amigaux/amix-cdfs](https://github.com/amigaux/amix-cdfs) | The CD filesystem |
| [amigaux/amix-paula](https://github.com/amigaux/amix-paula) | Paula audio |
| [amigaux/amix-z3660rtg](https://github.com/amigaux/amix-z3660rtg) | The Z3660 graphics driver |
| [amigaux/gcc14-cross-amix](https://github.com/amigaux/gcc14-cross-amix) | The GCC 14 cross compiler for programs |
| [jusii/amix-installng](https://github.com/jusii/amix-installng) | Install media and the installer |
| [jusii/Z3660-amix](https://github.com/jusii/Z3660-amix) | The Z3660 firmware with Amiga UNIX support |
| [jusii/grimoire-amix](https://github.com/jusii/grimoire-amix) | The documentation |

You don't need to know this to report something: amix is always the right place.

---

This project and its developers are not affiliated with, endorsed by, or sponsored by Amiga
Corporation. Amiga is a registered trademark of Amiga Corporation.
