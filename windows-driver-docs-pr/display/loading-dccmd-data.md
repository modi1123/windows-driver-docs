---
title: Loading DCCMD Data
description: Loading DCCMD Data
ms.assetid: 2fceaaa6-5604-4130-ae33-8567561fcccb
keywords:
- alpha-blend data loading WDK DirectX VA
- blended pictures WDK DirectX VA , alpha-blend data loading
- DCCMD WDK DirectX VA
ms.author: windowsdriverdev
ms.date: 04/20/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-devices
---

# Loading DCCMD Data


## <span id="ddk_loading_dccmd_data_gg"></span><span id="DDK_LOADING_DCCMD_DATA_GG"></span>


The DCCMD (display control command) data is formatted in a manner compatible with the DVD ROM specification, and is to be applied along with highlight data to a DPXD surface to create an alpha-blending surface. The DCCMD data buffer contents must consist of data formatted as a list of DVD DCCMDs. For further clarification of DVD subpicture definition and data field interpretation, see *DVD Specifications for Read-Only Disk: Part 3 - Video Specification (version 1.11, May 1999)*.

 

 

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20[display\display]:%20Loading%20DCCMD%20Data%20%20RELEASE:%20%282/10/2017%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")




