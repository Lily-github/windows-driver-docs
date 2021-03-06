---
title: KSPROPERTY\_VPCONFIG\_NUMCONNECTINFO
description: The KSPROPERTY\_VPCONFIG\_NUMCONNECTINFO property obtains the maximum number of electrical connection configurations.
ms.assetid: 8ffab85d-cf0d-44d7-ba37-692c3adfa1e5
keywords: ["KSPROPERTY_VPCONFIG_NUMCONNECTINFO Streaming Media Devices"]
topic_type:
- apiref
api_name:
- KSPROPERTY_VPCONFIG_NUMCONNECTINFO
api_location:
- ksmedia.h
api_type:
- HeaderDef
ms.author: windowsdriverdev
ms.date: 11/28/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-devices
---

# KSPROPERTY\_VPCONFIG\_NUMCONNECTINFO


The KSPROPERTY\_VPCONFIG\_NUMCONNECTINFO property obtains the maximum number of electrical connection configurations.

## <span id="ddk_ksproperty_vpconfig_numconnectinfo_ks"></span><span id="DDK_KSPROPERTY_VPCONFIG_NUMCONNECTINFO_KS"></span>


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
<th>Property descriptor type</th>
<th>Property value type</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Yes</p></td>
<td><p>No</p></td>
<td><p>Pin</p></td>
<td><p>[<strong>KSPROPERTY</strong>](https://msdn.microsoft.com/library/windows/hardware/ff564262)</p></td>
<td><p>DWORD</p></td>
</tr>
</tbody>
</table>

 

The property value (operation data) is a DWORD that describes the maximum number of video port configurations.

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

 

 





