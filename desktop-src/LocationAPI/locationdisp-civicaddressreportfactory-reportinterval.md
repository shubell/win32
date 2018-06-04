---
Description: The current civic address report event interval in milliseconds.
ms.assetid: 495dd8a1-4244-468f-b295-337b393aea8a
title: LocationDisp.CivicAddressReportFactory.ReportInterval property
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# LocationDisp.CivicAddressReportFactory.ReportInterval property

\[The Location API object model is available for use in the operating systems specified in the Requirements section. It may be altered or unavailable in subsequent versions. Instead, to access location from a website, use the [W3C Geolocation API](https://msdn.microsoft.com/library/gg589513). To access location from a desktop application, use the [**Windows.Devices.Geolocation**](https://msdn.microsoft.com/library/windows/apps/br225603) API.\]

The current civic address report event interval in milliseconds.

This property is read/write.

## Syntax


```JScript
ReportInterval = LocationDisp.CivicAddressReportFactory.ReportInterval
LocationDisp.CivicAddressReportFactory.ReportInterval = ReportInterval
```



## Property value

This property is a read/write **ULONG**.

## Remarks

This value is a request for the location provider. The location provider is not required to provide reports at the interval that you requested. Read the value of this property to discover the true report interval setting.

## Requirements



|                                     |                                            |
|-------------------------------------|--------------------------------------------|
| Minimum supported client<br/> | Windows 7 \[desktop apps only\]<br/> |
| Minimum supported server<br/> | None supported<br/>                  |



 

 



