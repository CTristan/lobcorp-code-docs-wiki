# Class UncontrollableAction

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class UncontrollableAction : HierarchicalData
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [HierarchicalData](/api/HierarchicalData) → UncontrollableAction

## Inherited Members
[_H_index](/api/HierarchicalData#h-index), [InitialSetting()](/api/HierarchicalData#initialsetting), [GetHierachicalName()](/api/HierarchicalData#gethierachicalname), [SetHierarchicalIndex(int)](/api/HierarchicalData#sethierarchicalindex-int), [Comparer(HierarchicalData)](/api/HierarchicalData#comparer-hierarchicaldata), [isUpperHierarchy(HierarchicalData)](/api/HierarchicalData#isupperhierarchy-hierarchicaldata), [Comparer(HierarchicalData, HierarchicalData)](/api/HierarchicalData#comparer-hierarchicaldata-hierarchicaldata), [HierachicalIndex](/api/HierarchicalData#hierachicalindex), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Constructors

### UncontrollableAction()

```csharp
public UncontrollableAction()
```

## Methods

### CastingSlider(Slider)

```csharp
public virtual bool CastingSlider(Slider slider)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `slider` | `UnityEngine.UI.Slider` |  |

#### Returns

**Type:** System.Boolean

### Execute()

```csharp
public virtual void Execute()
```

### HasAttackAnim()

```csharp
public virtual bool HasAttackAnim()
```

#### Returns

**Type:** System.Boolean

### HasUniqueHostility()

```csharp
public virtual bool HasUniqueHostility()
```

#### Returns

**Type:** System.Boolean

### Init()

```csharp
public virtual void Init()
```

### IsAttackTargetable()

```csharp
public virtual bool IsAttackTargetable()
```

#### Returns

**Type:** System.Boolean

### IsHostile()

```csharp
public virtual bool IsHostile()
```

#### Returns

**Type:** System.Boolean

### IsNextAttackWillKillTarget()

```csharp
public virtual bool IsNextAttackWillKillTarget()
```

#### Returns

**Type:** System.Boolean

### IsPreferredTouch()

```csharp
public virtual bool IsPreferredTouch()
```

#### Returns

**Type:** System.Boolean

### OnClick()

```csharp
public virtual void OnClick()
```

### OnDestroy()

```csharp
public virtual void OnDestroy()
```

### OnDie()

```csharp
public virtual void OnDie()
```

### OnKillTarget()

```csharp
public virtual void OnKillTarget()
```

### OnNextAttakInvokeKill()

```csharp
public virtual bool OnNextAttakInvokeKill()
```

#### Returns

**Type:** System.Boolean

### OnPrevDie()

```csharp
public virtual void OnPrevDie()
```

### OnStageEnd()

```csharp
public virtual void OnStageEnd()
```

### OnTakeMentalDamage(int)

```csharp
public virtual void OnTakeMentalDamage(int damage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `damage` | `System.Int32` |  |

### OnTakePhysicalDamage(int)

```csharp
public virtual void OnTakePhysicalDamage(int damage)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `damage` | `System.Int32` |  |

### SetAttackAnim()

```csharp
public virtual void SetAttackAnim()
```

### ShowUnconSpeech(string)

```csharp
public virtual void ShowUnconSpeech(string key)
```

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

### UnderAttack()

```csharp
public virtual void UnderAttack()
```
