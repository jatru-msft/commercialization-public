---
title: WindowsR
description: Blocks the Windows logo key+R key combination used to open the Run dialog box.
MSHAttr:
- 'PreferredSiteName:MSDN'
- 'PreferredLib:/library/windows/hardware'
ms.assetid: 2845FF3B-76E6-4064-816C-CB85DFF7A14B
ms.author: alhopper
ms.date: 05/02/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-oem
---

# WindowsR


Blocks the Windows logo key+R key combination used to open the Run dialog box.

## Type


String

## Values


<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>Value</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>Allowed</em></p></td>
<td><p>The Windows logo key+R key combination is not blocked.</p>
<p>This is the default value.</p></td>
</tr>
<tr class="even">
<td><p><em>Blocked</em></p></td>
<td><p>The Windows logo key+R key combination is blocked.</p></td>
</tr>
</tbody>
</table>

 

## Parent Hierarchy


[Microsoft-Windows-Embedded-KeyboardFilterService](microsoft-windows-embedded-keyboardfilterservice.md) | **WindowsR**

## Valid Configuration Passes


offlineServicing

## Applies To


For a list of the Windows editions and architectures that this component supports, see [Microsoft-Windows-Embedded-KeyboardFilterService](microsoft-windows-embedded-keyboardfilterservice.md).

## XML example


```
<settings pass="offlineServicing">
    <component name="Microsoft-Windows-Embedded-KeyboardFilterService" processorArchitecture="amd64" publicKeyToken="31bf3856ad364e35" language="neutral" versionScope="NonSxS" xmlns:wcm="http://schemas.microsoft.com/WMIConfig/2002/State" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
        <WindowsR>Blocked</WindowsR>
    </component>
</settings>
```

 

 






