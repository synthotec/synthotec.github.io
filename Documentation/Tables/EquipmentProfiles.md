---
layout : default
title : EquipmentProfiles
parent : Tables
---
# EquipmentProfiles

📊 **Overview:** 18 Fields | 1 Indexes

## ℹ️ Table Information

- **Table ID:** 59
- **UUID:** D8188042DA7A3C488CA350345D55AAE2
- **Primary Key:** 🔑 `ID`
- **Generated:** 🕐 2025-11-13T02:35:57Z

---

## 📑 Table of Contents

- [📋 Fields](#-fields) (18)
- [🔍 Indexes](#-indexes) (1)

---

## 📋 Fields

### Quick Reference

| Field | Type | Constraints | Description |
|:------|:-----|:------------|:------------|
| 🔑 **ID** | `Date` | 🔑 PK, ✨ Unique, ⚡ Auto | - |
| Tool_ID | `Date` | 🚫 Not Null | - |
| Machine | `Picture` | 🚫 Not Null | - |
| Pallet | `String` (255) | 🚫 Not Null | - |
| Mandrel | `String` (255) | 🚫 Not Null | - |
| RobotHead | `String` (255) | 🚫 Not Null | - |
| Grippers | `String` (255) | 🚫 Not Null | - |
| TargetCycleTime | `Boolean` | 🚫 Not Null | - |
| OverallOEE | `Boolean` | 🚫 Not Null | - |
| PalletLayout | `Picture` | 🚫 Not Null | - |
| MandrelCount | `Picture` | 🚫 Not Null | - |
| CagesPerMandrel | `Picture` | 🚫 Not Null | - |
| Comments | `String` (255) | 🚫 Not Null | - |
| BoxesPerPallet | `Boolean` | 🚫 Not Null | - |
| HandLoad | `Real` | 🚫 Not Null | - |
| HandLoadContainer | `String` (255) | 🚫 Not Null | - |
| ContainerCount | `String` (255) | 🚫 Not Null | - |
| ApprovedDate | `Integer` | 🚫 Not Null | - |

### Detailed Information

#### 🔑 ID

**Properties:**

- **Type:** Date
- **Constraints:** 🔑 Primary Key, ✨ Unique, ⚡ Auto-sequence

---

#### Tool_ID

**Properties:**

- **Type:** Date
- **Constraints:** 🚫 Never Null

---

#### Machine

**Properties:**

- **Type:** Picture
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

#### RobotHead

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### Grippers

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### TargetCycleTime

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### OverallOEE

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### PalletLayout

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### MandrelCount

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### CagesPerMandrel

**Properties:**

- **Type:** Picture
- **Constraints:** 🚫 Never Null

---

#### Comments

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### BoxesPerPallet

**Properties:**

- **Type:** Boolean
- **Constraints:** 🚫 Never Null

---

#### HandLoad

**Properties:**

- **Type:** Real
- **Constraints:** 🚫 Never Null

---

#### HandLoadContainer

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### ContainerCount

**Properties:**

- **Type:** String (max length: 255)
- **Constraints:** 🚫 Never Null

---

#### ApprovedDate

**Properties:**

- **Type:** Integer
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

---

*Generated from catalog.4DCatalog*
*Generated at: 2025-11-13T02:35:57Z*
