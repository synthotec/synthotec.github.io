---
layout : default
title : MaterialManagement
parent : Forms
---
# MaterialManagement [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/MaterialManagement)

📊 **Overview:** 14 Objects | 6 Types | 2 Pages | 1 Events | 8 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Pages** | 2 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MaterialManagement/method.4dm) |
| **Object Methods** | 8 |
| **Generated** | 🕐 2025-11-14T16:53:02.463Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (1)
- [🧩 Form Objects](#-form-objects) (14)
- [🔗 Related Items](#-related-items)
  - [Tables](#️-tables) (4)

---

## 🎯 Form Events

This form handles **1** of **44** possible events:

| Event | Status | Event | Status |
|:------|:------:|:------|:------:|
| `onLoad` | ✅ | `onUnload` | ❌ |
| `onValidate` | ❌ | `onClick` | ❌ |
| `onDoubleClick` | ❌ | `onHeader` | ❌ |
| `onPrintingBreak` | ❌ | `onPrintingFooter` | ❌ |
| `onDisplayDetail` | ❌ | `onOutsideCall` | ❌ |
| `onBeginDragOver` | ❌ | `onDragOver` | ❌ |
| `onDrop` | ❌ | `onAfterKeystroke` | ❌ |
| `onMenuSelect` | ❌ | `onPluginArea` | ❌ |
| `onAfterEdit` | ❌ | `onTimer` | ❌ |
| `onBoundVariableChange` | ❌ | `onPageChange` | ❌ |
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
| Popup Drop down List1 | - | 📥 dropdown | ✅ | ✅ | ❌ | vFromLocations | [Popup Drop down List1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MaterialManagement/ObjectMethods/Popup%20Drop%20down%20List1.4dm) |
| Text6 | From | 📄 text | ✅ | ✅ | ❌ | - | - |
| Popup Drop down List2 | - | 📥 dropdown | ✅ | ✅ | ❌ | vToLocations | [Popup Drop down List2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MaterialManagement/ObjectMethods/Popup%20Drop%20down%20List2.4dm) |
| Text7 | To | 📄 text | ✅ | ✅ | ❌ | - | - |
| List Box | - | 📋 listbox | ✅ | ✅ | ❌ | MaterialManagement_Listbox1 | - |
| Button1 | Move Selected Material(s) | 🔘 button | ✅ | ✅ | ❌ | Button | [Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MaterialManagement/ObjectMethods/Button1.4dm) |
| Text8 | Select Multiple Items by Holding Down CTRL While Selecting Items | 📄 text | ✅ | ✅ | ❌ | - | - |
| Popup Drop down List3 | - | 📥 dropdown | ✅ | ✅ | ❌ | vMaterials | [Popup Drop down List3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MaterialManagement/ObjectMethods/Popup%20Drop%20down%20List3.4dm) |
| Text9 | Material | 📄 text | ✅ | ✅ | ❌ | - | - |
| Button4 | Print ID Labels | 🔘 button | ✅ | ✅ | ❌ | Button4 | [Button4.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MaterialManagement/ObjectMethods/Button4.4dm) |
| List Box1 | - | 📋 listbox | ✅ | ✅ | ❌ | MaterialManagement_Listbox2 | [List Box1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MaterialManagement/ObjectMethods/List%20Box1.4dm) |
| Datepicker | - | 🔲 subform | ✅ | ✅ | ❌ | vDate | [Datepicker.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MaterialManagement/ObjectMethods/Datepicker.4dm) |
| Variable | - | 📝 input | ✅ | ✅ | ❌ | vDate | - |
| Button2 | Print A4 RMC Sheets | 🔘 button | ✅ | ✅ | ❌ | Button4 | [Button2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MaterialManagement/ObjectMethods/Button2.4dm) |

## 🔗 Related Items

### 🗂️ Tables

- [MaterialStock](../Tables/MaterialStock.md) - Data source for MaterialManagement form
- [MaterialLog](../Tables/MaterialLog.md) - Data source for MaterialManagement form
- [Material](../Tables/Material.md) - Data source for MaterialManagement form
- [RMC](../Tables/RMC.md) - Data source for MaterialManagement form

---

*Generated from form.4DForm*
