# PrintSettings

## Table of Contents

### Properties

- [Name](#name)
- [Paper](#paper)
- [Orientation](#orientation)
- [Copies](#copies)
- [CurrentPrinter](#currentprinter)

### Functions

- [display()](#display)
- [load()](#load)
- [save()](#save)
- [apply()](#apply)
- [restore()](#restore)

---

## Properties

### Name {#name}

**Type:** `Text`

---

### Paper {#paper}

**Type:** `Text`

---

### Orientation {#orientation}

**Type:** `Integer`

---

### Copies {#copies}

**Type:** `Integer`

---

### CurrentPrinter {#currentprinter}

**Type:** `Text`

---

## Functions

### display {#display}


```4d
Function display -> Boolean
```

**Returns:** `Boolean`

---

### load {#load}


```4d
Function load($SettingName : Text; $LoadCopyCount : Boolean) -> cs.PrintSettings
```

**Returns:** `cs.PrintSettings`

---

### save {#save}


```4d
Function save($SettingName : Text) -> cs.PrintSettings
```

**Returns:** `cs.PrintSettings`

---

### apply {#apply}


```4d
Function apply -> Boolean
```

**Returns:** `Boolean`

---

### restore {#restore}


```4d
Function restore -> Boolean
```

**Returns:** `Boolean`

---

---

*Generated from PrintSettings.4dm*
*Last updated: 2025-11-12T17:04:22.160Z*
