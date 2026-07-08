---
title: EmergencyLevel
description: 
published: true
date: 2026-02-25T03:54:08.528Z
tags: 
editor: markdown
dateCreated: 2026-01-06T03:57:01.017Z
---

# Enum EmergencyLevel
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public enum EmergencyLevel
```
Enum denoting the current emergency level (i.e. trumpet).

See [PlayerModel.EmergencyController](/api/Global/Misc/PlayerModelEmergencyController/).

Used by [EmergencyUI](/api/GameStatusUI/EmergencyUI/) and [BgmManager](/api/Global/IOBserver/BgmManager/), notably; and [Queen of Hatred](/api/Global/IOBserver/MagicalGirl/) for her heroic breach condition.


| Name | Value | Description |
| --- | --- | --- |
| NORMAL | 0 | Normal |
| LEVEL1 | 1 | First Trumpet |
| LEVEL2 | 2 | Second Trumpet |
| LEVEL3 | 3 | Third Trumpet |
| CHAOS | 4 | Not used|


