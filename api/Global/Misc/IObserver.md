---
uid: Global.IObserver
canonical_path: /api/Global/Misc/IObserver
---

# Interface IObserver

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public interface IObserver
```
Interface for all things which listen for events.

Note: *some* events will have additional information, which needs to be grabbed from param.

#### Method
void OnNotice(string notice, params object[] param)


%% An aside: This should probably not be implemented this way. %%

#exclude-from-graph 


## Methods

### OnNotice(string, params object[])

```csharp
void OnNotice(string notice, params object[] param)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `notice` | `System.String` |  |
| `param` | `System.Object[]` |  |
