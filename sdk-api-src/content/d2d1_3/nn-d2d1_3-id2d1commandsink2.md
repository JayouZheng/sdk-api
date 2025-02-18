---
UID: NN:d2d1_3.ID2D1CommandSink2
title: ID2D1CommandSink2 (d2d1_3.h)
description: This interface performs all the same functions as the existing ID2D1CommandSink1 interface. It also enables access to ink rendering and gradient mesh rendering.
old-location: direct2d\id2d1commandsink2.htm
tech.root: Direct2D
ms.assetid: bd1a22a8-bbf3-d515-5596-1797e261cd1e
ms.date: 12/05/2018
ms.keywords: ID2D1CommandSink2, ID2D1CommandSink2 interface [Direct2D], ID2D1CommandSink2 interface [Direct2D],described, d2d1_3/ID2D1CommandSink2, direct2d.id2d1commandsink2
f1_keywords:
- d2d1_3/ID2D1CommandSink2
dev_langs:
- c++
req.header: d2d1_3.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 8.1 [desktop apps \| UWP apps]
req.target-min-winversvr: Windows Server 2012 R2 [desktop apps \| UWP apps]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- d2d1_3.h
api_name:
- ID2D1CommandSink2
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# ID2D1CommandSink2 interface


## -description


This interface performs all the same functions as the existing <a href="https://docs.microsoft.com/windows/desktop/api/d2d1_1/nn-d2d1_1-id2d1commandsink">ID2D1CommandSink1</a> interface. 
   It also enables access to ink rendering and gradient mesh rendering.


## -inheritance

The <b xmlns:loc="http://microsoft.com/wdcml/l10n">ID2D1CommandSink2</b> interface inherits from <a href="https://docs.microsoft.com/windows/desktop/api/d2d1_1/nn-d2d1_1-id2d1commandsink">ID2D1CommandSink1</a>. <b>ID2D1CommandSink2</b> also has these types of members:
<ul>
<li><a href="https://docs.microsoft.com/">Methods</a></li>
</ul>

## -members

The <b>ID2D1CommandSink2</b> interface has these methods.
<table class="members" id="memberListMethods">
<tr>
<th align="left" width="37%">Method</th>
<th align="left" width="63%">Description</th>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d2d1_3/nf-d2d1_3-id2d1commandsink2-drawgdimetafile">DrawGdiMetafile</a>
</td>
<td align="left" width="63%">
Draws a metafile to the command sink using the given source and destination rectangles.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d2d1_3/nf-d2d1_3-id2d1commandsink2-drawgradientmesh">DrawGradientMesh</a>
</td>
<td align="left" width="63%">
Renders a given gradient mesh to the target.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://docs.microsoft.com/windows/desktop/api/d2d1_3/nf-d2d1_3-id2d1commandsink2-drawink">DrawInk</a>
</td>
<td align="left" width="63%">
Renders the given ink object using the given brush and ink style.

</td>
</tr>
</table> 


## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/d2d1_1/nn-d2d1_1-id2d1commandsink">ID2D1CommandSink1</a>
 

 

