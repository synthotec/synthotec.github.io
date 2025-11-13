---
layout : default
title : BOM
parent : Forms
---
# BOM

📊 **Overview:** 10 Objects | 4 Types | 2 Pages | 17 Events | 8 Object Methods

## 📸 Screenshots

### BOM Management Screen

![BOM Management Screen](Images/BOM-1.png)

Main view showing the Bill of Materials interface with listbox for parts selection and management controls.

---

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Pages** | 2 |
| **Form Method** | ✅ Yes |
| **Object Methods** | 8 |
| **Generated** | 🕐 2025-11-13T15:37:17.262Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (17)
- [🧩 Form Objects](#-form-objects) (10)

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

**Total Objects:** 10

### Object Type Summary

| Object Type | Count |
|:------------|------:|
| 📋 listbox | 2 |
| 🔘 button | 4 |
| 🔲 subform | 2 |
| 📥 dropdown | 2 |

### Interactive Objects by Page

#### Page 1

| Name | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| List Box | 📋 listbox | ✅ | ✅ | ❌ | MasterList | List Box.4dm |
| Button1 | 🔘 button | ✅ | ✅ | ❌ | - | Button1.4dm |
| List Box1 | 📋 listbox | ✅ | ✅ | ❌ | - | List Box1.4dm |
| SearchPicker | 🔲 subform | ✅ | ✅ | ❌ | vSearch | SearchPicker.4dm |
| Popup Dropdown List | 📥 dropdown | ✅ | ✅ | ❌ | BOM_AddProductCustomers | - |
| SearchPicker1 | 🔲 subform | ✅ | ✅ | ❌ | BOM_AddProductFilter | SearchPicker1.4dm |
| Popup Dropdown List1 | 📥 dropdown | ✅ | ✅ | ❌ | BOM_AddProductArray | - |
| Button | 🔘 button | ✅ | ✅ | ❌ | - | Button.4dm |
| Button2 | 🔘 button | ✅ | ✅ | ❌ | - | Button2.4dm |
| Button3 | 🔘 button | ✅ | ✅ | ❌ | - | Button3.4dm |

---

*Generated from form.4DForm*
