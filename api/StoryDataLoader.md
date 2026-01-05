# Class StoryDataLoader

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class StoryDataLoader
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → StoryDataLoader

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### StoryDataLoader()

```csharp
public StoryDataLoader()
```

## Fields

### ModTextLib

```csharp
public static Dictionary<string, string> ModTextLib
```

#### Field Value

**Type:** System.Collections.Generic.Dictionary{System.String,System.String}

## Methods

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

### LoadCommand_ending(XmlNode, StoryScriptCommandList)

```csharp
public void LoadCommand_ending(XmlNode cmdNode, StoryScriptCommandList cmdList)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |
| `cmdList` | `Global.StoryScriptCommandList` |  |

### LoadCommand_hide_exdiag(XmlNode, StoryScriptCommandList)

```csharp
public void LoadCommand_hide_exdiag(XmlNode cmdNode, StoryScriptCommandList cmdList)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |
| `cmdList` | `Global.StoryScriptCommandList` |  |

### LoadCommand_hide_option(XmlNode, StoryScriptCommandList)

```csharp
public void LoadCommand_hide_option(XmlNode cmdNode, StoryScriptCommandList cmdList)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |
| `cmdList` | `Global.StoryScriptCommandList` |  |

### LoadCommand_hide_ui(XmlNode, StoryScriptCommandList)

```csharp
public void LoadCommand_hide_ui(XmlNode cmdNode, StoryScriptCommandList cmdList)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |
| `cmdList` | `Global.StoryScriptCommandList` |  |

### LoadCommand_return_title(XmlNode, StoryScriptCommandList)

```csharp
public void LoadCommand_return_title(XmlNode cmdNode, StoryScriptCommandList cmdList)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |
| `cmdList` | `Global.StoryScriptCommandList` |  |

### LoadCommand_show_exdiag(XmlNode, StoryScriptCommandList)

```csharp
public void LoadCommand_show_exdiag(XmlNode cmdNode, StoryScriptCommandList cmdList)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `cmdNode` | `System.Xml.XmlNode` |  |
| `cmdList` | `Global.StoryScriptCommandList` |  |

### LoadCommand_show_ui(XmlNode, StoryScriptCommandList)

```csharp
public void LoadCommand_show_ui(XmlNode cmdNode, StoryScriptCommandList cmdList)
```

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

### LoadStoryData()

```csharp
public void LoadStoryData()
```

### XmlLoad(string, Dictionary<string, string>)

```csharp
public void XmlLoad(string data, Dictionary<string, string> dic)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `data` | `System.String` |  |
| `dic` | `System.Collections.Generic.Dictionary{System.String,System.String}` |  |
