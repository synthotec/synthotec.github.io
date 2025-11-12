# Translation

**Extends:** `DataClass`

## Table of Contents

### Functions

- [CurrentProcess() [getter]](#currentprocess)
- [_TranslationProcessCollection() [getter]](#_translationprocesscollection)
- [pushProcess()](#pushprocess)
- [popProcess()](#popprocess)
- [translate()](#translate)
- [translateFormObjects()](#translateformobjects)

---

## Functions

### CurrentProcess {#currentprocess}
 `[local]` `[getter]`

```4d
Function CurrentProcess -> Text
```

**Returns:** `Text`

---

### _TranslationProcessCollection {#_translationprocesscollection}
 `[local]` `[getter]`

```4d
Function _TranslationProcessCollection -> Collection
```

**Returns:** `Collection`

---

### pushProcess {#pushprocess}
 `[local]`

```4d
Function pushProcess($Process : Text)
```

---

### popProcess {#popprocess}
 `[local]`

```4d
Function popProcess
```

---

### translate {#translate}
 `[local]`

```4d
Function translate($Text : Text; $TranslationProcess : Text) -> Text
```

**Returns:** `Text`

---

### translateFormObjects {#translateformobjects}
 `[local]`

```4d
Function translateFormObjects($TranslationProcess : Text)
```

---

---

*Generated from Translation.4dm*
*Last updated: 2025-11-12T17:17:32.478Z*
