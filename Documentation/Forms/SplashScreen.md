---
layout : default
title : SplashScreen
parent : Forms
---
# SplashScreen [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/SplashScreen)

📊 **Overview:** 4 Objects | 2 Types | 3 Pages | 16 Events

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Title** | window title |
| **Window Sizing** | X: variable, Y: variable |
| **Pages** | 3 |
| **Form Method** | ✅ Yes |
| **Generated** | 🕐 2025-11-13T16:07:50.043Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (16)
- [🧩 Form Objects](#-form-objects) (4)

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
| `onDataChange` | ❌ | `onExpand` | ❌ |
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

| Name | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Text | 📄 text | ✅ | ✅ | ❌ | - | - |
| Country | 📝 input | ✅ | ✅ | ❌ | Uppercase:C13(ds:C1482.Settings.global("Location").getValue("United Kingdom")) | - |
| Input2 | 📝 input | ✅ | ✅ | ❌ | Form:C1466.VersionInfo | - |

#### Page 2

| Name | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Input | 📝 input | ✅ | ✅ | ❌ | SplashScreen_SplashImage | - |

---

*Generated from form.4DForm*
