# FormObject

## Table of Contents

### Properties

- [Name](#name)

### Functions

- [Title() [getter]](#title)
- [Title() [setter]](#title)
- [MinimumValue() [getter]](#minimumvalue)
- [MinimumValue() [setter]](#minimumvalue)
- [MaximumValue() [getter]](#maximumvalue)
- [MaximumValue() [setter]](#maximumvalue)
- [Visible() [getter]](#visible)
- [Visible() [setter]](#visible)
- [Enterable() [getter]](#enterable)
- [Enterable() [setter]](#enterable)
- [Enabled() [getter]](#enabled)
- [Enabled() [setter]](#enabled)
- [ForegroundColor() [getter]](#foregroundcolor)
- [ForegroundColor() [setter]](#foregroundcolor)
- [BackgroundColor() [getter]](#backgroundcolor)
- [BackgroundColor() [setter]](#backgroundcolor)
- [Left() [getter]](#left)
- [Left() [setter]](#left)
- [Top() [getter]](#top)
- [Top() [setter]](#top)
- [Right() [getter]](#right)
- [Right() [setter]](#right)
- [Bottom() [getter]](#bottom)
- [Bottom() [setter]](#bottom)
- [Width() [getter]](#width)
- [Width() [setter]](#width)
- [Height() [getter]](#height)
- [Height() [setter]](#height)
- [setMaxFontSize()](#setmaxfontsize)
- [setBestObjectSize()](#setbestobjectsize)
- [Font() [getter]](#font)
- [Font() [setter]](#font)
- [FontSize() [getter]](#fontsize)
- [FontSize() [setter]](#fontsize)
- [Bold() [getter]](#bold)
- [Bold() [setter]](#bold)
- [Italic() [getter]](#italic)
- [Italic() [setter]](#italic)
- [Underline() [getter]](#underline)
- [Underline() [setter]](#underline)
- [DisplayFormat() [getter]](#displayformat)
- [DisplayFormat() [setter]](#displayformat)
- [Multiline() [getter]](#multiline)
- [Multiline() [setter]](#multiline)
- [PlaceholderText() [getter]](#placeholdertext)
- [PlaceholderText() [setter]](#placeholdertext)
- [VerticalScrollPosition() [getter]](#verticalscrollposition)
- [VerticalScrollPosition() [setter]](#verticalscrollposition)
- [HorizontalScrollPosition() [getter]](#horizontalscrollposition)
- [HorizontalScrollPosition() [setter]](#horizontalscrollposition)
- [CornerRadius() [getter]](#cornerradius)
- [CornerRadius() [setter]](#cornerradius)
- [HelpTip() [getter]](#helptip)
- [HelpTip() [setter]](#helptip)
- [Pointer() [getter]](#pointer)
- [HasFocus() [getter]](#hasfocus)
- [Focus()](#focus)
- [HighlightText()](#highlighttext)

---

## Properties

### Name {#name}

**Type:** `Text`

---

## Functions

### Title {#title}
 `[getter]`

```4d
Function Title -> Text
```

**Returns:** `Text`

---

### Title {#title}
 `[setter]`

```4d
Function Title($Title : Text)
```

---

### MinimumValue {#minimumvalue}
 `[getter]`

```4d
Function MinimumValue -> Variant
```

**Returns:** `Variant`

---

### MinimumValue {#minimumvalue}
 `[setter]`

```4d
Function MinimumValue($MinimumValue : Variant)
```

---

### MaximumValue {#maximumvalue}
 `[getter]`

```4d
Function MaximumValue -> Variant
```

**Returns:** `Variant`

---

### MaximumValue {#maximumvalue}
 `[setter]`

```4d
Function MaximumValue($MaximumValue : Variant)
```

---

### Visible {#visible}
 `[getter]`

```4d
Function Visible -> Boolean
```

**Returns:** `Boolean`

---

### Visible {#visible}
 `[setter]`

```4d
Function Visible($Visible : Boolean)
```

---

### Enterable {#enterable}
 `[getter]`

```4d
Function Enterable -> Boolean
```

**Returns:** `Boolean`

---

### Enterable {#enterable}
 `[setter]`

```4d
Function Enterable($Enterable : Boolean)
```

---

### Enabled {#enabled}
 `[getter]`

```4d
Function Enabled -> Boolean
```

**Returns:** `Boolean`

---

### Enabled {#enabled}
 `[setter]`

```4d
Function Enabled($Enabled : Boolean)
```

---

### ForegroundColor {#foregroundcolor}
 `[getter]`

```4d
Function ForegroundColor -> Integer
```

**Returns:** `Integer`

---

### ForegroundColor {#foregroundcolor}
 `[setter]`

```4d
Function ForegroundColor($ForegroundColor : Variant)
```

---

### BackgroundColor {#backgroundcolor}
 `[getter]`

```4d
Function BackgroundColor -> Integer
```

**Returns:** `Integer`

---

### BackgroundColor {#backgroundcolor}
 `[setter]`

```4d
Function BackgroundColor($BackgroundColor : Variant)
```

---

### Left {#left}
 `[getter]`

```4d
Function Left -> Integer
```

**Returns:** `Integer`

---

### Left {#left}
 `[setter]`

```4d
Function Left($Left : Integer)
```

---

### Top {#top}
 `[getter]`

```4d
Function Top -> Integer
```

**Returns:** `Integer`

---

### Top {#top}
 `[setter]`

```4d
Function Top($Top : Integer)
```

---

### Right {#right}
 `[getter]`

```4d
Function Right -> Integer
```

**Returns:** `Integer`

---

### Right {#right}
 `[setter]`

```4d
Function Right($Right : Integer)
```

---

### Bottom {#bottom}
 `[getter]`

```4d
Function Bottom -> Integer
```

**Returns:** `Integer`

---

### Bottom {#bottom}
 `[setter]`

```4d
Function Bottom($Bottom : Integer)
```

---

### Width {#width}
 `[getter]`

```4d
Function Width -> Integer
```

**Returns:** `Integer`

---

### Width {#width}
 `[setter]`

```4d
Function Width($Width : Integer)
```

---

### Height {#height}
 `[getter]`

```4d
Function Height -> Integer
```

**Returns:** `Integer`

---

### Height {#height}
 `[setter]`

```4d
Function Height($Height : Integer)
```

---

### setMaxFontSize {#setmaxfontsize}


```4d
Function setMaxFontSize($MultiLine : Boolean; $UpperFontSizeLimit : Integer)
```

---

### setBestObjectSize {#setbestobjectsize}


```4d
Function setBestObjectSize($HeightOnly : Boolean)
```

---

### Font {#font}
 `[getter]`

```4d
Function Font -> Text
```

**Returns:** `Text`

---

### Font {#font}
 `[setter]`

```4d
Function Font($Font : Text)
```

---

### FontSize {#fontsize}
 `[getter]`

```4d
Function FontSize -> Integer
```

**Returns:** `Integer`

---

### FontSize {#fontsize}
 `[setter]`

```4d
Function FontSize($FontSize : Integer)
```

---

### Bold {#bold}
 `[getter]`

```4d
Function Bold -> Boolean
```

**Returns:** `Boolean`

---

### Bold {#bold}
 `[setter]`

```4d
Function Bold($Bold : Boolean)
```

---

### Italic {#italic}
 `[getter]`

```4d
Function Italic -> Boolean
```

**Returns:** `Boolean`

---

### Italic {#italic}
 `[setter]`

```4d
Function Italic($Italic : Boolean)
```

---

### Underline {#underline}
 `[getter]`

```4d
Function Underline -> Boolean
```

**Returns:** `Boolean`

---

### Underline {#underline}
 `[setter]`

```4d
Function Underline($Underline : Boolean)
```

---

### DisplayFormat {#displayformat}
 `[getter]`

```4d
Function DisplayFormat -> Text
```

**Returns:** `Text`

---

### DisplayFormat {#displayformat}
 `[setter]`

```4d
Function DisplayFormat($DisplayFormat : Variant)
```

---

### Multiline {#multiline}
 `[getter]`

```4d
Function Multiline -> Boolean
```

**Returns:** `Boolean`

---

### Multiline {#multiline}
 `[setter]`

```4d
Function Multiline($Multiline : Boolean)
```

---

### PlaceholderText {#placeholdertext}
 `[getter]`

```4d
Function PlaceholderText -> Text
```

**Returns:** `Text`

---

### PlaceholderText {#placeholdertext}
 `[setter]`

```4d
Function PlaceholderText($PlaceholderText : Text)
```

---

### VerticalScrollPosition {#verticalscrollposition}
 `[getter]`

```4d
Function VerticalScrollPosition -> Integer
```

**Returns:** `Integer`

---

### VerticalScrollPosition {#verticalscrollposition}
 `[setter]`

```4d
Function VerticalScrollPosition($VerticalScrollPosition : Integer)
```

---

### HorizontalScrollPosition {#horizontalscrollposition}
 `[getter]`

```4d
Function HorizontalScrollPosition -> Integer
```

**Returns:** `Integer`

---

### HorizontalScrollPosition {#horizontalscrollposition}
 `[setter]`

```4d
Function HorizontalScrollPosition($HorizontalScrollPosition : Integer)
```

---

### CornerRadius {#cornerradius}
 `[getter]`

```4d
Function CornerRadius -> Integer
```

**Returns:** `Integer`

---

### CornerRadius {#cornerradius}
 `[setter]`

```4d
Function CornerRadius($CornerRadius : Integer)
```

---

### HelpTip {#helptip}
 `[getter]`

```4d
Function HelpTip -> Text
```

**Returns:** `Text`

---

### HelpTip {#helptip}
 `[setter]`

```4d
Function HelpTip($HelpTip : Text)
```

---

### Pointer {#pointer}
 `[getter]`

```4d
Function Pointer -> Pointer
```

**Returns:** `Pointer`

---

### HasFocus {#hasfocus}
 `[getter]`

```4d
Function HasFocus -> Boolean
```

**Returns:** `Boolean`

---

### Focus {#focus}


```4d
Function Focus
```

---

### HighlightText {#highlighttext}


```4d
Function HighlightText($StartPosition : Integer; $EndPosition : Integer)
```

---

---

*Generated from FormObject.4dm*
*Last updated: 2025-11-12T17:04:21.778Z*
