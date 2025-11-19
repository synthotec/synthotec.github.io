---
layout : default
title : CapacityPlanning
parent : Forms
---
# CapacityPlanning [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/CapacityPlanning)

📊 **Overview:** 24 Objects | 6 Types | 2 Pages | 16 Events | 20 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Sizing** | X: variable, Y: variable |
| **Pages** | 2 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CapacityPlanning/method.4dm) |
| **Object Methods** | 20 |
| **Generated** | 🕐 2025-11-14T16:53:02.345Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (16)
- [🧩 Form Objects](#-form-objects) (24)
- [🔗 Related Items](#-related-items)
  - [Tables](#️-tables) (6)

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
| List Box | - | 📋 listbox | ✅ | ✅ | ❌ | $ListBox | [List Box.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CapacityPlanning/ObjectMethods/List%20Box.4dm) |
| List Box1 | - | 📋 listbox | ✅ | ✅ | ❌ | $ListBox1 | [List Box1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CapacityPlanning/ObjectMethods/List%20Box1.4dm) |
| List Box2 | - | 📋 listbox | ✅ | ✅ | ❌ | $ListBox2 | [List Box2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CapacityPlanning/ObjectMethods/List%20Box2.4dm) |
| List Box3 | - | 📋 listbox | ✅ | ✅ | ❌ | $ListBox3 | [List Box3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CapacityPlanning/ObjectMethods/List%20Box3.4dm) |
| Check Box | ALL | ☑️ checkbox | ✅ | ✅ | ❌ | allMC | [Check Box.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CapacityPlanning/ObjectMethods/Check%20Box.4dm) |
| Check Box1 | ALL | ☑️ checkbox | ✅ | ✅ | ❌ | allPALLET | - |
| Check Box2 | ALL | ☑️ checkbox | ✅ | ✅ | ❌ | allMANDREL | - |
| Button1 | + NEW PRODUCTS | 🔘 button | ✅ | ✅ | ❌ | Button1 | [Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CapacityPlanning/ObjectMethods/Button1.4dm) |
| Variable2 | - | 📝 input | ✅ | ✅ | ❌ | xbox | [Variable2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CapacityPlanning/ObjectMethods/Variable2.4dm) |
| Variable | - | 📝 input | ✅ | ✅ | ❌ | vSearch | [Variable.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CapacityPlanning/ObjectMethods/Variable.4dm) |
| Button2 | LOAD FORECAST | 🔘 button | ✅ | ✅ | ❌ | Button1 | [Button2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CapacityPlanning/ObjectMethods/Button2.4dm) |
| Button3 | LOAD | 🔘 button | ✅ | ✅ | ❌ | Button1 | [Button3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CapacityPlanning/ObjectMethods/Button3.4dm) |
| Button | EQUIPMENT LIST | 🔘 button | ✅ | ✅ | ❌ | Button | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CapacityPlanning/ObjectMethods/Button.4dm) |
| Popup Drop down List | - | 📥 dropdown | ✅ | ✅ | ❌ | vProfile | [Popup Drop down List.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CapacityPlanning/ObjectMethods/Popup%20Drop%20down%20List.4dm) |
| Text | Capacity Profile | 📄 text | ✅ | ✅ | ❌ | - | - |
| Button4 | New Profile | 🔘 button | ✅ | ✅ | ❌ | Button1 | [Button4.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CapacityPlanning/ObjectMethods/Button4.4dm) |
| Button5 | Rename | 🔘 button | ✅ | ✅ | ❌ | Button1 | [Button5.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CapacityPlanning/ObjectMethods/Button5.4dm) |
| Button6 | Delete | 🔘 button | ✅ | ✅ | ❌ | Button1 | [Button6.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CapacityPlanning/ObjectMethods/Button6.4dm) |
| Button7 | APPLY | 🔘 button | ✅ | ✅ | ❌ | Button1 | [Button7.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CapacityPlanning/ObjectMethods/Button7.4dm) |
| Button8 | Duplicate | 🔘 button | ✅ | ✅ | ❌ | Button1 | [Button8.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CapacityPlanning/ObjectMethods/Button8.4dm) |
| Popup Drop down List1 | - | 📥 dropdown | ✅ | ✅ | ❌ | vSnapDates | [Popup Drop down List1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CapacityPlanning/ObjectMethods/Popup%20Drop%20down%20List1.4dm) |
| Text1 | Snapshot Date | 📄 text | ✅ | ✅ | ❌ | - | - |
| Button9 | New Window | 🔘 button | ✅ | ✅ | ❌ | Button9 | [Button9.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CapacityPlanning/ObjectMethods/Button9.4dm) |
| Check Box3 | Hide Zero Forecast Lines | ☑️ checkbox | ✅ | ✅ | ❌ | CapacityPlanning_HideZero | [Check Box3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CapacityPlanning/ObjectMethods/Check%20Box3.4dm) |

## 🔗 Related Items

### 🗂️ Tables

- [Planning](../Tables/Planning.md) - Data source for CapacityPlanning form
- [Product](../Tables/Product.md) - Data source for CapacityPlanning form
- [SalesForecast](../Tables/SalesForecast.md) - Data source for CapacityPlanning form
- [Tools](../Tables/Tools.md) - Data source for CapacityPlanning form
- [PlanningSettings](../Tables/PlanningSettings.md) - Data source for CapacityPlanning form
- [EquipmentStock](../Tables/EquipmentStock.md) - Data source for CapacityPlanning form

---

*Generated from form.4DForm*
