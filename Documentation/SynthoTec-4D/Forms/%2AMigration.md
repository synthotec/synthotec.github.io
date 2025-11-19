---
layout : default
title : %2AMigration
parent : Forms
---
# %2AMigration [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/%2AMigration)

📊 **Overview:** 14 Objects | 4 Types | 6 Pages | 15 Events | 11 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Title** | window title |
| **Window Sizing** | X: variable, Y: variable |
| **Pages** | 6 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AMigration/method.4dm) |
| **Object Methods** | 11 |
| **Generated** | 🕐 2025-11-14T16:53:02.250Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (15)
- [🧩 Form Objects](#-form-objects) (14)

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

#### Page 0 (Visible on All Pages)

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Form.Log | - | 📝 input | ✅ | ✅ | ❌ | Form:C1466.Log | - |
| TestModeButton | 🟢 Test Mode Active | 🔘 button | ✅ | ✅ | ❌ | - | [TestModeButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AMigration/ObjectMethods/TestModeButton.4dm) |
| Form_DataClass | - | 📥 dropdown | ✅ | ✅ | ❌ | Form_DataClass | [Form_DataClass.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AMigration/ObjectMethods/Form_DataClass.4dm) |
| AbortButton | 🛑Abort Migration | 🔘 button | ✅ | ✅ | ❌ | - | [AbortButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AMigration/ObjectMethods/AbortButton.4dm) |
| List Box4 | - | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.CompareCollection.orderBy("Field ASC") | - |
| Input | - | 📝 input | ✅ | ✅ | ❌ | Form:C1466.CompareTitle | - |

#### Page 1

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| List Box | - | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.ProductSelection | [List Box.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AMigration/ObjectMethods/List%20Box.4dm) |

#### Page 2

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| List Box1 | - | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.MaterialSelection | [List Box1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AMigration/ObjectMethods/List%20Box1.4dm) |

#### Page 3

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| List Box2 | - | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.CustomerSelection | [List Box2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AMigration/ObjectMethods/List%20Box2.4dm) |
| CustomersMigrateAdditionalButton | 🔀 Migrate Additional Data | 🔘 button | ✅ | ✅ | ❌ | - | [CustomersMigrateAdditionalButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AMigration/ObjectMethods/CustomersMigrateAdditionalButton.4dm) |

#### Page 4

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| List Box3 | - | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.WorksOrderSelection | [List Box3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AMigration/ObjectMethods/List%20Box3.4dm) |
| MigrateWOButton | ⚡Migrate S1 Works Order | 🔘 button | ✅ | ✅ | ❌ | - | [MigrateWOButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AMigration/ObjectMethods/MigrateWOButton.4dm) |

#### Page 5

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| List Box5 | - | 📋 listbox | ✅ | ✅ | ❌ | Form:C1466.PalletSelection | [List Box5.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AMigration/ObjectMethods/List%20Box5.4dm) |
| MigrateWOButton1 | ⚡Migrate S1 Pallets (Sent to S2) | 🔘 button | ✅ | ✅ | ❌ | - | [MigrateWOButton1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/%2AMigration/ObjectMethods/MigrateWOButton1.4dm) |

---

*Generated from form.4DForm*
