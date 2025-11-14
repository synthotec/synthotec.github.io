---
layout : default
title : RelationshipManager
parent : Classes
---
# RelationshipManager [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/RelationshipManager.4dm)

📊 **Overview:** 3 Properties | 1 Constructor | 11 Functions

## 📝 Description

🗨️ Set up paths

🕐 *Last updated: 2025-11-14T16:35:59.340Z*

---

## 📑 Table of Contents

- [📋 Properties (3)](#properties)
- [🏗️ Constructor](#constructor)
- [⚙️ Functions](#functions)
  - [_loadRelationships](#_loadrelationships)
  - [discoverRelationships](#discoverrelationships) → `Integer`
  - [_discoverFormTableLinks](#_discoverformtablelinks)
  - [_discoverTableClassLinks](#_discovertableclasslinks)
  - [_discoverClassClassLinks](#_discoverclassclasslinks)
  - [addLink](#addlink) (6 params)
  - [removeLink](#removelink) (4 params)
  - [getRelationshipsFor](#getrelationshipsfor) (2 params) → `Collection`
  - [getReverseRelationshipsFor](#getreverserelationshipsfor) (2 params) → `Collection`
  - [save](#save)
  - [toJSON](#tojson) → `Text`
---

## Properties {#properties}

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `RelationshipsFile` | `Text` | - | - |
| `Relationships` | `Collection` | - | - |
| `Changes` | `Collection` | - | - |

## Constructor {#constructor}

#### constructor {#constructor}
 `[🏗️ constructor]`

```4d
Class constructor
```

---

## Functions {#functions}

### Regular Functions

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
Function addLink($FromName : Text; $FromType : Text; $ToName : Text; $ToType : Text; $FromDesc : Text; $ToDesc : Text)
```

Check if relationship already exists

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$FromName` | `Text` | - | - |
| `$FromType` | `Text` | - | - |
| `$ToName` | `Text` | - | - |
| `$ToType` | `Text` | - | - |
| `$FromDesc` | `Text` | - | - |
| `$ToDesc` | `Text` | - | - |

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
Function getRelationshipsFor($EntityName : Text; $EntityType : Text) -> Collection
```

Get relationships for a specific entity (where entity is FROM)

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$EntityName` | `Text` | - | - |
| `$EntityType` | `Text` | - | - |

**Returns:** `Collection`

---

#### getReverseRelationshipsFor {#getreverserelationshipsfor}


```4d
Function getReverseRelationshipsFor($EntityName : Text; $EntityType : Text) -> Collection
```

Get reverse relationships (where entity is TO)

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$EntityName` | `Text` | - | - |
| `$EntityType` | `Text` | - | - |

**Returns:** `Collection`

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
