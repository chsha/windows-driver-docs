---
title: WS-DSD Event Elements
description: WS-DSD Event Elements
ms.assetid: 329dbfe5-b430-443e-922a-43694bff0d50
keywords: ["WS-DSD Event Elements"]
ms.author: windowsdriverdev
ms.date: 11/28/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-devices
---

# WS-DSD Event Elements


The scanner must implement eventing as it is defined by the WS-Eventing specification. The scanner will be an extension of the WS-Eventing port type and must add the operations that are defined for the scan service to create and manage event subscriptions.

The eventing model for WS-DSD notifies the control point of changes in the scanner status and the job status.

A WS-DSD system must support the following events:

[JobEndStateEvent](jobendstateevent.md)

[JobStatusEvent](jobstatusevent.md)

[ScannerElementsChangeEvent](scannerelementschangeevent.md)

[ScannerStatusConditionClearedEvent](scannerstatusconditionclearedevent.md)

[ScannerStatusConditionEvent](scannerstatusconditionevent.md)

[ScannerStatusSummaryEvent](scannerstatussummaryevent.md)

 

 

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bimage\image%5D:%20WS-DSD%20Event%20Elements%20%20RELEASE:%20%2811/8/2017%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")




