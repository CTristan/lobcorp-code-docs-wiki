---
uid: Global.StoryDataLoader
canonical_path: /api/Global/Loader/StoryDataLoader
---

# Class StoryDataLoader

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class StoryDataLoader
```
Loads the story data, including (especially) commands.
#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → StoryDataLoader

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### StoryDataLoader()

```csharp
public StoryDataLoader()
```

## Fields

### idRegex

```csharp
private Regex idRegex
```
#INC


#### Field Value

**Type:** System.Text.RegularExpressions.Regex

### ModTextLib

```csharp
public static Dictionary<string, string> ModTextLib
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,System.String}

## Methods

### ConvertToDirectionEnum(string)

```csharp
private StoryScriptDirectionEnum ConvertToDirectionEnum(string str)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `str` | `System.String` |  |

#### Returns

**Type:** Global.StoryScriptDirectionEnum

### ConvertToPosEnum(string)

```csharp
private StoryScriptPosEnum ConvertToPosEnum(string str)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `str` | `System.String` |  |

#### Returns

**Type:** Global.StoryScriptPosEnum

### GetModText(string)

```csharp
public string GetModText(string str)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `str` | `System.String` |  |

#### Returns

**Type:** System.String

### GetStoryList()

```csharp
private string[] GetStoryList()
```
#INC


#### Returns

**Type:** System.String[]

### IsValidId(string)

```csharp
private bool IsValidId(string id)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `id` | `System.String` |  |

#### Returns

**Type:** System.Boolean

### LoadCommand_add_filter(XmlNode, StoryScriptCommandList)

```csharp
private void LoadCommand_add_filter(XmlNode cmdNode, StoryScriptCommandList cmdList)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |
| `cmdList` | `Global.StoryScriptCommandList` |  |

### LoadCommand_add_filter_Blur_Blurry(XmlNode)

```csharp
private StoryFilterParameter LoadCommand_add_filter_Blur_Blurry(XmlNode cmdNode)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |

#### Returns

**Type:** Global.StoryFilterParameter

### LoadCommand_add_filter_Blur_Focus(XmlNode)

```csharp
private StoryFilterParameter LoadCommand_add_filter_Blur_Focus(XmlNode cmdNode)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |

#### Returns

**Type:** Global.StoryFilterParameter

### LoadCommand_add_filter_BlurBloom(XmlNode)

```csharp
private StoryFilterParameter LoadCommand_add_filter_BlurBloom(XmlNode cmdNode)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |

#### Returns

**Type:** Global.StoryFilterParameter

### LoadCommand_add_filter_Broken_Screen(XmlNode)

```csharp
private StoryFilterParameter LoadCommand_add_filter_Broken_Screen(XmlNode cmdNode)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |

#### Returns

**Type:** Global.StoryFilterParameter

### LoadCommand_add_filter_Distortion_Dream2(XmlNode)

```csharp
private StoryFilterParameter LoadCommand_add_filter_Distortion_Dream2(XmlNode cmdNode)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |

#### Returns

**Type:** Global.StoryFilterParameter

### LoadCommand_add_filter_Distortion_Heat(XmlNode)

```csharp
private StoryFilterParameter LoadCommand_add_filter_Distortion_Heat(XmlNode cmdNode)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |

#### Returns

**Type:** Global.StoryFilterParameter

### LoadCommand_add_filter_Distortion_Noise(XmlNode)

```csharp
private StoryFilterParameter LoadCommand_add_filter_Distortion_Noise(XmlNode cmdNode)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |

#### Returns

**Type:** Global.StoryFilterParameter

### LoadCommand_add_filter_Fire_Gradient(XmlNode)

```csharp
private StoryFilterParameter LoadCommand_add_filter_Fire_Gradient(XmlNode cmdNode)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |

#### Returns

**Type:** Global.StoryFilterParameter

### LoadCommand_add_filter_TV_Broken_Glass(XmlNode)

```csharp
private StoryFilterParameter LoadCommand_add_filter_TV_Broken_Glass(XmlNode cmdNode)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |

#### Returns

**Type:** Global.StoryFilterParameter

### LoadCommand_add_filter_Tv_Noise(XmlNode)

