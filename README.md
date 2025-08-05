# 🐧 lsusb Command for macOS

[![Codacy Badge](https://app.codacy.com/project/badge/Grade/f56c0620f67f464983aa51019d558027)](https://app.codacy.com/gh/LanikSJ/lsusb/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade)
![GitHub Repo Size](https://img.shields.io/github/repo-size/laniksj/lsusb)
![GitHub Code Size in Bytes](https://img.shields.io/github/languages/code-size/laniksj/lsusb)
![GitHub Last Commit](https://img.shields.io/github/last-commit/laniksj/lsusb)
![GitHub Commit Activity](https://img.shields.io/github/commit-activity/m/laniksj/lsusb)

## 📑 Table of Contents

- [📝 Description](#-description)
- [💾 Installation](#-installation)
  - [📥 Manual](#-manual)
  - [🍻 Homebrew](#-homebrew)
- [🧑‍💻 Usage](#-usage)
- [🙋 Help](#-help)
- [🐛 Bugs](#-bugs)
- [📄 License](#-license)
- [💰 Donate](#-donate)

## 📝 Description

This is an utility to easily list USB devices in Mac OS X, just like the
`lsusb` command in Linux. It leverages the data from the
`system_profiler SPUSBDataType` built-in command available in Mac. You can
type `lsusb -v` to get the unmodified output of
`system_profiler SPUSBDataType`.

## 💾 Installation

### 📥 Manual

To install, clone the repository and copy to a location available in your
PATH, for example `sudo cp lsusb /usr/sbin`.

### 🍻 Homebrew

You can also install it with [Homebrew](http://brew.sh)🍻 using my
[Tap](https://github.com/LanikSJ/homebrew-tap):

```bash
brew update && brew install laniksj/tap/lsusb-plus
```

or from official [Homebrew](http://brew.sh)🍻
[Tap](https://github.com/Homebrew/homebrew-core):

```bash
brew update && brew install lsusb-laniksj
```

## 🧑‍💻 Usage

Here's an output example:

```bash
Bus 036 Device 003: ID 04e8:6860 Samsung Electronics Co., Ltd. SAMSUNG_Android  Serial: 323062d3f6738057
Bus 036 Device 002: ID 05ac:8507 Apple Inc. Built-in iSight  Serial: 8J97P2KF16V13A00
Bus 038 Device 003: ID 1a40:0101 TERMINUS TECHNOLOGY INC. USB 2.0 Hub [MTT]
Bus 038 Device 004: ID 0403:6001 Future Technology Devices International Limited FT232R USB UART  Serial: A601EFG9
Bus 038 Device 005: ID 12d1:1038 Huawei Technologies Co., Ltd. Android Adapter  Serial: 509F2735096D
Bus 038 Device 002: ID 05ac:8403 Apple Inc. Internal Memory Card Reader  Serial: 000000009833
Bus 004 Device 003: ID 05ac:8242 Apple Inc. IR Receiver
Bus 004 Device 002: ID 05ac:0236 Apple Inc. Apple Internal Keyboard / Trackpad
Bus 006 Device 002: ID 0a5c:4500 Broadcom Corp. BRCM2046 Hub
Bus 006 Device 003: ID 05ac:8213 Apple Inc. Bluetooth USB Host Controller  Serial: 002608CCAC6F
Bus 036 Device 001: ID 05ac:8006 Apple Inc. EHCI Root Hub Simulation
Bus 038 Device 001: ID 05ac:8006 Apple Inc. EHCI Root Hub Simulation
Bus 004 Device 001: ID 05ac:8005 Apple Inc. OHCI Root Hub Simulation
Bus 006 Device 001: ID 05ac:8005 Apple Inc. OHCI Root Hub Simulation
```

## 🙋 Help

```bash
List USB devices
  -v  Increase verbosity (show output of "system_profiler SPUSBDataType")
  -s  [[bus]:][devnum]
       Show only devices with specified device and/or
       bus numbers (in decimal)
  -d  [vendor]:[product]
       Show only devices with the specified vendor and
       product ID numbers (in hexadecimal)
  -p  Display manufacturer names in parentheses
  -t  Dump the physical USB device hierarchy as a tree
  -V  Show version of program
  -h  Show usage and help
```

For a more accurate usage description type `man lsusb` or
`man man/lsusb.8` if inside the script's directory.

## 🐛 Bugs

Please report any bugs or issues you find. Thanks!

## 📄 License

[![MIT License](https://img.shields.io/badge/license-MIT-blue)](https://en.wikipedia.org/wiki/MIT_License)

## 💰 Donate

[![Patreon](https://img.shields.io/badge/patreon-donate-blue.svg)](https://www.patreon.com/laniksj/overview)
