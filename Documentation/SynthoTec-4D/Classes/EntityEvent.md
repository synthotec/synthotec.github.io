---
layout : default
title : EntityEvent
parent : Classes
---
# EntityEvent [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/EntityEvent.4dm)

📊 **Overview:** 7 Properties | 1 Constructor

## 📝 Description

Wraps a raw 4D entity event object (from save/drop triggers) into a typed class, normalising status strings to Boolean flags and providing named access to event kind, attribute name, dataclass name, and affected attribute lists.

🕐 *Last updated: 2026-03-09T14:45:29.461Z*

---

## 📑 Table of Contents

- [📋 Properties (7)](#properties)
- [🏗️ Constructor](#constructor) (1 param)

---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `kind` | `Text` | - | Event type (e.g., "save", "drop") |
| `attributeName` | `Text` | - | Name of the affected attribute |
| `dataClassName` | `Text` | - | Name of the DataClass that triggered the event |
| `savedAttributes` | `Collection` | - | Collection of attribute names that were saved |
| `droppedAttributes` | `Collection` | - | Collection of attribute names that were dropped |
| `saveStatus` | `Boolean` | - | True if the save operation was successful |
| `dropStatus` | `Boolean` | - | True if the drop operation was successful |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor($EventObjectPointer : Pointer)
```

Wraps the raw 4D entity event object, extracting fields and normalizing status flags to Boolean

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$EventObjectPointer` | `Pointer` | - | - |

---

---

*Generated from EntityEvent.4dm*
