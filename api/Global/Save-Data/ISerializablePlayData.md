---
uid: Global.ISerializablePlayData
canonical_path: /api/Global/Misc/ISerializablePlayData
---
# Interface ISerializablePlayData
**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
internal interface ISerializablePlayData
```
> This section may have incomplete or incorrect information.
{.is-warning}

Interface for classes which have data that needs to be saved and loaded.

#### Methods
	Dictionary<string, object> GetSaveData()
	void LoadData(Dictionary<string, object> dic)


## Methods
### GetSaveData()
```csharp
Dictionary<string, object> GetSaveData()
```


#### Returns
**Type:** System.Collections.Generic.Dictionary{System.String,System.Object}

### LoadData(Dictionary<string, object>)
```csharp
void LoadData(Dictionary<string, object> dic)
```


#### Parameters
| Name | Type | Description |
| --- | --- | --- |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.Object}` |  |




