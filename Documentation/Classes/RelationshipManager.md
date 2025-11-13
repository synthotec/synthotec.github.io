---
layout : default
title : RelationshipManager
parent : Classes
---
# RelationshipManager

📊 **Overview:** 1 Constructor | 11 Functions

## 📝 Description

🗨️ Manages relationships/links between Forms, Tables, and Classes for documentation

🕐 *Last updated: 2025-11-13T16:13:51.200Z*

---

## 📑 Table of Contents

### ⚙️ Functions

**🏗️ Constructors (1):**

- [constructor](#constructor)

**⚙️ Regular Functions (11):**

- [_loadRelationships](#_loadrelationships)
- [discoverRelationships](#discoverrelationships) → `Integer`
- [_discoverFormTableLinks](#_discoverformtablelinks)
- [_discoverTableClassLinks](#_discovertableclasslinks)
- [_discoverClassClassLinks](#_discoverclassclasslinks)
- [addLink](#addlink) (5 params)
- [removeLink](#removelink) (4 params)
- [getRelationshipsFor](#getrelationshipsfor) (2 params) → `Object`
- [getReverseRelationshipsFor](#getreverserelationshipsfor) (2 params) → `Object`
- [save](#save)
- [toJSON](#tojson) → `Text`

---

## ⚙️ Functions

### 🏗️ Constructors

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor
```

Manages relationships/links between Forms, Tables, and Classes for documentation

---

### ⚙️ Regular Functions

#### _loadRelationships {#_loadrelationships}


```4d
Function _loadRelationships
```

Load existing relationships from JSON file

---

#### discoverRelationships {#discoverrelationships}


```4d
Function discoverRelationships -> Integer
```

Auto-discover relationships from existing JSON files

**Returns:** `Integer`

---

#### _discoverFormTableLinks {#_discoverformtablelinks}


```4d
Function _discoverFormTableLinks
```

Discover Form → Table links from form JSON files

---

#### _discoverTableClassLinks {#_discovertableclasslinks}


```4d
Function _discoverTableClassLinks
```

Discover Table → Class links (DataClass, Entity, EntitySelection patterns)

---

#### _discoverClassClassLinks {#_discoverclassclasslinks}


```4d
Function _discoverClassClassLinks
```

Discover Class → Class links (extends relationships)

---

#### addLink {#addlink}


```4d
Function addLink($FromName : Text; $FromType : Text; $ToName : Text; $ToType : Text; $Note : Text)
```

Add a manual link between entities

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$FromName` | `Text` | - | - |
| `$FromType` | `Text` | - | - |
| `$ToName` | `Text` | - | - |
| `$ToType` | `Text` | - | - |
| `$Note` | `Text` | - | - |

---

#### removeLink {#removelink}


```4d
Function removeLink($FromName : Text; $FromType : Text; $ToName : Text; $ToType : Text)
```

Remove a link between entities

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$FromName` | `Text` | - | - |
| `$FromType` | `Text` | - | - |
| `$ToName` | `Text` | - | - |
| `$ToType` | `Text` | - | - |

---

#### getRelationshipsFor {#getrelationshipsfor}


```4d
Function getRelationshipsFor($EntityName : Text; $EntityType : Text) -> Object
```

Get relationships for a specific entity

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$EntityName` | `Text` | - | - |
| `$EntityType` | `Text` | - | - |

**Returns:** `Object`

---

#### getReverseRelationshipsFor {#getreverserelationshipsfor}


```4d
Function getReverseRelationshipsFor($EntityName : Text; $EntityType : Text) -> Object
```

Get reverse relationships (what links TO this entity)

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$EntityName` | `Text` | - | - |
| `$EntityType` | `Text` | - | - |

**Returns:** `Object`

---

#### save {#save}


```4d
Function save
```

Save relationships to JSON file

---

#### toJSON {#tojson}


```4d
Function toJSON -> Text
```

Convert to JSON string

**Returns:** `Text`

---

---

*Generated from RelationshipManager.4dm*
