---
layout : default
title : SalesForecast
parent : Tables
---
# SalesForecast

📊 **Overview:** 22 Fields | 7 Indexes

## ℹ️ Table Information

- **Table ID:** 49
- **UUID:** 0412FF273154D14EA78AFDEC1CD85D3D
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:35:48Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (22)
- [🔍 Indexes](#-indexes) (7)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| ProductID | `Date` | 🚫 Not Null | - |
| fYear | `Picture` | 🚫 Not Null | - |
| January | `Undefined` | 🚫 Not Null | - |
| February | `Undefined` | 🚫 Not Null | - |
| March | `Undefined` | 🚫 Not Null | - |
| April | `Undefined` | 🚫 Not Null | - |
| May | `Undefined` | 🚫 Not Null | - |
| June | `Undefined` | 🚫 Not Null | - |
| July | `Undefined` | 🚫 Not Null | - |
| August | `Undefined` | 🚫 Not Null | - |
| September | `Undefined` | 🚫 Not Null | - |
| October | `Undefined` | 🚫 Not Null | - |
| November | `Undefined` | 🚫 Not Null | - |
| December | `Undefined` | 🚫 Not Null | - |
| Customer | `String` (255) | 🚫 Not Null | - |
| PartName | `String` (255) | 🚫 Not Null | - |
| LastEdited | `Integer` | 🚫 Not Null | - |
| YearlyVolume | `Undefined` | 🚫 Not Null | - |
| SnapShot | `Real` | 🚫 Not Null | - |
| SnapDate | `Integer` | 🚫 Not Null | - |
| CurrentBacklog | `Undefined` | 🚫 Not Null | - |
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |

### Detailed Information

#### ProductID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### fYear

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### January

**Properties:**

- **Type:** Undefined
- **Constraints:** 🚫 Never Null

---

#### February

**Properties:**

- **Type:** Undefined
- **Constraints:** 🚫 Never Null

---

#### March

**Properties:**

- **Type:** Undefined
- **Constraints:** 🚫 Never Null

---

#### April

**Properties:**

- **Type:** Undefined
- **Constraints:** 🚫 Never Null

---

#### May

**Properties:**

- **Type:** Undefined
- **Constraints:** 🚫 Never Null

---

#### June

**Properties:**

- **Type:** Undefined
- **Constraints:** 🚫 Never Null

---

#### July

**Properties:**

- **Type:** Undefined
- **Constraints:** 🚫 Never Null

---

#### August

**Properties:**

- **Type:** Undefined
- **Constraints:** 🚫 Never Null

---

#### September

**Properties:**

- **Type:** Undefined
- **Constraints:** 🚫 Never Null

---

#### October

**Properties:**

- **Type:** Undefined
- **Constraints:** 🚫 Never Null

---

#### November

**Properties:**

- **Type:** Undefined
- **Constraints:** 🚫 Never Null

---

#### December

**Properties:**

- **Type:** Undefined
- **Constraints:** 🚫 Never Null

---

#### Customer

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### PartName

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### LastEdited

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### YearlyVolume

**Properties:**

- **Type:** Undefined
- **Constraints:** 🚫 Never Null

---

#### SnapShot

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### SnapDate

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### CurrentBacklog

**Properties:**

- **Type:** Undefined
- **Constraints:** 🚫 Never Null

---

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence, 🚫 Never Null

---

## 🔍 Indexes

### Quick Reference

| Field | Type | Kind | Unique |
|:------|:-----|:-----|:-------|
| `fYear` | Cluster | regular | - |
| `ProductID` | Cluster | regular | - |
| `SnapDate` | Cluster | regular | - |
| `Customer` | Cluster | regular | - |
| `PartName` | Cluster | regular | - |
| `SnapShot` | Cluster | regular | - |
| `ID` | B-Tree | regular | ✨ Yes |

### Detailed Information

- **Field:** `fYear`
  - **Kind:** regular
  - **Type:** Cluster
- **Field:** `ProductID`
  - **Kind:** regular
  - **Type:** Cluster
- **Field:** `SnapDate`
  - **Kind:** regular
  - **Type:** Cluster
- **Field:** `Customer`
  - **Kind:** regular
  - **Type:** Cluster
- **Field:** `PartName`
  - **Kind:** regular
  - **Type:** Cluster
- **Field:** `SnapShot`
  - **Kind:** regular
  - **Type:** Cluster
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** B-Tree

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:48Z*
