---
layout : default
title : CycleHistory
parent : Forms
---
# CycleHistory [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/CycleHistory)

📊 **Overview:** 6 Objects | 4 Types | 2 Pages | 16 Events | 4 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Pages** | 2 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CycleHistory/method.4dm) |
| **Object Methods** | 4 |
| **Generated** | 🕐 2025-11-14T00:07:30.097Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (16)
- [🧩 Form Objects](#-form-objects) (6)

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

#### Page 1

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| List Box | - | 📋 listbox | ✅ | ✅ | ❌ | $ListBox | [List Box.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CycleHistory/ObjectMethods/List%20Box.4dm) |
| List Box1 | - | 📋 listbox | ✅ | ✅ | ❌ | - | [List Box1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CycleHistory/ObjectMethods/List%20Box1.4dm) |
| Button | Refresh | 🔘 button | ✅ | ✅ | ❌ | - | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CycleHistory/ObjectMethods/Button.4dm) |
| Variable | - | 📝 input | ✅ | ✅ | ❌ | "CYCLE TIME HISTORY FOR WORKS ORDER "+String:C10(<>HistoryWO)+" FOR "+vDateRange | - |
| Text | SELECT A LINE TO SEE THE CYCLE TIME HISTORY FOR THAT DATE | 📄 text | ✅ | ✅ | ❌ | - | - |
| Button1 | Export to Excel File | 🔘 button | ✅ | ✅ | ❌ | - | [Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CycleHistory/ObjectMethods/Button1.4dm) |

---

*Generated from form.4DForm*
