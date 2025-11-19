---
layout : default
title : FormObject
parent : Classes
---
# FormObject [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/FormObject.4dm)

📊 **Overview:** 1 Properties | 1 Constructor | 4 Functions | 28 Getters | 26 Setters

🕐 *Last updated: 2025-11-19T18:10:06.095Z*

---

## 📑 Table of Contents

- [📋 Properties (1)](#properties)
- [🏗️ Constructor](#constructor) (1 param)
- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [setMaxFontSize](#setmaxfontsize) (2 params)
    - [setBestObjectSize](#setbestobjectsize) (1 param)
    - [Focus](#focus)
    - [HighlightText](#highlighttext) (2 params)
  - **Computed Attributes (Getters/Setters/Query/OrderBy)**
    - [BackgroundColor](#backgroundcolor) 🔍 ✏️ → `Integer`
    - [Bold](#bold) 🔍 ✏️ → `Boolean`
    - [Bottom](#bottom) 🔍 ✏️ → `Integer`
    - [CornerRadius](#cornerradius) 🔍 ✏️ → `Integer`
    - [DisplayFormat](#displayformat) 🔍 ✏️ → `Text`
    - [Enabled](#enabled) 🔍 ✏️ → `Boolean`
    - [Enterable](#enterable) 🔍 ✏️ → `Boolean`
    - [Font](#font) 🔍 ✏️ → `Text`
    - [FontSize](#fontsize) 🔍 ✏️ → `Integer`
    - [ForegroundColor](#foregroundcolor) 🔍 ✏️ → `Integer`
    - [HasFocus](#hasfocus) 🔍 → `Boolean`
    - [Height](#height) 🔍 ✏️ → `Integer`
    - [HelpTip](#helptip) 🔍 ✏️ → `Text`
    - [HorizontalScrollPosition](#horizontalscrollposition) 🔍 ✏️ → `Integer`
    - [Italic](#italic) 🔍 ✏️ → `Boolean`
    - [Left](#left) 🔍 ✏️ → `Integer`
    - [MaximumValue](#maximumvalue) 🔍 ✏️ → `Variant`
    - [MinimumValue](#minimumvalue) 🔍 ✏️ → `Variant`
    - [Multiline](#multiline) 🔍 ✏️ → `Boolean`
    - [PlaceholderText](#placeholdertext) 🔍 ✏️ → `Text`
    - [Pointer](#pointer) 🔍 → `Pointer`
    - [Right](#right) 🔍 ✏️ → `Integer`
    - [Title](#title) 🔍 ✏️ → `Text`
    - [Top](#top) 🔍 ✏️ → `Integer`
    - [Underline](#underline) 🔍 ✏️ → `Boolean`
    - [VerticalScrollPosition](#verticalscrollposition) 🔍 ✏️ → `Integer`
    - [Visible](#visible) 🔍 ✏️ → `Boolean`
    - [Width](#width) 🔍 ✏️ → `Integer`
---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `Name` | `Text` | - | - |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($FormObjectName : Text)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$FormObjectName` | `Text` | - | - |

---

## Functions {#functions}

### Regular Functions

#### setMaxFontSize {#setmaxfontsize}


```4d
Function setMaxFontSize($MultiLine : Boolean; $UpperFontSizeLimit : Integer)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$MultiLine` | `Boolean` | - | - |
| `$UpperFontSizeLimit` | `Integer` | - | - |

---

#### setBestObjectSize {#setbestobjectsize}


```4d
Function setBestObjectSize($HeightOnly : Boolean)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$HeightOnly` | `Boolean` | - | - |

---

#### Focus {#focus}


```4d
Function Focus
```

---

#### HighlightText {#highlighttext}


```4d
Function HighlightText($StartPosition : Integer; $EndPosition : Integer)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$StartPosition` | `Integer` | - | - |
| `$EndPosition` | `Integer` | - | - |

---

### Computed Attributes (Getters/Setters/Query/OrderBy)

#### BackgroundColor {#backgroundcolor}
 `[🔍 get, ✏️ set]`

```4d
Function get BackgroundColor -> $BackgroundColor : Integer
Function set BackgroundColor($BackgroundColor : Variant)
```

**Setter Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$BackgroundColor` | `Variant` | - |

**Returns:** `Integer`

---

#### Bold {#bold}
 `[🔍 get, ✏️ set]`

```4d
Function get Bold -> Boolean
Function set Bold($Bold : Boolean)
```

**Setter Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$Bold` | `Boolean` | - |

**Returns:** `Boolean`

---

#### Bottom {#bottom}
 `[🔍 get, ✏️ set]`

```4d
Function get Bottom -> $Bottom : Integer
Function set Bottom($Bottom : Integer)
```

**Setter Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$Bottom` | `Integer` | - |

**Returns:** `Integer`

---

#### CornerRadius {#cornerradius}
 `[🔍 get, ✏️ set]`

```4d
Function get CornerRadius -> Integer
Function set CornerRadius($CornerRadius : Integer)
```

**Setter Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$CornerRadius` | `Integer` | - |

**Returns:** `Integer`

---

#### DisplayFormat {#displayformat}
 `[🔍 get, ✏️ set]`

```4d
Function get DisplayFormat -> Text
Function set DisplayFormat($DisplayFormat : Variant)
```

**Setter Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$DisplayFormat` | `Variant` | - |

**Returns:** `Text`

---

#### Enabled {#enabled}
 `[🔍 get, ✏️ set]`

```4d
Function get Enabled -> Boolean
Function set Enabled($Enabled : Boolean)
```

**Setter Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$Enabled` | `Boolean` | - |

**Returns:** `Boolean`

---

#### Enterable {#enterable}
 `[🔍 get, ✏️ set]`

```4d
Function get Enterable -> Boolean
Function set Enterable($Enterable : Boolean)
```

**Setter Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$Enterable` | `Boolean` | - |

**Returns:** `Boolean`

---

#### Font {#font}
 `[🔍 get, ✏️ set]`

```4d
Function get Font -> Text
Function set Font($Font : Text)
```

**Setter Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$Font` | `Text` | - |

**Returns:** `Text`

---

#### FontSize {#fontsize}
 `[🔍 get, ✏️ set]`

```4d
Function get FontSize -> Integer
Function set FontSize($FontSize : Integer)
```

**Setter Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$FontSize` | `Integer` | - |

**Returns:** `Integer`

---

#### ForegroundColor {#foregroundcolor}
 `[🔍 get, ✏️ set]`

```4d
Function get ForegroundColor -> $ForegroundColor : Integer
Function set ForegroundColor($ForegroundColor : Variant)
```

**Setter Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$ForegroundColor` | `Variant` | - |

**Returns:** `Integer`

---

#### HasFocus {#hasfocus}
 `[🔍 get only]`

```4d
Function get HasFocus -> Boolean
```

**Returns:** `Boolean`

---

#### Height {#height}
 `[🔍 get, ✏️ set]`

```4d
Function get Height -> Integer
Function set Height($Height : Integer)
```

**Setter Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$Height` | `Integer` | - |

**Returns:** `Integer`

---

#### HelpTip {#helptip}
 `[🔍 get, ✏️ set]`

```4d
Function get HelpTip -> Text
Function set HelpTip($HelpTip : Text)
```

**Setter Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$HelpTip` | `Text` | - |

**Returns:** `Text`

---

#### HorizontalScrollPosition {#horizontalscrollposition}
 `[🔍 get, ✏️ set]`

```4d
Function get HorizontalScrollPosition -> $HorizontalScrollPosition : Integer
Function set HorizontalScrollPosition($HorizontalScrollPosition : Integer)
```

**Setter Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$HorizontalScrollPosition` | `Integer` | - |

**Returns:** `Integer`

---

#### Italic {#italic}
 `[🔍 get, ✏️ set]`

```4d
Function get Italic -> Boolean
Function set Italic($Italic : Boolean)
```

**Setter Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$Italic` | `Boolean` | - |

**Returns:** `Boolean`

---

#### Left {#left}
 `[🔍 get, ✏️ set]`

```4d
Function get Left -> $Left : Integer
Function set Left($Left : Integer)
```

**Setter Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$Left` | `Integer` | - |

**Returns:** `Integer`

---

#### MaximumValue {#maximumvalue}
 `[🔍 get, ✏️ set]`

```4d
Function get MaximumValue -> $MaximumValue : Variant
Function set MaximumValue($MaximumValue : Variant)
```

**Setter Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$MaximumValue` | `Variant` | - |

**Returns:** `Variant`

---

#### MinimumValue {#minimumvalue}
 `[🔍 get, ✏️ set]`

```4d
Function get MinimumValue -> $MinimumValue : Variant
Function set MinimumValue($MinimumValue : Variant)
```

**Setter Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$MinimumValue` | `Variant` | - |

**Returns:** `Variant`

---

#### Multiline {#multiline}
 `[🔍 get, ✏️ set]`

```4d
Function get Multiline -> Boolean
Function set Multiline($Multiline : Boolean)
```

**Setter Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$Multiline` | `Boolean` | - |

**Returns:** `Boolean`

---

#### PlaceholderText {#placeholdertext}
 `[🔍 get, ✏️ set]`

```4d
Function get PlaceholderText -> Text
Function set PlaceholderText($PlaceholderText : Text)
```

**Setter Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$PlaceholderText` | `Text` | - |

**Returns:** `Text`

---

#### Pointer {#pointer}
 `[🔍 get only]`

```4d
Function get Pointer -> Pointer
```

**Returns:** `Pointer`

---

#### Right {#right}
 `[🔍 get, ✏️ set]`

```4d
Function get Right -> $Right : Integer
Function set Right($Right : Integer)
```

**Setter Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$Right` | `Integer` | - |

**Returns:** `Integer`

---

#### Title {#title}
 `[🔍 get, ✏️ set]`

```4d
Function get Title -> Text
Function set Title($Title : Text)
```

**Setter Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$Title` | `Text` | - |

**Returns:** `Text`

---

#### Top {#top}
 `[🔍 get, ✏️ set]`

```4d
Function get Top -> $Top : Integer
Function set Top($Top : Integer)
```

**Setter Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$Top` | `Integer` | - |

**Returns:** `Integer`

---

#### Underline {#underline}
 `[🔍 get, ✏️ set]`

```4d
Function get Underline -> Boolean
Function set Underline($Underline : Boolean)
```

**Setter Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$Underline` | `Boolean` | - |

**Returns:** `Boolean`

---

#### VerticalScrollPosition {#verticalscrollposition}
 `[🔍 get, ✏️ set]`

```4d
Function get VerticalScrollPosition -> $VerticalScrollPosition : Integer
Function set VerticalScrollPosition($VerticalScrollPosition : Integer)
```

**Setter Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$VerticalScrollPosition` | `Integer` | - |

**Returns:** `Integer`

---

#### Visible {#visible}
 `[🔍 get, ✏️ set]`

```4d
Function get Visible -> Boolean
Function set Visible($Visible : Boolean)
```

**Setter Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$Visible` | `Boolean` | - |

**Returns:** `Boolean`

---

#### Width {#width}
 `[🔍 get, ✏️ set]`

```4d
Function get Width -> Integer
Function set Width($Width : Integer)
```

**Setter Parameter:**

| Name | Type | Description |
|:-----|:-----|:------------|
| `$Width` | `Integer` | - |

**Returns:** `Integer`

---

---

*Generated from FormObject.4dm*
