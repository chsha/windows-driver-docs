---
title: KSPROPERTY\_VIDEOPROCAMP\_DIGITAL\_MULTIPLIER
description: The KSPROPERTY\_VIDEOPROCAMP\_DIGITAL\_MULTIPLIER property specifies the amount of digital zoom to apply to the image.
ms.assetid: e566dd2b-d99a-4e7f-888e-f0f431618c2d
keywords: ["KSPROPERTY_VIDEOPROCAMP_DIGITAL_MULTIPLIER Streaming Media Devices"]
topic_type:
- apiref
api_name:
- KSPROPERTY_VIDEOPROCAMP_DIGITAL_MULTIPLIER
api_location:
- Ksmedia.h
api_type:
- HeaderDef
ms.author: windowsdriverdev
ms.date: 11/28/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-devices
---

# KSPROPERTY\_VIDEOPROCAMP\_DIGITAL\_MULTIPLIER


The KSPROPERTY\_VIDEOPROCAMP\_DIGITAL\_MULTIPLIER property specifies the amount of digital zoom to apply to the image.

## <span id="ddk_ksproperty_videoprocamp_digital_multiplier_ks"></span><span id="DDK_KSPROPERTY_VIDEOPROCAMP_DIGITAL_MULTIPLIER_KS"></span>


### <span id="Usage_Summary_Table"></span><span id="usage_summary_table"></span><span id="USAGE_SUMMARY_TABLE"></span>Usage Summary Table

<table>
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<thead>
<tr class="header">
<th>Get</th>
<th>Set</th>
<th>Target</th>
<th>Property Descriptor Type</th>
<th>Property Value Type</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Filter or node</p></td>
<td><p>[<strong>KSPROPERTY_VIDEOPROCAMP_S</strong>](https://msdn.microsoft.com/library/windows/hardware/ff566089) or [<strong>KSPROPERTY_VIDEOPROCAMP_NODE_S</strong>](https://msdn.microsoft.com/library/windows/hardware/ff566080)</p></td>
<td><p>LONG</p></td>
</tr>
</tbody>
</table>

 

The property value (operation data) is a LONG that specifies a camera's digital multiplier setting. The value specifies the digital multiplier value that the camera applies to the image.

Remarks
-------

When making a set request, the client should supply a digital multiplier value in the **Value** member of the KSPROPERTY\_VIDEOPROCAMP\_NODE\_S structure.

To determine the range of digital multiplier values supported by the device, an application can issue a KSPROPERTY\_TYPE\_BASICSUPPORT request. You can specify KSPROPERTY\_TYPE\_BASICSUPPORT in the **Flags** member of the [**KSPROPERTY\_ITEM**](https://msdn.microsoft.com/library/windows/hardware/ff565176) structure.

When making a get request, the client receives a value of type LONG in the **Value** member of the KSPROPERTY\_VIDEOPROCAMP\_NODE\_S structure.

Requirements
------------

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Header</p></td>
<td>Ksmedia.h (include Ksmedia.h)</td>
</tr>
</tbody>
</table>

## <span id="see_also"></span>See also


[**KSPROPERTY**](https://msdn.microsoft.com/library/windows/hardware/ff564262)

[**KSPROPERTY\_VIDEOPROCAMP\_S**](https://msdn.microsoft.com/library/windows/hardware/ff566089)

 

 

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bstream\stream%5D:%20KSPROPERTY_VIDEOPROCAMP_DIGITAL_MULTIPLIER%20%20RELEASE:%20%2811/22/2017%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")





