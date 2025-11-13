---
layout : default
title : NominalCodes
parent : Tables
---
# NominalCodes

📊 **Overview:** 6 Fields | 3 Indexes | 1 One-to-Many Relations

## ℹ️ Table Information

- **Table ID:** 84
- **UUID:** B4B021F72621A44A861BDFF8762EE00C
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:36:20Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (6)
- [🔍 Indexes](#-indexes) (3)
- [🔗 One-to-Many Relations](#-one-to-many-relations) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| NominalCode | `Date` | ✨ Unique | - |
| Description | `String` (255) | 🚫 Not Null | - |
| Code_4D | `String` (255) | 🚫 Not Null | - |
| Category | `String` (255) | 🚫 Not Null | - |
| FinishedGoodsTransport | `Real` | 🚫 Not Null | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### NominalCode

**Properties:**

- **Type:** Date
- **Constraints:** ✨ Unique

---

#### Description

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Code_4D

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Category

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### FinishedGoodsTransport

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `FinishedGoodsTransport` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `NominalCode` | B-Tree | regular | ✨ Yes |

### Detailed Information

- **Field:** `FinishedGoodsTransport`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `NominalCode` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** B-Tree

## 🔗 One-to-Many Relations

### Quick Reference

| Relation Name | Source Table | Source → Destination | State |
|:--------------|:-------------|:---------------------|:------|
| `PurchaseInfoSelection` | [PurchaseInfo](PurchaseInfo.md) | `NominalCode` → `ID` | Active |

### Detailed Information

#### PurchaseInfoSelection

**Links from:** [PurchaseInfo](PurchaseInfo.md)

- **Source Table:** `PurchaseInfo`
- **Source Field:** `NominalCode`
- **This Table Field:** `ID`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:20Z*
