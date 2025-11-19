---
layout : default
title : MaterialCheck
parent : Forms
---
# MaterialCheck [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/MaterialCheck)

📊 **Overview:** 16 Objects | 5 Types | 2 Pages | 16 Events | 3 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Sizing** | X: variable, Y: variable |
| **Pages** | 2 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MaterialCheck/method.4dm) |
| **Object Methods** | 3 |
| **Generated** | 🕐 2025-11-14T16:53:02.461Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (16)
- [🧩 Form Objects](#-form-objects) (16)

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
| Variable2 | - | 📝 input | ✅ | ✅ | ❌ | vTitle | - |
| Variable1 | - | 📝 input | ✅ | ✅ | ❌ | TranslateText("Planned Material") | - |
| Variable3 | - | 📝 input | ✅ | ✅ | ❌ | vPlannedMaterial | - |
| Variable4 | - | 📝 input | ✅ | ✅ | ❌ | TranslateText("Planned Closed Loop") | - |
| Variable5 | - | 📝 input | ✅ | ✅ | ❌ | vPlannedClosedLoop | - |
| Variable6 | - | 📝 input | ✅ | ✅ | ❌ | TranslateText("Using Material") | - |
| List Box | - | 📋 listbox | ✅ | ✅ | ❌ | - | [List Box.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MaterialCheck/ObjectMethods/List%20Box.4dm) |
| Popup Dropdown List | - | 📥 dropdown | ✅ | ✅ | ❌ | aMaterials | [Popup Dropdown List.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MaterialCheck/ObjectMethods/Popup%20Dropdown%20List.4dm) |
| Popup Dropdown List1 | - | 📥 dropdown | ✅ | ✅ | ❌ | aClosedLoop | - |
| Variable9 | - | 📝 input | ✅ | ✅ | ❌ | vComments | - |
| Button | Submit Material Check Results | 🔘 button | ✅ | ✅ | ❌ | - | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/MaterialCheck/ObjectMethods/Button.4dm) |
| Variable7 | - | 📝 input | ✅ | ✅ | ❌ | TranslateText("Closed Loop") | - |
| Variable8 | - | 📝 input | ✅ | ✅ | ❌ | TranslateText("RMC Information") | - |
| List Box1 | - | 📋 listbox | ✅ | ✅ | ❌ | - | - |
| Variable10 | - | 📝 input | ✅ | ✅ | ❌ | TranslateText("Comments / Reason") | - |
| Text | LINES THIS COLOUR INDICATE THAT THEY ARE FROM A MATERIAL CHECK COMPLETED FOR ANOTHER WORKS ORDER AND THIS MATERIAL IS SETUP TO USE A SHARED SOURCE | 📄 text | ✅ | ✅ | ❌ | - | - |

---

*Generated from form.4DForm*
