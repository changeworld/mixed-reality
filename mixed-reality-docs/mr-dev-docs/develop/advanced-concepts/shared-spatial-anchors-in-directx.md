---
title: Use anchors to share holograms
description: Learn how to synchronize two HoloLens devices by sharing local and Azure spatial anchors in DirectX applications.
author: vtieto
ms.author: vinnietieto
ms.date: 9/8/2021
ms.topic: article
keywords: HoloLens, synchronize, spatial anchor, transfer, multiplayer, view, scenario, walkthrough, sample code, Azure, Azure Spatial Anchors, ASA
---

# Use anchors to share holograms

> [!NOTE]
> This article relates to the legacy WinRT native APIs.  For new native app projects, we recommend using the **[OpenXR API](../native/openxr-getting-started.md)**.

A shared experience is one where multiple users with their own HoloLens, iOS, or Android device, collectively view and interact with the same hologram. The hologram is positioned at a fixed point in space using spatial anchor sharing.

This article provides a brief introduction to local anchors.

## Local anchor transfers

In situations where you can't use Azure Spatial Anchors, [local anchor transfers](../../out-of-scope/local-anchor-transfers-in-directx.md) enable one HoloLens device to export an anchor to be imported by a second HoloLens device.  This approach provides less robust anchor recall than Azure Spatial Anchors, and iOS and Android devices are not supported by this approach.

## See also

* [Shared experiences in mixed reality](../../design/shared-experiences-in-mixed-reality.md)
