---
layout : default
title : CalibrationLog
parent : Forms
---
# CalibrationLog [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/CalibrationLog)

📊 **Overview:** 12 Objects | 4 Types | 6 Pages | 15 Events | 4 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Title** | window title |
| **Window Sizing** | X: fixed, Y: fixed |
| **Pages** | 6 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CalibrationLog/method.4dm) |
| **Object Methods** | 4 |
| **Generated** | 🕐 2025-12-03T16:38:20.264Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (15)
- [🧩 Form Objects](#-form-objects) (12)
- [🔗 Related Items](#-related-items)
  - [Tables](#️-tables) (4)

---

## 🎯 Form Events

This form handles **15** of **44** possible events:

| Event | Status | Event | Status |
|:------|:------:|:------|:------:|
| `onLoad` | ✅ | `onUnload` | ❌ |
| `onValidate` | ✅ | `onClick` | ✅ |
| `onDoubleClick` | ✅ | `onHeader` | ❌ |
| `onPrintingBreak` | ❌ | `onPrintingFooter` | ❌ |
| `onDisplayDetail` | ❌ | `onOutsideCall` | ✅ |
| `onBeginDragOver` | ✅ | `onDragOver` | ✅ |
| `onDrop` | ✅ | `onAfterKeystroke` | ✅ |
| `onMenuSelect` | ✅ | `onPluginArea` | ✅ |
| `onAfterEdit` | ✅ | `onTimer` | ✅ |
| `onBoundVariableChange` | ✅ | `onPageChange` | ✅ |
| `onBeforeDataEntry` | ❌ | `onLoadRecord` | ❌ |
| `onAfterSort` | ❌ | `onSelectionChange` | ❌ |
| `onDataChange` | ❌ | `onExpand` | ❌ |
| `onCollapse` | ❌ | `onBeforeKeystroke` | ❌ |
| `onOpenDetail` | ❌ | `onCloseDetail` | ❌ |
| `onResize` | ❌ | `onActivate` | ❌ |
| `onDeactivate` | ❌ | `onOpenExternalLink` | ❌ |
| `onWindowOpeningDenied` | ❌ | `onScroll` | ❌ |
| `onCloseBox` | ❌ | `onDeleteAction` | ❌ |
| `onRowResize` | ❌ | `onAlternativeClick` | ❌ |
| `onLongClick` | ❌ | `onMouseEnter` | ❌ |
| `onMouseLeave` | ❌ | `onMouseMove` | ❌ |

## 🧩 Form Objects

### Interactive Objects by Page

#### Page 0 (Visible on All Pages)

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Title* | - | 📝 input | ✅ | ✅ | ❌ | CalibrationLog_Title | [Title%2A.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CalibrationLog/ObjectMethods/Title%2A.4dm) |
| Button* | Button | 🔘 button | ✅ | ✅ | ❌ | - | [Button%2A.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CalibrationLog/ObjectMethods/Button%2A.4dm) |
| Title*1 | - | 📝 input | ✅ | ✅ | ❌ | CalibrationLog_Step | [Title%2A1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CalibrationLog/ObjectMethods/Title%2A1.4dm) |

#### Page 1

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Input | - | 📝 input | ✅ | ✅ | ❌ | CalibrationLog_Date | - |

#### Page 2

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Input1 | - | 📝 input | ✅ | ✅ | ❌ | CalibrationLog_FileName | - |
| Button | Select A File | 🔘 button | ✅ | ✅ | ❌ | - | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CalibrationLog/ObjectMethods/Button.4dm) |

#### Page 3

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Input2 | - | 📝 input | ✅ | ✅ | ✅ | CalibrationLog_Number | - |
| Text | Result | 📄 text | ✅ | ✅ | ❌ | - | - |
| Input3 | - | 📝 input | ✅ | ✅ | ❌ | CalibrationLog_NumberTarget | - |

#### Page 4

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Input4 | - | 📝 input | ✅ | ✅ | ❌ | CalibrationLog_Text | - |

#### Page 5

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Text1 | The Above Statement is | 📄 text | ✅ | ✅ | ❌ | - | - |
| Popup Dropdown List | - | 📥 dropdown | ✅ | ✅ | ❌ | CalibrationLog_Boolean | - |

## 🔗 Related Items

### 🗂️ Tables

- [CalibrationEquipment](../Tables/CalibrationEquipment.md) - Data source for CalibrationLog form
- [CalibrationProcedures](../Tables/CalibrationProcedures.md) - Data source for CalibrationLog form
- [Calibrations](../Tables/Calibrations.md) - Data source for CalibrationLog form
- [CalibrationResults](../Tables/CalibrationResults.md) - Data source for CalibrationLog form

---

*Generated from form.4DForm*
