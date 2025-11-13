---
layout : default
title : (Route_Card_Data)
parent : Tables
---
# (Route_Card_Data)

📊 **Overview:** 18 Fields | 5 Indexes

## ℹ️ Table Information

- **Table ID:** 26
- **UUID:** AB1C481C69AFC94D924C5E73D8EC1283
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:35:17Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (18)
- [🔍 Indexes](#-indexes) (5)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| Product_ID | `Date` | ⚠️ Required, 🚫 Not Null | - |
| Works_Order | `Date` | ⚠️ Required, 🚫 Not Null | - |
| Chamber_No | `Picture` | ⚠️ Required, 🚫 Not Null | - |
| Box_Number | `Boolean` | 🚫 Not Null | - |
| Actual_Time | `Picture` | 🚫 Not Null | - |
| Wet_Date | `Integer` | 🚫 Not Null | - |
| TopUp_Weight | `Boolean` | 🚫 Not Null | - |
| Wet_Initals | `String` (5) | ⚠️ Required, 🚫 Not Null | - |
| Dry_Weight | `Boolean` | ⚠️ Required, 🚫 Not Null | - |
| Wet_Weight | `Boolean` | 🚫 Not Null | - |
| TopUp_Date | `Integer` | 🚫 Not Null | - |
| TopUp_Initials | `String` (5) | 🚫 Not Null | - |
| Moisture_Percent | `Boolean` | 🚫 Not Null | - |
| TopUp_Percent | `Boolean` | 🚫 Not Null | - |
| Does_Need_TopUp | `Real` | 🚫 Not Null | - |
| Part_No | `String` (20) | ⚠️ Required, 🚫 Not Null | - |
| Second_TopUp | `Real` | 🚫 Not Null | - |
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto, 🚫 Not Null | - |

### Detailed Information

#### Product_ID

**Properties:**

- **Type:** Date
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null, 🔒 Not Modifiable

---

#### Works_Order

**Properties:**

- **Type:** Date
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Chamber_No

**Properties:**

- **Type:** Picture
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Box_Number

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Actual_Time

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Wet_Date

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### TopUp_Weight

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Wet_Initals

**Properties:**

- **Type:** String (max length: 5)
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Dry_Weight

**Properties:**

- **Type:** Boolean
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Wet_Weight

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### TopUp_Date

**Properties:**

- **Type:** Integer
- **Constraints:** 🚫 Never Null

---

#### TopUp_Initials

**Properties:**

- **Type:** String (max length: 5)
- **Constraints:** 🚫 Never Null

---

#### Moisture_Percent

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### TopUp_Percent

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### Does_Need_TopUp

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### Part_No

**Properties:**

- **Type:** String (max length: 20)
- **Constraints:** ⚠️ Mandatory, 🚫 Never Null

---

#### Second_TopUp

**Properties:**

- **Type:** Real
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
| `Product_ID` | Keywords | regular | - |
| `Chamber_No` | Keywords | regular | - |
| `Works_Order` | Keywords | regular | - |
| `ID` | Keywords | regular | ✨ Yes |
| `Part_No` | Keywords | regular | - |

### Detailed Information

- **Field:** `Product_ID`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Chamber_No`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Works_Order`
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `ID` ✨ **(Unique)**
  - **Kind:** regular
  - **Type:** Keywords
- **Field:** `Part_No`
  - **Kind:** regular
  - **Type:** Keywords

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:17Z*
