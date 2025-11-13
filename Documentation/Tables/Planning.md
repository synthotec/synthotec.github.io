---
layout : default
title : Planning
parent : Tables
---
# Planning

📊 **Overview:** 13 Fields | 4 Indexes

## ℹ️ Table Information

- **Table ID:** 69
- **UUID:** 85B429DD73F4624CB829A1662373A124
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:36:06Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (13)
- [🔍 Indexes](#-indexes) (4)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Product_ID | `Date` | 🚫 Not Null | - |
| Hours | `Boolean` | 🚫 Not Null | - |
| fQTY | `Date` | 🚫 Not Null | - |
| tRoute | `Picture` | 🚫 Not Null | - |
| tImps | `Boolean` | 🚫 Not Null | - |
| tCycle | `Boolean` | 🚫 Not Null | - |
| Comments | `String` (255) | 🚫 Not Null | - |
| Pallet | `String` (255) | 🚫 Not Null | - |
| Mandrel | `String` (255) | 🚫 Not Null | - |
| Profile | `String` (255) | 🚫 Not Null | - |
| SnapDate | `Integer` | 🚫 Not Null | - |
| ShotWeight | `Boolean` | 🚫 Not Null | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### Product_ID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Hours

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### fQTY

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### tRoute

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### tImps

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### tCycle

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Comments

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Pallet

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Mandrel

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Profile

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### SnapDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### ShotWeight

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `SnapDate` | Cluster | regular | - |
| `Profile` | Cluster | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `tRoute` | Cluster | regular | - |

### Detailed Information

- **Field:** `SnapDate`
  - **Kind:** regular
  - **Type:** Cluster
- **Field:** `Profile`
  - **Kind:** regular
  - **Type:** Cluster
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `tRoute`
  - **Kind:** regular
  - **Type:** Cluster

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:06Z*
