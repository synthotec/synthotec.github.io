---
layout : default
title : ProcurementProgramImporter
parent : Forms
---
# ProcurementProgramImporter [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/ProcurementProgramImporter)

📊 **Overview:** 6 Objects | 3 Types | 2 Pages | 15 Events | 7 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Title** | window title |
| **Window Sizing** | X: variable, Y: variable |
| **Pages** | 2 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ProcurementProgramImporter/method.4dm) |
| **Object Methods** | 7 |
| **Generated** | 🕐 2025-11-14T16:53:02.521Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (15)
- [🧩 Form Objects](#-form-objects) (6)
- [🔗 Related Items](#-related-items)
  - [Tables](#️-tables) (1)

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

#### Page 1

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| List Box | - | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.VisibleLines | [List Box.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ProcurementProgramImporter/ObjectMethods/List%20Box.4dm) |
| Button | 📋 Read Data from Clipboard | 🔘 button | ✅ | ✅ | ❌ | - | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ProcurementProgramImporter/ObjectMethods/Button.4dm) |
| Check Box | Hide Actioned Orders | ☑️ checkbox | ✅ | ✅ | ❌ | Form:C1466.HideActioned | [Check Box.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ProcurementProgramImporter/ObjectMethods/Check%20Box.4dm) |
| ReloadButton | 🔃 Reload Data | 🔘 button | ✅ | ✅ | ❌ | - | [ReloadButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ProcurementProgramImporter/ObjectMethods/ReloadButton.4dm) |
| ProcessButton | ⚡Process Procurement Prgram Orders | 🔘 button | ✅ | ✅ | ❌ | - | [ProcessButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ProcurementProgramImporter/ObjectMethods/ProcessButton.4dm) |
| Check Box1 | Hide Forecast Orders | ☑️ checkbox | ✅ | ✅ | ❌ | Form:C1466.HideForecasts | [Check Box1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ProcurementProgramImporter/ObjectMethods/Check%20Box1.4dm) |

## 🔗 Related Items

### 🗂️ Tables

- [Settings](../Tables/Settings.md) - Data source for ProcurementProgramImporter form

---

*Generated from form.4DForm*
