---
title: Getting Started with the Windows Driver Kit
description: This section describes how to get the WDK and samples and start building Windows drivers.
ms.assetid: 5502AAF9-2400-4338-A646-C746B29F9A44
ms.author: windowsdriverdev
ms.date: 04/20/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-devices
---

# Getting Started with the Windows Driver Kit

Windows Driver Kit (WDK) 10 is integrated with Microsoft Visual Studio 2017 and [Debugging Tools for Windows][dbg]. This integrated environment gives you the tools you need to develop, build, package, deploy, test, and debug drivers. You can run many basic certification tests in the integrated environment. The Windows Driver Kit (WDK) includes templates for several technologies and driver models, including [Windows Driver Frameworks](https://msdn.microsoft.com/en-us/library/windows/hardware/ff557565), Universal Serial Bus (USB), print, networking, and file system filters.

For fundamental driver concepts and an introduction to driver development tools, please see [Getting started with Windows drivers](gettingstarted/index.md).

## Universal Windows driver samples

Universal Windows driver samples are available on GitHub. For more info, see [Microsoft/Windows-driver-samples](http://go.microsoft.com/fwlink/p/?LinkId=534087).

## How to get WDK 10

Install [Visual Studio 2017](https://go.microsoft.com/fwlink/p/?LinkId=698539), and then install [WDK 10](https://go.microsoft.com/fwlink/p/?LinkId=733614). [Debugging Tools for Windows][dbg] is included in WDK 10, so you don't need to download it separately.

## Run-time requirements for WDK 10

You can use WDK 10 to develop drivers that run on the these operating systems:

* Windows 10
* Windows 8.1
* Windows 8
* Windows 7
* Windows Server 2016 Technical Preview
* Windows Server 2008 R2

You can run WDK 10, integrated with Visual Studio 2015, on these operating systems:

* Windows 10
* Windows 8.1
* Windows 8
* Windows 7

For additional driver documentation, see [Windows Driver Kit (WDK)](https://msdn.microsoft.com/en-us/library/windows/hardware/ff557573).

[dbg]: https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/index