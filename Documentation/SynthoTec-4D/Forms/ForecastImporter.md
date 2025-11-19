---
layout : default
title : ForecastImporter
parent : Forms
---
# ForecastImporter [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/ForecastImporter)

📊 **Overview:** 9 Objects | 5 Types | 2 Pages | 16 Events | 4 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Sizing** | X: fixed, Y: fixed |
| **Pages** | 2 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ForecastImporter/method.4dm) |
| **Object Methods** | 4 |
| **Generated** | 🕐 2025-11-14T16:53:02.422Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (16)
- [🧩 Form Objects](#-form-objects) (9)
- [🔗 Related Items](#-related-items)
  - [Tables](#️-tables) (2)

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
| Button1 | Read Clipboard Data | 🔘 button | ✅ | ✅ | ❌ | Button1 | [Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ForecastImporter/ObjectMethods/Button1.4dm) |
| List Box | - | 📋 listbox | ✅ | ✅ | ❌ | MissingList | [List Box.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ForecastImporter/ObjectMethods/List%20Box.4dm) |
| Popup Drop down List | - | 📥 dropdown | ✅ | ✅ | ❌ | Forecast_ImportMonth | - |
| Button2 | Apply To Forecast | 🔘 button | ✅ | ✅ | ❌ | Button1 | [Button2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ForecastImporter/ObjectMethods/Button2.4dm) |
| Text | Import From | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text1 | To import data go to the SUMMARY PIVOT sheet in the Excel forecast and follow the instructions in cell P3

Double click a missing from forecast line to add it to the forecast

Select Apply To Forecast to commit the schedule changes (You should aim to have all non-zero items corrected first) | 📄 text | ✅ | ✅ | ❌ | - | - |
| Popup Drop down List1 | - | 📥 dropdown | ✅ | ✅ | ❌ | Forecast_ImportYear | [Popup Drop down List1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/ForecastImporter/ObjectMethods/Popup%20Drop%20down%20List1.4dm) |
| Text2 | Import Year | 📄 text | ✅ | ✅ | ❌ | - | - |
| Variable | - | 📝 input | ✅ | ✅ | ❌ | LastUpdated | - |

## 🔗 Related Items

### 🗂️ Tables

- [SalesForecast](../Tables/SalesForecast.md) - Data source for ForecastImporter form
- [Product](../Tables/Product.md) - Data source for ForecastImporter form

---

*Generated from form.4DForm*
