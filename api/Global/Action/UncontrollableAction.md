---
uid: Global.UncontrollableAction
canonical_path: /api/Global/Action/UncontrollableAction
---

# Class UncontrollableAction

**Namespace:** [Global](/api/Global)
**Assembly:** Assembly-CSharp.dll

```csharp
public class UncontrollableAction : HierarchicalData
```

An uncontrollable effect, for employees which are 'Uncontrollable' or otherwise possessed.

#INC 


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → [HierarchicalData](/api/Global/Misc/HierarchicalData) → UncontrollableAction

## Derived
[PinkCorpsUncontrollable](/api/Global/UncontrollableAction/PinkCorpsUncontrollable), [Uncontrollable_Alriune](/api/Global/UncontrollableAction/UncontrollableAlriune), [Uncontrollable_AuthorNoteMainCharacter](/api/Global/UncontrollableAction/UncontrollableAuthorNoteMainCharacter), [Uncontrollable_AuthorNoteOther](/api/Global/UncontrollableAction/UncontrollableAuthorNoteOther), [Uncontrollable_Baku](/api/Global/UncontrollableAction/UncontrollableBaku), [Uncontrollable_BigBird](/api/Global/UncontrollableAction/UncontrollableBigBird), [Uncontrollable_Censored](/api/Global/UncontrollableAction/UncontrollableCensored), [Uncontrollable_Fetus](/api/Global/UncontrollableAction/UncontrollableFetus), [Uncontrollable_LightsHammer](/api/Global/UncontrollableAction/UncontrollableLightsHammer), [Uncontrollable_Machine](/api/Global/UncontrollableAction/UncontrollableMachine), [Uncontrollable_OfficerSuicide](/api/Global/UncontrollableAction/UncontrollableOfficerSuicide), [Uncontrollable_RedShoes](/api/Global/UncontrollableAction/UncontrollableRedShoes), [Uncontrollable_RedShoesAttract](/api/Global/UncontrollableAction/UncontrollableRedShoesAttract), [Uncontrollable_Sakura](/api/Global/UncontrollableAction/UncontrollableSakura), [Uncontrollable_SilentOrchestra](/api/Global/UncontrollableAction/UncontrollableSilentOrchestra), [Uncontrollable_SingingMachine_attacker](/api/Global/UncontrollableAction/UncontrollableSingingMachineattacker), [Uncontrollable_SingingMachine_suicide](/api/Global/UncontrollableAction/UncontrollableSingingMachinesuicide), [Uncontrollable_ViscusSnake](/api/Global/UncontrollableAction/UncontrollableViscusSnake), [Uncontrollable_WolfEaten](/api/Global/UncontrollableAction/UncontrollableWolfEaten), [Uncontrollable_Yggdrasil](/api/Global/UncontrollableAction/UncontrollableYggdrasil), [Uncontrollable_Yggdrasil_Fake_Panic](/api/Global/UncontrollableAction/UncontrollableYggdrasilFakePanic), [Uncontrollable_Yggdrasil_Fake_PanicReady](/api/Global/UncontrollableAction/UncontrollableYggdrasilFakePanicReady), [Uncontrollable_YoungPrince](/api/Global/UncontrollableAction/UncontrollableYoungPrince), [Uncontrollable_DeathApostle](/api/Legacy/Uncontrollable_DeathApostle), [Uncontrollable_PlagueDoctorAttract](/api/Legacy/Uncontrollable_PlagueDoctorAttract), [Uncontorllable_PlagueDoctor](/api/WhiteNightSpace/Uncontorllable_PlagueDoctor)

## Inherited Members
[_H_index](/api/Global/Misc/HierarchicalData#h-index), [InitialSetting()](/api/Global/Misc/HierarchicalData#initialsetting), [GetHierachicalName()](/api/Global/Misc/HierarchicalData#gethierachicalname), [SetHierarchicalIndex(int)](/api/Global/Misc/HierarchicalData#sethierarchicalindex-int), [Comparer(HierarchicalData)](/api/Global/Misc/HierarchicalData#comparer-hierarchicaldata), [isUpperHierarchy(HierarchicalData)](/api/Global/Misc/HierarchicalData#isupperhierarchy-hierarchicaldata), [Comparer(HierarchicalData, HierarchicalData)](/api/Global/Misc/HierarchicalData#comparer-hierarchicaldata-hierarchicaldata), [HierachicalIndex](/api/Global/Misc/HierarchicalData#hierachicalindex), [Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

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
#INC


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
#INC


### HasAttackAnim()

```csharp
public virtual bool HasAttackAnim()
```
#INC


#### Returns

**Type:** System.Boolean

### HasUniqueHostility()

```csharp
public virtual bool HasUniqueHostility()
```
#INC


#### Returns

**Type:** System.Boolean

### Init()

```csharp
public virtual void Init()
```
#INC
#code-generated


### IsAttackTargetable()

```csharp
public virtual bool IsAttackTargetable()
```
#INC


#### Returns

**Type:** System.Boolean

### IsHostile()

```csharp
public virtual bool IsHostile()
```
#INC


#### Returns

**Type:** System.Boolean

### IsNextAttackWillKillTarget()

```csharp
public virtual bool IsNextAttackWillKillTarget()
```
#INC


#### Returns

**Type:** System.Boolean

### IsPreferredTouch()

```csharp
public virtual bool IsPreferredTouch()
```
#INC


#### Returns

**Type:** System.Boolean

### OnClick()

```csharp
public virtual void OnClick()
```
#INC


### OnDestroy()

```csharp
public virtual void OnDestroy()
```
#INC


### OnDie()

```csharp
public virtual void OnDie()
```
#INC


### OnKillTarget()

```csharp
public virtual void OnKillTarget()
```
#INC


### OnNextAttakInvokeKill()

```csharp
public virtual bool OnNextAttakInvokeKill()
```
#INC


#### Returns

**Type:** System.Boolean

### OnPrevDie()

```csharp
public virtual void OnPrevDie()
```
#INC


### OnStageEnd()

```csharp
public virtual void OnStageEnd()
```
#INC


### OnTakeMentalDamage(int)

```csharp
public virtual void OnTakeMentalDamage(int damage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `damage` | `System.Int32` |  |

### OnTakePhysicalDamage(int)

```csharp
public virtual void OnTakePhysicalDamage(int damage)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `damage` | `System.Int32` |  |

### SetAttackAnim()

```csharp
public virtual void SetAttackAnim()
```
#INC


### ShowUnconSpeech(string)

```csharp
public virtual void ShowUnconSpeech(string key)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `key` | `System.String` |  |

### UnderAttack()

```csharp
public virtual void UnderAttack()
```
#INC

