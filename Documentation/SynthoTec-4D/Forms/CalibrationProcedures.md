---
layout : default
title : CalibrationProcedures
parent : Forms
---
# CalibrationProcedures [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/CalibrationProcedures)

📊 **Overview:** 21 Objects | 5 Types | 6 Pages | 16 Events | 6 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Sizing** | X: fixed, Y: fixed |
| **Pages** | 6 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CalibrationProcedures/method.4dm) |
| **Object Methods** | 6 |
| **Generated** | 🕐 2025-12-03T16:38:20.269Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (16)
- [🧩 Form Objects](#-form-objects) (21)
- [🔗 Related Items](#-related-items)
  - [Tables](#️-tables) (3)

---

## 🎯 Form Events

This form handles **16** of **44** possible events:

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
| `onDataChange` | ✅ | `onExpand` | ❌ |
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
| Title* | - | 📝 input | ✅ | ✅ | ❌ | CalibrationProcedures_Title | [Title%2A.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CalibrationProcedures/ObjectMethods/Title%2A.4dm) |
| List Box | - | 📋 listbox | ✅ | ✅ | ❌ | - | [List Box.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CalibrationProcedures/ObjectMethods/List%20Box.4dm) |
| Variable1 | - | 📝 input | ✅ | ✅ | ❌ | CalibrationProcedure_Desc | - |
| Popup Dropdown List | - | 📥 dropdown | ✅ | ✅ | ❌ | CalibrationProcedures_Type | [Popup Dropdown List.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CalibrationProcedures/ObjectMethods/Popup%20Dropdown%20List.4dm) |
| Text | Procedure Description | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text1 | Procedure Result Type | 📄 text | ✅ | ✅ | ❌ | - | - |
| Button | Save Procedure | 🔘 button | ✅ | ✅ | ❌ | - | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CalibrationProcedures/ObjectMethods/Button.4dm) |
| Button1 | Add Procedure | 🔘 button | ✅ | ✅ | ❌ | - | [Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CalibrationProcedures/ObjectMethods/Button1.4dm) |

#### Page 1

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Button2 | Cancel | 🔘 button | ✅ | ✅ | ❌ | - | [Button2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CalibrationProcedures/ObjectMethods/Button2.4dm) |
| Text8 | Select a prodedure to modify it | 📄 text | ✅ | ✅ | ❌ | - | - |

#### Page 3

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Text2 | Number Target Between | 📄 text | ✅ | ✅ | ❌ | - | - |
| Variable2 | - | 📝 input | ✅ | ✅ | ❌ | CalibrationProcedure_Min | - |
| Text3 | Number Target Between | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text4 | and | 📄 text | ✅ | ✅ | ❌ | - | - |
| Variable3 | - | 📝 input | ✅ | ✅ | ❌ | CalibrationProcedure_Max | - |

#### Page 4

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Text5 | Number Target | 📄 text | ✅ | ✅ | ❌ | - | - |
| Variable4 | - | 📝 input | ✅ | ✅ | ❌ | CalibrationProcedure_Target | - |
| Text7 | - | 📄 text | ✅ | ✅ | ❌ | - | - |
| Variable5 | - | 📝 input | ✅ | ✅ | ❌ | CalibrationProcedure_Minus | - |
| Text6 | + | 📄 text | ✅ | ✅ | ❌ | - | - |
| Variable6 | - | 📝 input | ✅ | ✅ | ❌ | CalibrationProcedure_Plus | - |

## 🔗 Related Items

### 🗂️ Tables

- [CalibrationProcedures](../Tables/CalibrationProcedures.md) - Data source for CalibrationProcedures form
- [Translation](../Tables/Translation.md) - Data source for CalibrationProcedures form
- [CalibrationEquipment](../Tables/CalibrationEquipment.md) - Data source for CalibrationProcedures form

---

*Generated from form.4DForm*
