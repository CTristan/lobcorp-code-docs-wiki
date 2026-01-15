---
uid: Global.BlackLovePanicReady
canonical_path: /api/Global/Misc/BlackLovePanicReady
---

# Class BlackLovePanicReady

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class BlackLovePanicReady : PanicReady
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [PanicAction](/api/Global/Action/PanicAction) → [PanicReady](/api/Global/Misc/PanicReady) → BlackLovePanicReady

## Inherited Members
[actor](/api/Global/Misc/PanicReady#actor), [elapsedTime](/api/Global/Misc/PanicReady#elapsedtime), [waitTime](/api/Global/Misc/PanicReady#waittime), [PanicEnd()](/api/Global/Misc/PanicReady#panicend), [StartPanicAction()](/api/Global/Misc/PanicReady#startpanicaction), [OnDie()](/api/Global/Action/PanicAction#ondie), [GetAttackSpeedMultiplier()](/api/Global/Action/PanicAction#getattackspeedmultiplier), [GetMovementMultiplier()](/api/Global/Action/PanicAction#getmovementmultiplier), [GetDefenseMultiplier()](/api/Global/Action/PanicAction#getdefensemultiplier), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Constructors

### BlackLovePanicReady(WorkerModel, BlackLoveBuf)

```csharp
public BlackLovePanicReady(WorkerModel target, BlackLoveBuf buf)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `target` | `Global.WorkerModel` |  |
| `buf` | `Global.BlackLoveBuf` |  |

## Fields

### buf

```csharp
private BlackLoveBuf buf
```

#### Field Value

**Type:** Global.BlackLoveBuf

## Methods

### Execute()

```csharp
public override void Execute()
```

### Init()

```csharp
public override void Init()
```

### StartPanic()

```csharp
public void StartPanic()
```
