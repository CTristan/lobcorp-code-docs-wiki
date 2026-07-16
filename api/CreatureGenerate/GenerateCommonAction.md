---
title: GenerateCommonAction
description: 
published: true
date: 2026-07-16T21:26:51.654Z
tags: 
editor: markdown
dateCreated: 2026-07-08T03:37:28.634Z
---

# Enum GenerateCommonAction
**Namespace:** [CreatureGenerate](/api/CreatureGenerate)
**Assembly:** Assembly-CSharp.dll

```csharp
public enum GenerateCommonAction
```
Enum used representing the action to be taken during abnormality selection.

See also [`CreatureGenerateModel::ParseActionNode(string)`](/api/CreatureGenerate/CreatureGenerateModel#parseactionnodestring).
| Name | Value | Description |
| --- | --- | --- |
| REMOVE | 0 | Action to remove certain abnormalities from the pool today. |
| ONLY | 1 | Action to restrict abnormalities to only the listed ones today. |
| NONE | 2 | Unused. |







