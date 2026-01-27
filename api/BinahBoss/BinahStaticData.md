---
uid: BinahBoss.BinahStaticData
canonical_path: /api/BinahBoss/BinahStaticData
---

# Class BinahStaticData

**Namespace:** [BinahBoss](/api/BinahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public static class BinahStaticData
```
A bunch of static variables for [Binah's core suppression](/api/Global/Misc/BinahBossBase).


## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → BinahStaticData

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), [InternalGetHashCode(object)](https://learn.microsoft.com/dotnet/api/system.object.internalgethashcode), [obj_address()](https://learn.microsoft.com/dotnet/api/system.object.obj_address), [FieldGetter(string, string, ref object)](https://learn.microsoft.com/dotnet/api/system.object.fieldgetter), [FieldSetter(string, string, object)](https://learn.microsoft.com/dotnet/api/system.object.fieldsetter)

## Fields

### AttackDelay

```csharp
public static MinMax AttackDelay
```
#INC


#### Field Value

**Type:** Global.MinMax

### BinahGroggyTime

```csharp
public static MinMax BinahGroggyTime
```
#INC


#### Field Value

**Type:** Global.MinMax

### EightColumnDelay

```csharp
public static MinMax EightColumnDelay
```
#INC


#### Field Value

**Type:** Global.MinMax

### EightColumnProb

```csharp
public static float EightColumnProb
```
#INC


#### Field Value

**Type:** System.Single

### First_Blade_B

```csharp
public static DamageInfo First_Blade_B
```
#INC


#### Field Value

**Type:** Global.DamageInfo

### First_Blade_P

```csharp
public static DamageInfo First_Blade_P
```
#INC


#### Field Value

**Type:** Global.DamageInfo

### First_Blade_R

```csharp
public static DamageInfo First_Blade_R
```
#INC


#### Field Value

**Type:** Global.DamageInfo

### First_Blade_W

```csharp
public static DamageInfo First_Blade_W
```
#INC


#### Field Value

**Type:** Global.DamageInfo

### ID_BlackOverload_Failure

```csharp
public static int ID_BlackOverload_Failure
```
#INC


#### Field Value

**Type:** System.Int32

### ID_BlackOverload_Success

```csharp
public static int ID_BlackOverload_Success
```
#INC


#### Field Value

**Type:** System.Int32

### ID_BladeThrow_End

```csharp
public static int ID_BladeThrow_End
```
#INC


#### Field Value

**Type:** System.Int32

### ID_BladeThrow_Start

```csharp
public static int[] ID_BladeThrow_Start
```
#INC


#### Field Value

**Type:** System.Int32[]

### ID_ColumnOverload_Failure

```csharp
public static int ID_ColumnOverload_Failure
```
#INC


#### Field Value

**Type:** System.Int32

### ID_ColumnOverload_Success

```csharp
public static int ID_ColumnOverload_Success
```
#INC


#### Field Value

**Type:** System.Int32

### ID_ColumnThrow_End

```csharp
public static int[] ID_ColumnThrow_End
```
#INC


#### Field Value

**Type:** System.Int32[]

### ID_ColumnThrow_Start

```csharp
public static int[] ID_ColumnThrow_Start
```
#INC


#### Field Value

**Type:** System.Int32[]

### ID_EightColumn_Start

```csharp
public static int[] ID_EightColumn_Start
```
#INC


#### Field Value

**Type:** System.Int32[]

### ID_GoldenOverload_Failure

```csharp
public static int ID_GoldenOverload_Failure
```
#INC


#### Field Value

**Type:** System.Int32

### ID_GoldenOverload_Success

```csharp
public static int ID_GoldenOverload_Success
```
#INC


#### Field Value

**Type:** System.Int32

### ID_Thorn_Start

```csharp
public static int[] ID_Thorn_Start
```
#INC


#### Field Value

**Type:** System.Int32[]

### ID_WaveOverload_Failure

```csharp
public static int ID_WaveOverload_Failure
```
#INC


#### Field Value

**Type:** System.Int32

### ID_WaveOverload_Success

```csharp
public static int ID_WaveOverload_Success
```
#INC


#### Field Value

**Type:** System.Int32

### RwbpRange

```csharp
private static MinMax RwbpRange
```
#INC


#### Field Value

**Type:** Global.MinMax

### Second_BlackThron

```csharp
public static DamageInfo Second_BlackThron
```
#INC


#### Field Value

**Type:** Global.DamageInfo

### Third_Column_B

```csharp
public static DamageInfo Third_Column_B
```
#INC


#### Field Value

**Type:** Global.DamageInfo

### Third_Column_P

```csharp
public static DamageInfo Third_Column_P
```
#INC


#### Field Value

**Type:** Global.DamageInfo

### Third_Column_R

```csharp
public static DamageInfo Third_Column_R
```
#INC


#### Field Value

**Type:** Global.DamageInfo

### Third_Column_W

```csharp
public static DamageInfo Third_Column_W
```
#INC


#### Field Value

**Type:** Global.DamageInfo

### Wave_Damage

```csharp
public static DamageInfo Wave_Damage
```
#INC


#### Field Value

**Type:** Global.DamageInfo

## Properties

### RandType

```csharp
public static RwbpType RandType { get; }
```

#### Property Value

**Type:** Global.RwbpType

## Methods

### GetRwbpTypeRandom(MinMax)

```csharp
public static RwbpType GetRwbpTypeRandom(MinMax range)
```
#INC
#code-generated


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `range` | `Global.MinMax` |  |

#### Returns

**Type:** Global.RwbpType

### SelectRandomID(params int[])

```csharp
public static int SelectRandomID(params int[] ary)
```
#INC


#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ary` | `System.Int32[]` |  |

#### Returns

**Type:** System.Int32