```csharp
private StoryFilterParameter LoadCommand_add_filter_Tv_Noise(XmlNode cmdNode)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |

#### Returns

**Type:** Global.StoryFilterParameter

### LoadCommand_add_filter_TvOldMovie2(XmlNode)

```csharp
private StoryFilterParameter LoadCommand_add_filter_TvOldMovie2(XmlNode cmdNode)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |

#### Returns

**Type:** Global.StoryFilterParameter

### LoadCommand_background(XmlNode, StoryScriptCommandList)

```csharp
private void LoadCommand_background(XmlNode cmdNode, StoryScriptCommandList cmdList)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |
| `cmdList` | `Global.StoryScriptCommandList` |  |

### LoadCommand_bgm(XmlNode, StoryScriptCommandList)

```csharp
private void LoadCommand_bgm(XmlNode cmdNode, StoryScriptCommandList cmdList)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |
| `cmdList` | `Global.StoryScriptCommandList` |  |

### LoadCommand_call(XmlNode, StoryScriptCommandList)

```csharp
private void LoadCommand_call(XmlNode cmdNode, StoryScriptCommandList cmdList)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |
| `cmdList` | `Global.StoryScriptCommandList` |  |

### LoadCommand_camera_filter(XmlNode, StoryScriptCommandList)

```csharp
private void LoadCommand_camera_filter(XmlNode cmdNode, StoryScriptCommandList cmdList)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |
| `cmdList` | `Global.StoryScriptCommandList` |  |

### LoadCommand_cg(XmlNode, StoryScriptCommandList)

```csharp
private void LoadCommand_cg(XmlNode cmdNode, StoryScriptCommandList cmdList)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |
| `cmdList` | `Global.StoryScriptCommandList` |  |

### LoadCommand_character(XmlNode, StoryScriptCommandList)

```csharp
private void LoadCommand_character(XmlNode cmdNode, StoryScriptCommandList cmdList)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |
| `cmdList` | `Global.StoryScriptCommandList` |  |

### LoadCommand_dialogue(XmlNode, StoryScriptCommandList)

```csharp
private void LoadCommand_dialogue(XmlNode cmdNode, StoryScriptCommandList cmdList)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |
| `cmdList` | `Global.StoryScriptCommandList` |  |

### LoadCommand_disappear(XmlNode, StoryScriptCommandList)

```csharp
private void LoadCommand_disappear(XmlNode cmdNode, StoryScriptCommandList cmdList)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |
| `cmdList` | `Global.StoryScriptCommandList` |  |

### LoadCommand_ending(XmlNode, StoryScriptCommandList)

```csharp
public void LoadCommand_ending(XmlNode cmdNode, StoryScriptCommandList cmdList)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |
| `cmdList` | `Global.StoryScriptCommandList` |  |

### LoadCommand_hide_exdiag(XmlNode, StoryScriptCommandList)

```csharp
public void LoadCommand_hide_exdiag(XmlNode cmdNode, StoryScriptCommandList cmdList)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |
| `cmdList` | `Global.StoryScriptCommandList` |  |

### LoadCommand_hide_option(XmlNode, StoryScriptCommandList)

```csharp
public void LoadCommand_hide_option(XmlNode cmdNode, StoryScriptCommandList cmdList)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |
| `cmdList` | `Global.StoryScriptCommandList` |  |

### LoadCommand_hide_ui(XmlNode, StoryScriptCommandList)

```csharp
public void LoadCommand_hide_ui(XmlNode cmdNode, StoryScriptCommandList cmdList)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |
| `cmdList` | `Global.StoryScriptCommandList` |  |

### LoadCommand_if(XmlNode, StoryScriptCommandList)

```csharp
private void LoadCommand_if(XmlNode cmdNode, StoryScriptCommandList cmdList)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |
| `cmdList` | `Global.StoryScriptCommandList` |  |

### LoadCommand_move_background(XmlNode, StoryScriptCommandList)

```csharp
private void LoadCommand_move_background(XmlNode cmdNode, StoryScriptCommandList cmdList)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |
| `cmdList` | `Global.StoryScriptCommandList` |  |

### LoadCommand_position(XmlNode, StoryScriptCommandList)

```csharp
private void LoadCommand_position(XmlNode cmdNode, StoryScriptCommandList cmdList)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |
| `cmdList` | `Global.StoryScriptCommandList` |  |

### LoadCommand_remove_cg(XmlNode, StoryScriptCommandList)

```csharp
private void LoadCommand_remove_cg(XmlNode cmdNode, StoryScriptCommandList cmdList)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |
| `cmdList` | `Global.StoryScriptCommandList` |  |

