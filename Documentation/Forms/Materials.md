---
layout : default
title : Materials
parent : Forms
---
# Materials [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/Materials)

📊 **Overview:** 39 Objects | 9 Types | 4 Pages | 15 Events | 19 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Title** | window title |
| **Window Sizing** | X: variable, Y: variable |
| **Pages** | 4 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Materials/method.4dm) |
| **Object Methods** | 19 |
| **Generated** | 🕐 2025-11-13T23:49:49.448Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (15)
- [🧩 Form Objects](#-form-objects) (39)

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
| Check Box | Show Archived Materials | ☑️ checkbox | ✅ | ✅ | ❌ | Materials_IncludeArchived | [Check Box.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Materials/ObjectMethods/Check%20Box.4dm) |
| Radio Button | Sort By Name | 🔘 radio | ✅ | ✅ | ❌ | Materials_NameSort | [Radio Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Materials/ObjectMethods/Radio%20Button.4dm) |
| Radio Button1 | Sort By Colour | 🔘 radio | ✅ | ✅ | ❌ | Materials_ColourSort | [Radio Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Materials/ObjectMethods/Radio%20Button1.4dm) |
| Rectangle1 | text default | 📄 text | ✅ | ✅ | ❌ | - | - |
| Button | CONVERT OLD COLOURS | 🔘 button | ✅ | ✅ | ❌ | - | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Materials/ObjectMethods/Button.4dm) |
| Text | Right click a material to change its colour | 📄 text | ✅ | ✅ | ❌ | - | - |
| Input | - | 📝 input | ✅ | ✅ | ❌ | Materials_Name | - |
| Text1 | Material Name | 📄 text | ✅ | ✅ | ❌ | - | - |
| Input1 | - | 📝 input | ✅ | ✅ | ❌ | Materials_Manufacturer | - |
| Text2 | Material Manufacturer | 📄 text | ✅ | ✅ | ❌ | - | - |
| Input2 | - | 📝 input | ✅ | ✅ | ❌ | Materials_Supplier | - |
| Text3 | Material Supplier | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text4 | Usage Material A | 📄 text | ✅ | ✅ | ❌ | - | - |
| Popup Dropdown List | - | 📥 dropdown | ✅ | ✅ | ❌ | Materials_UsageMaterialA | [Popup Dropdown List.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Materials/ObjectMethods/Popup%20Dropdown%20List.4dm) |
| Text5 | Usage Material B | 📄 text | ✅ | ✅ | ❌ | - | - |
| Popup Dropdown List1 | - | 📥 dropdown | ✅ | ✅ | ❌ | Materials_UsageMaterialB | [Popup Dropdown List1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Materials/ObjectMethods/Popup%20Dropdown%20List1.4dm) |
| Input3 | - | 📝 input | ✅ | ✅ | ❌ | Materials_UsageMatBPercent | [Input3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Materials/ObjectMethods/Input3.4dm) |
| Text6 | Usage Material B % | 📄 text | ✅ | ✅ | ❌ | - | - |
| Input4 | - | 📝 input | ✅ | ✅ | ❌ | Materials_UsageMatAPercent | - |
| Text7 | Usage Material A % | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text8 | Usage Material C | 📄 text | ✅ | ✅ | ❌ | - | - |
| Popup Dropdown List2 | - | 📥 dropdown | ✅ | ✅ | ❌ | Materials_UsageMaterialC | [Popup Dropdown List2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Materials/ObjectMethods/Popup%20Dropdown%20List2.4dm) |
| Input5 | - | 📝 input | ✅ | ✅ | ❌ | Materials_UsageMatCPercent | [Input5.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Materials/ObjectMethods/Input5.4dm) |
| Text9 | Usage Material C % | 📄 text | ✅ | ✅ | ❌ | - | - |
| EditButton | EDIT MATERIAL RECORD | 🔘 button | ✅ | ✅ | ❌ | - | [EditButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Materials/ObjectMethods/EditButton.4dm) |
| CancelButton | CANCEL | 🔘 button | ✅ | ✅ | ❌ | - | [CancelButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Materials/ObjectMethods/CancelButton.4dm) |
| SaveButton | SAVE | 🔘 button | ✅ | ✅ | ❌ | - | [SaveButton.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Materials/ObjectMethods/SaveButton.4dm) |
| Button1 | New Material | 🔘 button | ✅ | ✅ | ❌ | - | [Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Materials/ObjectMethods/Button1.4dm) |
| SearchPicker | - | 🔲 subform | ✅ | ✅ | ❌ | Materials_Search | [SearchPicker.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Materials/ObjectMethods/SearchPicker.4dm) |
| ArchiveButton* | EDIT MATERIAL RECORD | 🔘 button | ✅ | ✅ | ❌ | - | [ArchiveButton%2A.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Materials/ObjectMethods/ArchiveButton%2A.4dm) |
| Materials_MaterialsList | - | 📋 listbox | ✅ | ✅ | ❌ | - | [Materials_MaterialsList.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Materials/ObjectMethods/Materials_MaterialsList.4dm) |
| RemoveButtonC | Remove | 🔘 button | ✅ | ✅ | ❌ | - | [RemoveButtonC.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Materials/ObjectMethods/RemoveButtonC.4dm) |
| RemoveButtonB | Remove | 🔘 button | ✅ | ✅ | ❌ | - | [RemoveButtonB.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Materials/ObjectMethods/RemoveButtonB.4dm) |
| Text12 | Shared Material Source | 📄 text | ✅ | ✅ | ❌ | - | - |
| Form.SharedMaterialSource | - | 📥 dropdown | ✅ | ✅ | ❌ | Form:C1466.SharedMaterialSource.CollectionObject() | [Form.SharedMaterialSource.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/Materials/ObjectMethods/Form.SharedMaterialSource.4dm) |

#### Page 2

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Text10 | Select a material record | 📄 text | ✅ | ✅ | ❌ | - | - |

#### Page 3

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Text11 | Editing in progress | 📄 text | ✅ | ✅ | ❌ | - | - |

---

*Generated from form.4DForm*
