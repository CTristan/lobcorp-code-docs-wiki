# Enum TransformMode

**Namespace:** [Spine](/api/Spine)
**Assembly:** Assembly-CSharp.dll

[`[System.FlagsAttribute]`](#)

```csharp
[Flags]
public enum TransformMode
```

## Fields

### Normal

```csharp
Normal = 0
```

#### Field Value

**Type:** Spine.TransformMode

### NoRotationOrReflection

```csharp
NoRotationOrReflection = 1
```

#### Field Value

**Type:** Spine.TransformMode

### NoScale

```csharp
NoScale = 2
```

#### Field Value

**Type:** Spine.TransformMode

### NoScaleOrReflection

```csharp
NoScaleOrReflection = 6
```

#### Field Value

**Type:** Spine.TransformMode

### OnlyTranslation

```csharp
OnlyTranslation = NoRotationOrReflection | NoScaleOrReflection
```

#### Field Value

**Type:** Spine.TransformMode