### LoadCommand_remove_filter(XmlNode, StoryScriptCommandList)

```csharp
private void LoadCommand_remove_filter(XmlNode cmdNode, StoryScriptCommandList cmdList)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |
| `cmdList` | `Global.StoryScriptCommandList` |  |

### LoadCommand_return_title(XmlNode, StoryScriptCommandList)

```csharp
public void LoadCommand_return_title(XmlNode cmdNode, StoryScriptCommandList cmdList)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |
| `cmdList` | `Global.StoryScriptCommandList` |  |

### LoadCommand_select(XmlNode, StoryScriptCommandList)

```csharp
private void LoadCommand_select(XmlNode cmdNode, StoryScriptCommandList cmdList)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |
| `cmdList` | `Global.StoryScriptCommandList` |  |

### LoadCommand_set_anim(XmlNode, StoryScriptCommandList)

```csharp
private void LoadCommand_set_anim(XmlNode cmdNode, StoryScriptCommandList cmdList)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |
| `cmdList` | `Global.StoryScriptCommandList` |  |

### LoadCommand_show_exdiag(XmlNode, StoryScriptCommandList)

```csharp
public void LoadCommand_show_exdiag(XmlNode cmdNode, StoryScriptCommandList cmdList)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |
| `cmdList` | `Global.StoryScriptCommandList` |  |

### LoadCommand_show_ui(XmlNode, StoryScriptCommandList)

```csharp
public void LoadCommand_show_ui(XmlNode cmdNode, StoryScriptCommandList cmdList)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |
| `cmdList` | `Global.StoryScriptCommandList` |  |

### LoadCommand_sound(XmlNode, StoryScriptCommandList)

```csharp
private void LoadCommand_sound(XmlNode cmdNode, StoryScriptCommandList cmdList)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |
| `cmdList` | `Global.StoryScriptCommandList` |  |

### LoadCommand_speak(XmlNode, StoryScriptCommandList)

```csharp
private void LoadCommand_speak(XmlNode cmdNode, StoryScriptCommandList cmdList)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |
| `cmdList` | `Global.StoryScriptCommandList` |  |

### LoadCommand_var_set(XmlNode, StoryScriptCommandList)

```csharp
private void LoadCommand_var_set(XmlNode cmdNode, StoryScriptCommandList cmdList)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |
| `cmdList` | `Global.StoryScriptCommandList` |  |

### LoadCommand_var_set_random(XmlNode, StoryScriptCommandList)

```csharp
private void LoadCommand_var_set_random(XmlNode cmdNode, StoryScriptCommandList cmdList)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |
| `cmdList` | `Global.StoryScriptCommandList` |  |

### LoadCommand_wait(XmlNode, StoryScriptCommandList)

```csharp
private void LoadCommand_wait(XmlNode cmdNode, StoryScriptCommandList cmdList)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |
| `cmdList` | `Global.StoryScriptCommandList` |  |

### LoadData(string, Dictionary<string, StoryScriptScene>)

```csharp
public void LoadData(string str, Dictionary<string, StoryScriptScene> dictionary)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `str` | `System.String` |  |
| `dictionary` | `System.Collections.Generic.Dictionary{System.String,StoryScriptScene}` |  |

### LoadModStroyData()

```csharp
public void LoadModStroyData()
```

### LoadStoryCommands(XmlNode, StoryScriptCommandList)

```csharp
private void LoadStoryCommands(XmlNode parent, StoryScriptCommandList cmdList)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `parent` | `System.Xml.XmlNode` |  |
| `cmdList` | `Global.StoryScriptCommandList` |  |

### LoadStoryData()

```csharp
public void LoadStoryData()
```
#INC
#code-generated


### TryGetStoryScriptValue(string, out StoryScriptValue)

```csharp
private bool TryGetStoryScriptValue(string valueStr, out StoryScriptValue value)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `valueStr` | `System.String` |  |
| `value` | `Global.StoryScriptValue` |  |

#### Returns

**Type:** System.Boolean

### XmlLoad(string, Dictionary<string, string>)

```csharp
public void XmlLoad(string data, Dictionary<string, string> dic)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `System.String` |  |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.String}` |  |
