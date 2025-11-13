---
layout : default
title : PalletMethods
parent : Tables
---
# PalletMethods

📊 **Overview:** 4 Fields | 1 Indexes | 1 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 86
- **UUID:** CDB25505B7647A449BCF479500B14E95
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:36:21Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (4)
- [🔍 Indexes](#-indexes) (1)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Symbol | `String` (255) | 🚫 Not Null | - |
| BoxesPerPallet | `Picture` | 🚫 Not Null | - |
| Description | `String` (255) | 🚫 Not Null | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### Symbol

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### BoxesPerPallet

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Description

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `ID` | Keywords | regular | ✨ Yes |

### Detailed Information

- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `ProductSelection` | [Product](Product.md) | `PalletMethodID` → `ID` | Active |

### Detailed Information

#### ProductSelection

**Links from:** [Product](Product.md)

- **Source Table:** `Product`
- **Source Field:** `PalletMethodID`
- **This Table Field:** `ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:21Z*
