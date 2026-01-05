# Class BinahStaticData

**Namespace:** [BinahBoss](/api/BinahBoss)
**Assembly:** Assembly-CSharp.dll

```csharp
public static class BinahStaticData
```

## Inheritance
[object](https://learn.microsoft.com/dotnet/api/system.object) → BinahStaticData

## Inherited Members
[Equals(object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object)), [Equals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.equals#system-object-equals(system-object-system-object)), [GetHashCode()](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), [GetType()](https://learn.microsoft.com/dotnet/api/system.object.gettype), [MemberwiseClone()](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), [ToString()](https://learn.microsoft.com/dotnet/api/system.object.tostring), [ReferenceEquals(object, object)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals)

## Fields

### AttackDelay

```csharp
public static MinMax AttackDelay
```

#### Field Value

**Type:** Global.MinMax

### BinahGroggyTime

```csharp
public static MinMax BinahGroggyTime
```

#### Field Value

**Type:** Global.MinMax

### EightColumnDelay

```csharp
public static MinMax EightColumnDelay
```

#### Field Value

**Type:** Global.MinMax

### EightColumnProb

```csharp
public static float EightColumnProb
```

#### Field Value

**Type:** System.Single

### First_Blade_B

```csharp
public static DamageInfo First_Blade_B
```

#### Field Value

**Type:** Global.DamageInfo

### First_Blade_P

```csharp
public static DamageInfo First_Blade_P
```

#### Field Value

**Type:** Global.DamageInfo

### First_Blade_R

```csharp
public static DamageInfo First_Blade_R
```

#### Field Value

**Type:** Global.DamageInfo

### First_Blade_W

```csharp
public static DamageInfo First_Blade_W
```

#### Field Value

**Type:** Global.DamageInfo

### ID_BlackOverload_Failure

```csharp
public static int ID_BlackOverload_Failure
```

#### Field Value

**Type:** System.Int32

### ID_BlackOverload_Success

```csharp
public static int ID_BlackOverload_Success
```

#### Field Value

**Type:** System.Int32

### ID_BladeThrow_End

```csharp
public static int ID_BladeThrow_End
```

#### Field Value

**Type:** System.Int32

### ID_BladeThrow_Start

```csharp
public static int[] ID_BladeThrow_Start
```

#### Field Value

**Type:** System.Int32[]

### ID_ColumnOverload_Failure

```csharp
public static int ID_ColumnOverload_Failure
```

#### Field Value

**Type:** System.Int32

### ID_ColumnOverload_Success

```csharp
public static int ID_ColumnOverload_Success
```

#### Field Value

**Type:** System.Int32

### ID_ColumnThrow_End

```csharp
public static int[] ID_ColumnThrow_End
```

#### Field Value

**Type:** System.Int32[]

### ID_ColumnThrow_Start

```csharp
public static int[] ID_ColumnThrow_Start
```

#### Field Value

**Type:** System.Int32[]

### ID_EightColumn_Start

```csharp
public static int[] ID_EightColumn_Start
```

#### Field Value

**Type:** System.Int32[]

### ID_GoldenOverload_Failure

```csharp
public static int ID_GoldenOverload_Failure
```

#### Field Value

**Type:** System.Int32

### ID_GoldenOverload_Success

```csharp
public static int ID_GoldenOverload_Success
```

#### Field Value

**Type:** System.Int32

### ID_Thorn_Start

```csharp
public static int[] ID_Thorn_Start
```

#### Field Value

**Type:** System.Int32[]

### ID_WaveOverload_Failure

```csharp
public static int ID_WaveOverload_Failure
```

#### Field Value

**Type:** System.Int32

### ID_WaveOverload_Success

```csharp
public static int ID_WaveOverload_Success
```

#### Field Value

**Type:** System.Int32

### Second_BlackThron

```csharp
public static DamageInfo Second_BlackThron
```

#### Field Value

**Type:** Global.DamageInfo

### Third_Column_B

```csharp
public static DamageInfo Third_Column_B
```

#### Field Value

**Type:** Global.DamageInfo

### Third_Column_P

```csharp
public static DamageInfo Third_Column_P
```

#### Field Value

**Type:** Global.DamageInfo

### Third_Column_R

```csharp
public static DamageInfo Third_Column_R
```

#### Field Value

**Type:** Global.DamageInfo

### Third_Column_W

```csharp
public static DamageInfo Third_Column_W
```

#### Field Value

**Type:** Global.DamageInfo

### Wave_Damage

```csharp
public static DamageInfo Wave_Damage
```

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

#### Parameters

| Name | Type | Description |
| --- | --- | --- |
| `ary` | `System.Int32[]` |  |

#### Returns

**Type:** System.Int32
