---
layout : default
title : QuarantineManager
parent : Forms
---
# QuarantineManager [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/QuarantineManager)

📊 **Overview:** 17 Objects | 5 Types | 2 Pages | 16 Events | 6 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Title** | Quarantined Stock Manager |
| **Window Sizing** | X: fixed, Y: fixed |
| **Pages** | 2 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/QuarantineManager/method.4dm) |
| **Object Methods** | 6 |
| **Generated** | 🕐 2025-12-03T16:38:20.476Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (16)
- [🧩 Form Objects](#-form-objects) (17)
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

#### Page 1

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Variable | - | 📝 input | ✅ | ✅ | ❌ | vWorksOrder | [Variable.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/QuarantineManager/ObjectMethods/Variable.4dm) |
| Text | Works Order | 📄 text | ✅ | ✅ | ❌ | - | - |
| Variable1 | - | 📝 input | ✅ | ✅ | ❌ | vQFinished | - |
| Variable2 | - | 📝 input | ✅ | ✅ | ❌ | vWOFinished | - |
| Field | - | 📝 input | ✅ | ✅ | ❌ | [Product:10]Our Part No:2 | - |
| Variable3 | - | 📝 input | ✅ | ✅ | ❌ | vParts | [Variable3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/QuarantineManager/ObjectMethods/Variable3.4dm) |
| Variable4 | - | 📝 input | ✅ | ✅ | ❌ | vBoxes | [Variable4.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/QuarantineManager/ObjectMethods/Variable4.4dm) |
| Button | Move to Quarantine | 🔘 button | ✅ | ✅ | ❌ | Button | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/QuarantineManager/ObjectMethods/Button.4dm) |
| Button1 | Release to Finished Goods | 🔘 button | ✅ | ✅ | ❌ | Button1 | [Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/QuarantineManager/ObjectMethods/Button1.4dm) |
| Text1 | Product | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text4 | Finished Goods | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text5 | Quarantined | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text6 | Parts to Move | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text7 | Boxes to Move | 📄 text | ✅ | ✅ | ❌ | - | - |
| Button2 | Button | 🔘 button | ✅ | ✅ | ❌ | Button2 | [Button2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/QuarantineManager/ObjectMethods/Button2.4dm) |

## 🔗 Related Items

### 🗂️ Tables

- [Product](../Tables/Product.md) - Data source for QuarantineManager form
- [WorksOrder](../Tables/WorksOrder.md) - Data source for QuarantineManager form
- [Finished_Stock](../Tables/Finished_Stock.md) - Data source for QuarantineManager form

---

*Generated from form.4DForm*
