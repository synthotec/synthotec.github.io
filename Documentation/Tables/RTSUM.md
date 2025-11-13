---
layout : default
title : RTSUM
parent : Tables
---
# RTSUM

📊 **Overview:** 10 Fields | 4 Indexes | 1 Many-to-One Relations

## ℹ️ Table Information

- **Table ID:** 67
- **UUID:** B4BCF8D18A05AB4AB5784486D50CD234
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:36:04Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (10)
- [🔍 Indexes](#-indexes) (4)
- [🔗 Many-to-One Relations](#-many-to-one-relations) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| dDate | `Integer` | 🚫 Not Null | - |
| WorksOrder | `Date` | 🚫 Not Null | - |
| Stoppage | `Real` | 🚫 Not Null | - |
| DownCode | `Date` | 🚫 Not Null | - |
| Impressions | `Date` | 🚫 Not Null | - |
| Seconds | `Boolean` | 🚫 Not Null | - |
| Instances | `Picture` | 🚫 Not Null | - |
| Target | `Boolean` | 🚫 Not Null | - |
| TC | `Real` | 🚫 Not Null | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### dDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### WorksOrder

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Stoppage

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### DownCode

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Impressions

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Seconds

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Instances

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Target

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### TC

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `dDate` | Cluster | regular | - |
| `Stoppage` | Cluster | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `WorksOrder` | Keywords | regular | - |

### Detailed Information

- **Field:** `dDate`
  - **Kind:** regular
  - **Type:** Cluster
- **Field:** `Stoppage`
  - **Kind:** regular
  - **Type:** Cluster
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `WorksOrder`
  - **Kind:** regular
  - **Type:** Keywords

## 🔗 Many-to-One Relations

### Quick Reference

| Relation Name | Destination Table | Source → Destination | State |
|:--------------|:------------------|:---------------------|:------|
| `WorksOrderEntity` | [WorksOrder](WorksOrder.md) | `WorksOrder` → `Works_Order_No` | Active |

### Detailed Information

#### WorksOrderEntity

**Links to:** [WorksOrder](WorksOrder.md)

- **Source Field:** `WorksOrder`
- **Destination Field:** `Works_Order_No`
- **State:** Active

---

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:36:04Z*
