---
layout : default
title : SupplierDocumentation
parent : Tables
---
# SupplierDocumentation

📊 **Overview:** 9 Fields | 3 Indexes | 1 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 85
- **UUID:** 39E8E2BA6606BA4E97B23381CEBA900D
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:36:21Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (9)
- [🔍 Indexes](#-indexes) (3)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| SupplierID | `Date` | 🚫 Not Null | - |
| DocumentType | `String` (255) | 🚫 Not Null | - |
| DocumentReference | `String` (255) | 🚫 Not Null | - |
| File | `Unknown (18)` | 🚫 Not Null | - |
| DateAdded | `Integer` | 🚫 Not Null | - |
| DateValidUntil | `Integer` | 🚫 Not Null | - |
| FileName | `String` (255) | 🚫 Not Null | - |
| Archived | `Real` | 🚫 Not Null | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### SupplierID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### DocumentType

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### DocumentReference

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### File

**Properties:**

- **Type:** Unknown (18)
- **Constraints:** 🚫 Never Null

---

#### DateAdded

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### DateValidUntil

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### FileName

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Archived

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `DateValidUntil` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `Archived` | Keywords | regular | - |

### Detailed Information

- **Field:** `DateValidUntil`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Archived`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `SuppliersEntity` | [Suppliers](Suppliers.md) | `SupplierID` → `SupplierID_l` | Active |

### Detailed Information

#### SuppliersEntity

**Links to:** [Suppliers](Suppliers.md)

- **Source Field:** `SupplierID`
- **Destination Field:** `SupplierID_l`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:21Z*
