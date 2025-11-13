---
layout : default
title : EntityMigration
parent : Classes
---
# EntityMigration

📊 **Overview:** 6 Properties | 1 Constructor | 10 Functions | 7 Getters

## 📝 Description

🗨️ Initialize migration manager for a specific dataclass with optional remote selection for linking

🕐 *Last updated: 2025-11-13T00:47:52.460Z*

---

## 📑 Table of Contents

### 📋 Properties (6)

- [_RemoteDataStore](#remotedatastore) : `4D.DataStoreImplementation`
- [_DataClass](#dataclass) : `4D.DataClass`
- [LinkFunctionCancelled](#linkfunctioncancelled)
- [RemoteDataClass](#remotedataclass) : `4D.DataClass`
- [LinkRemoteSelection](#linkremoteselection) : `4D.EntitySelection`
- [Loading](#loading) : `cs.Loading`

### ⚙️ Functions

**🏗️ Constructors (1):**

- [constructor](#constructor) (2 params)

**⚙️ Functions (10):**

- [sync](#sync) (2 params) → `4D.Entity`
- [_functionsExistChecks](#_functionsexistchecks)
- [create](#create) (2 params) → `4D.Entity`
- [link](#link) (2 params) → `4D.Entity`
- [get](#get) (3 params) → `4D.Entity`
- [LinkDisplayPropertyValue](#linkdisplaypropertyvalue) (1 param) → `Variant`
- [updateLoading](#updateloading) (2 params)
- [startTransactions](#starttransactions)
- [validateTransactions](#validatetransactions)
- [cancelTransactions](#canceltransactions)

**🔍 Getters (7):**

- [NewEntityPropertyFormulas](#newentitypropertyformulas) → `Collection`
- [LinkDisplayProperty](#linkdisplayproperty) → `Text`
- [LinkAdditionalInfoProperty](#linkadditionalinfoproperty) → `Text`
- [LinkingEnabled](#linkingenabled) → `Boolean`
- [_MigrationSettings](#_migrationsettings) → `Object`
- [DataClassName](#dataclassname) → `Text`
- [MigrationPropertyExists](#migrationpropertyexists) → `Boolean`

---

## 📋 Properties

### Quick Reference

| Property | Type | Default | Description |
|:---------|:-----|:--------|:------------|
| `_RemoteDataStore` | `4D.DataStoreImplementation` | `DataStore(2)` | Remote datastore connection for migration target |
| `_DataClass` | `4D.DataClass` | - | Local dataclass being migrated |
| `LinkFunctionCancelled` | *Not specified* | `False` | Flag indicating user cancelled the link dialog |
| `RemoteDataClass` | `4D.DataClass` | - | Remote dataclass corresponding to local dataclass |
| `LinkRemoteSelection` | `4D.EntitySelection` | - | Remote entities available for linking |
| `Loading` | `cs.Loading` | - | Loading indicator for migration progress |

### Detailed Information

#### _RemoteDataStore {#remotedatastore}

**Type:** `4D.DataStoreImplementation`

**Default Value:** `DataStore(2)`

Remote datastore connection for migration target

---

#### _DataClass {#dataclass}

**Type:** `4D.DataClass`

Local dataclass being migrated

---

#### LinkFunctionCancelled {#linkfunctioncancelled}

**Type:** *Not specified*

**Default Value:** `False`

Flag indicating user cancelled the link dialog

---

#### RemoteDataClass {#remotedataclass}

**Type:** `4D.DataClass`

Remote dataclass corresponding to local dataclass

---

#### LinkRemoteSelection {#linkremoteselection}

**Type:** `4D.EntitySelection`

Remote entities available for linking

---

#### Loading {#loading}

**Type:** `cs.Loading`

Loading indicator for migration progress

---

## ⚙️ Functions

### 🏗️ Constructors

### ⚙️ Regular Functions

### 🔍 Getters

---

*Generated from EntityMigration.4dm*
