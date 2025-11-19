---
layout : default
title : Forecast
parent : Forms
---
# Forecast [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/Forecast)

📊 **Overview:** 20 Objects | 6 Types | 2 Pages | 17 Events | 25 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Pages** | 2 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Forecast/method.4dm) |
| **Object Methods** | 25 |
| **Generated** | 🕐 2025-11-14T16:53:02.417Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (17)
- [🧩 Form Objects](#-form-objects) (20)

---

## 🎯 Form Events

This form handles **17** of **44** possible events:

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
| `onCloseBox` | ✅ | `onDeleteAction` | ❌ |
| `onRowResize` | ❌ | `onAlternativeClick` | ❌ |
| `onLongClick` | ❌ | `onMouseEnter` | ❌ |
| `onMouseLeave` | ❌ | `onMouseMove` | ❌ |

## 🧩 Form Objects

### Interactive Objects by Page

#### Page 1

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Popup Drop down List | - | 📥 dropdown | ✅ | ✅ | ❌ | Forecast_QueryYearArray | [Popup Drop down List.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Forecast/ObjectMethods/Popup%20Drop%20down%20List.4dm) |
| ForecastListBox | - | 📋 listbox | ✅ | ✅ | ❌ | ForecastListBox | [ForecastListBox.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Forecast/ObjectMethods/ForecastListBox.4dm) |
| Button | Add Products | 🔘 button | ✅ | ✅ | ❌ | Button | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Forecast/ObjectMethods/Button.4dm) |
| Popup Drop down List1 | - | 📥 dropdown | ✅ | ✅ | ❌ | qCustomers | [Popup Drop down List1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Forecast/ObjectMethods/Popup%20Drop%20down%20List1.4dm) |
| Variable | - | 📝 input | ✅ | ✅ | ❌ | vSearchBox | [Variable.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Forecast/ObjectMethods/Variable.4dm) |
| Button3 | Show Zero Forecasts | 🔘 button | ✅ | ✅ | ❌ | Button | [Button3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Forecast/ObjectMethods/Button3.4dm) |
| Popup Drop down List2 | - | 📥 dropdown | ✅ | ✅ | ❌ | qSnapList | [Popup Drop down List2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Forecast/ObjectMethods/Popup%20Drop%20down%20List2.4dm) |
| Text | SnapShot Date | 📄 text | ✅ | ✅ | ❌ | - | - |
| Button4 | Create SnapShot | 🔘 button | ✅ | ✅ | ❌ | Button | [Button4.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Forecast/ObjectMethods/Button4.4dm) |
| Popup Drop down List3 | - | 📥 dropdown | ✅ | ✅ | ❌ | Forecast_BackfillMonth | [Popup Drop down List3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Forecast/ObjectMethods/Popup%20Drop%20down%20List3.4dm) |
| Popup Drop down List4 | - | 📥 dropdown | ✅ | ✅ | ❌ | Forecast_BackfillYear | - |
| Button1 | Backfill | 🔘 button | ✅ | ✅ | ❌ | Button1 | [Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Forecast/ObjectMethods/Button1.4dm) |
| DateEntry | - | 🔲 subform | ✅ | ✅ | ❌ | vDateStart | [DateEntry.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Forecast/ObjectMethods/DateEntry.4dm) |
| DateEntry1 | - | 🔲 subform | ✅ | ✅ | ❌ | vDateFinish | [DateEntry1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Forecast/ObjectMethods/DateEntry1.4dm) |
| Text1 | Backfill forecast for  | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text2 | Using Advice Notes Generated from | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text3 | and before | 📄 text | ✅ | ✅ | ❌ | - | - |
| Button2 | Import Excel Forecast | 🔘 button | ✅ | ✅ | ❌ | Button2 | [Button2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Forecast/ObjectMethods/Button2.4dm) |
| List Box | - | 📋 listbox | ✅ | ✅ | ❌ | - | - |
| Variable1 | - | 📝 input | ✅ | ✅ | ❌ | LastUpdated | - |

---

*Generated from form.4DForm*
