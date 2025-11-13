---
layout : default
title : FormObject
parent : Classes
---
# FormObject

📊 **Overview:** 1 Properties | 1 Constructor | 4 Functions | 28 Getters | 26 Setters

🕐 *Last updated: 2025-11-13T14:26:50.057Z*

---

## 📑 Table of Contents

- [📋 Properties (1)](#-properties)

### ⚙️ Functions

**🏗️ Constructors (1):**

- [constructor](#constructor) (1 param)

**⚙️ Regular Functions (4):**

- [setMaxFontSize](#setmaxfontsize) (2 params)
- [setBestObjectSize](#setbestobjectsize) (1 param)
- [Focus](#focus)
- [HighlightText](#highlighttext) (2 params)

**🔍 Getters (28):**

- [Title](#title) → `Text`
- [MinimumValue](#minimumvalue) → `Variant`
- [MaximumValue](#maximumvalue) → `Variant`
- [Visible](#visible) → `Boolean`
- [Enterable](#enterable) → `Boolean`
- [Enabled](#enabled) → `Boolean`
- [ForegroundColor](#foregroundcolor) → `Integer`
- [BackgroundColor](#backgroundcolor) → `Integer`
- [Left](#left) → `Integer`
- [Top](#top) → `Integer`
- [Right](#right) → `Integer`
- [Bottom](#bottom) → `Integer`
- [Width](#width) → `Integer`
- [Height](#height) → `Integer`
- [Font](#font) → `Text`
- [FontSize](#fontsize) → `Integer`
- [Bold](#bold) → `Boolean`
- [Italic](#italic) → `Boolean`
- [Underline](#underline) → `Boolean`
- [DisplayFormat](#displayformat) → `Text`
- [Multiline](#multiline) → `Boolean`
- [PlaceholderText](#placeholdertext) → `Text`
- [VerticalScrollPosition](#verticalscrollposition) → `Integer`
- [HorizontalScrollPosition](#horizontalscrollposition) → `Integer`
- [CornerRadius](#cornerradius) → `Integer`
- [HelpTip](#helptip) → `Text`
- [Pointer](#pointer) → `Pointer`
- [HasFocus](#hasfocus) → `Boolean`

**✏️ Setters (26):**

- [Title](#title) (1 param)
- [MinimumValue](#minimumvalue) (1 param)
- [MaximumValue](#maximumvalue) (1 param)
- [Visible](#visible) (1 param)
- [Enterable](#enterable) (1 param)
- [Enabled](#enabled) (1 param)
- [ForegroundColor](#foregroundcolor) (1 param)
- [BackgroundColor](#backgroundcolor) (1 param)
- [Left](#left) (1 param)
- [Top](#top) (1 param)
- [Right](#right) (1 param)
- [Bottom](#bottom) (1 param)
- [Width](#width) (1 param)
- [Height](#height) (1 param)
- [Font](#font) (1 param)
- [FontSize](#fontsize) (1 param)
- [Bold](#bold) (1 param)
- [Italic](#italic) (1 param)
- [Underline](#underline) (1 param)
- [DisplayFormat](#displayformat) (1 param)
- [Multiline](#multiline) (1 param)
- [PlaceholderText](#placeholdertext) (1 param)
- [VerticalScrollPosition](#verticalscrollposition) (1 param)
- [HorizontalScrollPosition](#horizontalscrollposition) (1 param)
- [CornerRadius](#cornerradius) (1 param)
- [HelpTip](#helptip) (1 param)

---

## 📋 Properties

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `Name` | `Text` | - | - |

## ⚙️ Functions

### 🏗️ Constructors

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

### ⚙️ Regular Functions

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

### 🔍 Getters

#### Title {#title}
 `[🔍 getter]`

```4d
Function Title -> Text
```

**Returns:** `Text`

---

#### MinimumValue {#minimumvalue}
 `[🔍 getter]`

```4d
Function MinimumValue -> $MinimumValue : Variant
```

**Returns:** `Variant`

---

#### MaximumValue {#maximumvalue}
 `[🔍 getter]`

```4d
Function MaximumValue -> $MaximumValue : Variant
```

**Returns:** `Variant`

---

#### Visible {#visible}
 `[🔍 getter]`

```4d
Function Visible -> Boolean
```

**Returns:** `Boolean`

---

#### Enterable {#enterable}
 `[🔍 getter]`

```4d
Function Enterable -> Boolean
```

**Returns:** `Boolean`

---

#### Enabled {#enabled}
 `[🔍 getter]`

```4d
Function Enabled -> Boolean
```

**Returns:** `Boolean`

---

#### ForegroundColor {#foregroundcolor}
 `[🔍 getter]`

```4d
Function ForegroundColor -> $ForegroundColor : Integer
```

**Returns:** `Integer`

---

#### BackgroundColor {#backgroundcolor}
 `[🔍 getter]`

```4d
Function BackgroundColor -> $BackgroundColor : Integer
```

**Returns:** `Integer`

---

#### Left {#left}
 `[🔍 getter]`

```4d
Function Left -> $Left : Integer
```

**Returns:** `Integer`

---

#### Top {#top}
 `[🔍 getter]`

```4d
Function Top -> $Top : Integer
```

**Returns:** `Integer`

---

#### Right {#right}
 `[🔍 getter]`

```4d
Function Right -> $Right : Integer
```

**Returns:** `Integer`

---

#### Bottom {#bottom}
 `[🔍 getter]`

```4d
Function Bottom -> $Bottom : Integer
```

**Returns:** `Integer`

---

#### Width {#width}
 `[🔍 getter]`

```4d
Function Width -> Integer
```

**Returns:** `Integer`

---

#### Height {#height}
 `[🔍 getter]`

```4d
Function Height -> Integer
```

**Returns:** `Integer`

---

#### Font {#font}
 `[🔍 getter]`

```4d
Function Font -> Text
```

**Returns:** `Text`

---

#### FontSize {#fontsize}
 `[🔍 getter]`

```4d
Function FontSize -> Integer
```

**Returns:** `Integer`

---

#### Bold {#bold}
 `[🔍 getter]`

```4d
Function Bold -> Boolean
```

**Returns:** `Boolean`

---

#### Italic {#italic}
 `[🔍 getter]`

```4d
Function Italic -> Boolean
```

**Returns:** `Boolean`

---

#### Underline {#underline}
 `[🔍 getter]`

```4d
Function Underline -> Boolean
```

**Returns:** `Boolean`

---

#### DisplayFormat {#displayformat}
 `[🔍 getter]`

```4d
Function DisplayFormat -> Text
```

**Returns:** `Text`

---

#### Multiline {#multiline}
 `[🔍 getter]`

```4d
Function Multiline -> Boolean
```

**Returns:** `Boolean`

---

#### PlaceholderText {#placeholdertext}
 `[🔍 getter]`

```4d
Function PlaceholderText -> Text
```

**Returns:** `Text`

---

#### VerticalScrollPosition {#verticalscrollposition}
 `[🔍 getter]`

```4d
Function VerticalScrollPosition -> $VerticalScrollPosition : Integer
```

**Returns:** `Integer`

---

#### HorizontalScrollPosition {#horizontalscrollposition}
 `[🔍 getter]`

```4d
Function HorizontalScrollPosition -> $HorizontalScrollPosition : Integer
```

**Returns:** `Integer`

---

#### CornerRadius {#cornerradius}
 `[🔍 getter]`

```4d
Function CornerRadius -> Integer
```

**Returns:** `Integer`

---

#### HelpTip {#helptip}
 `[🔍 getter]`

```4d
Function HelpTip -> Text
```

**Returns:** `Text`

---

#### Pointer {#pointer}
 `[🔍 getter]`

```4d
Function Pointer -> Pointer
```

**Returns:** `Pointer`

---

#### HasFocus {#hasfocus}
 `[🔍 getter]`

```4d
Function HasFocus -> Boolean
```

**Returns:** `Boolean`

---

### ✏️ Setters

#### Title {#title}
 `[✏️ setter]`

```4d
Function Title($Title : Text)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Title` | `Text` | - | - |

---

#### MinimumValue {#minimumvalue}
 `[✏️ setter]`

```4d
Function MinimumValue($MinimumValue : Variant)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$MinimumValue` | `Variant` | - | - |

---

#### MaximumValue {#maximumvalue}
 `[✏️ setter]`

```4d
Function MaximumValue($MaximumValue : Variant)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$MaximumValue` | `Variant` | - | - |

---

#### Visible {#visible}
 `[✏️ setter]`

```4d
Function Visible($Visible : Boolean)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Visible` | `Boolean` | - | - |

---

#### Enterable {#enterable}
 `[✏️ setter]`

```4d
Function Enterable($Enterable : Boolean)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Enterable` | `Boolean` | - | - |

---

#### Enabled {#enabled}
 `[✏️ setter]`

```4d
Function Enabled($Enabled : Boolean)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Enabled` | `Boolean` | - | - |

---

#### ForegroundColor {#foregroundcolor}
 `[✏️ setter]`

```4d
Function ForegroundColor($ForegroundColor : Variant)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$ForegroundColor` | `Variant` | - | - |

---

#### BackgroundColor {#backgroundcolor}
 `[✏️ setter]`

```4d
Function BackgroundColor($BackgroundColor : Variant)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$BackgroundColor` | `Variant` | - | - |

---

#### Left {#left}
 `[✏️ setter]`

```4d
Function Left($Left : Integer)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Left` | `Integer` | - | - |

---

#### Top {#top}
 `[✏️ setter]`

```4d
Function Top($Top : Integer)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Top` | `Integer` | - | - |

---

#### Right {#right}
 `[✏️ setter]`

```4d
Function Right($Right : Integer)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Right` | `Integer` | - | - |

---

#### Bottom {#bottom}
 `[✏️ setter]`

```4d
Function Bottom($Bottom : Integer)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Bottom` | `Integer` | - | - |

---

#### Width {#width}
 `[✏️ setter]`

```4d
Function Width($Width : Integer)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Width` | `Integer` | - | - |

---

#### Height {#height}
 `[✏️ setter]`

```4d
Function Height($Height : Integer)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Height` | `Integer` | - | - |

---

#### Font {#font}
 `[✏️ setter]`

```4d
Function Font($Font : Text)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Font` | `Text` | - | - |

---

#### FontSize {#fontsize}
 `[✏️ setter]`

```4d
Function FontSize($FontSize : Integer)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$FontSize` | `Integer` | - | - |

---

#### Bold {#bold}
 `[✏️ setter]`

```4d
Function Bold($Bold : Boolean)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Bold` | `Boolean` | - | - |

---

#### Italic {#italic}
 `[✏️ setter]`

```4d
Function Italic($Italic : Boolean)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Italic` | `Boolean` | - | - |

---

#### Underline {#underline}
 `[✏️ setter]`

```4d
Function Underline($Underline : Boolean)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Underline` | `Boolean` | - | - |

---

#### DisplayFormat {#displayformat}
 `[✏️ setter]`

```4d
Function DisplayFormat($DisplayFormat : Variant)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$DisplayFormat` | `Variant` | - | - |

---

#### Multiline {#multiline}
 `[✏️ setter]`

```4d
Function Multiline($Multiline : Boolean)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$Multiline` | `Boolean` | - | - |

---

#### PlaceholderText {#placeholdertext}
 `[✏️ setter]`

```4d
Function PlaceholderText($PlaceholderText : Text)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$PlaceholderText` | `Text` | - | - |

---

#### VerticalScrollPosition {#verticalscrollposition}
 `[✏️ setter]`

```4d
Function VerticalScrollPosition($VerticalScrollPosition : Integer)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$VerticalScrollPosition` | `Integer` | - | - |

---

#### HorizontalScrollPosition {#horizontalscrollposition}
 `[✏️ setter]`

```4d
Function HorizontalScrollPosition($HorizontalScrollPosition : Integer)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$HorizontalScrollPosition` | `Integer` | - | - |

---

#### CornerRadius {#cornerradius}
 `[✏️ setter]`

```4d
Function CornerRadius($CornerRadius : Integer)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$CornerRadius` | `Integer` | - | - |

---

#### HelpTip {#helptip}
 `[✏️ setter]`

```4d
Function HelpTip($HelpTip : Text)
```

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$HelpTip` | `Text` | - | - |

---

---

*Generated from FormObject.4dm*
