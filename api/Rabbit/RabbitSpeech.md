---
uid: Rabbit.RabbitSpeech
canonical_path: /api/Rabbit/RabbitSpeech
---

# Class RabbitSpeech

**Namespace:** [Rabbit](/api/Rabbit)
**Assembly:** Assembly-CSharp.dll

```csharp
public class RabbitSpeech
```
For [rabbit](/api/Global/Model/RabbitModel) speech during the Rabbit Protocol.

See also [RabbitConversationType](/api/Rabbit/RabbitConversationType).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → RabbitSpeech

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### RabbitSpeech()

```csharp
public RabbitSpeech()
```

## Fields

### _unit

```csharp
private RabbitUnit _unit
```
#INC


#### Field Value

**Type:** Global.RabbitUnit

### currentSpeechProb

```csharp
public float currentSpeechProb
```
#INC


#### Field Value

**Type:** System.Single

### layout

```csharp
public VerticalLayoutGroup layout
```
#INC


#### Field Value

**Type:** UnityEngine.UI.VerticalLayoutGroup

### rootActiveControl

```csharp
public GameObject rootActiveControl
```
#INC


#### Field Value

**Type:** UnityEngine.GameObject

### speechBg

```csharp
public Image speechBg
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Image

### speechText

```csharp
public Text speechText
```
#INC


#### Field Value

**Type:** UnityEngine.UI.Text

### speechTimer

```csharp
public Timer speechTimer
```
#INC


#### Field Value

**Type:** Global.Timer

## Methods

### Execute()

```csharp
public void Execute()
```
#INC


### Init(RabbitUnit)

```csharp
public void Init(RabbitUnit unit)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `unit` | `Global.RabbitUnit` |  |

### SetSpeechProb(float)

```csharp
public void SetSpeechProb(float prob)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `prob` | `System.Single` |  |

### Speech(string, float)

```csharp
public void Speech(string text, float speechTime = 3)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `text` | `System.String` |  |
| `speechTime` | `System.Single` |  |
