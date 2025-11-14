---
layout : default
title : NewScrapEntry
parent : Forms
---
# NewScrapEntry [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/NewScrapEntry)

📊 **Overview:** 26 Objects | 5 Types | 2 Pages | 16 Events | 15 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Sizing** | X: fixed, Y: fixed |
| **Pages** | 2 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/NewScrapEntry/method.4dm) |
| **Object Methods** | 15 |
| **Generated** | 🕐 2025-11-14T00:18:22.259Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (16)
- [🧩 Form Objects](#-form-objects) (26)

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

#### Page 0 (Visible on All Pages)

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Variable | - | 📝 input | ✅ | ✅ | ❌ | NewScrapEntry_WorksOrder | [Variable.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/NewScrapEntry/ObjectMethods/Variable.4dm) |
| List Box | - | 📋 listbox | ✅ | ✅ | ❌ | List Box | [List Box.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/NewScrapEntry/ObjectMethods/List%20Box.4dm) |
| Popup Drop down List | - | 📥 dropdown | ✅ | ✅ | ❌ | vType | [Popup Drop down List.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/NewScrapEntry/ObjectMethods/Popup%20Drop%20down%20List.4dm) |
| Popup Drop down List1 | - | 📥 dropdown | ✅ | ✅ | ❌ | NewScrapEntry_FaultsArray | [Popup Drop down List1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/NewScrapEntry/ObjectMethods/Popup%20Drop%20down%20List1.4dm) |
| Popup Drop down List2 | - | 📥 dropdown | ✅ | ✅ | ❌ | NewScrapEntry_ReasonsArray | [Popup Drop down List2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/NewScrapEntry/ObjectMethods/Popup%20Drop%20down%20List2.4dm) |
| Variable1 | - | 📝 input | ✅ | ✅ | ❌ | ToolPic | - |
| Text | TYPE THE WORKS ORDER NUMBER OR SCAN THE ROUTE CARD BARCODE | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text1 | SELECT THE PART NAME FROM BELOW | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text2 | SELECT THE SCRAP FAULT | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text3 | SELECT WHAT YOU ARE SCRAPPING | 📄 text | ✅ | ✅ | ❌ | - | - |
| Variable2 | - | 📝 input | ✅ | ✅ | ❌ | vCount | [Variable2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/NewScrapEntry/ObjectMethods/Variable2.4dm) |
| Text4 | TYPE | 📄 text | ✅ | ✅ | ❌ | - | - |
| List Box1 | - | 📋 listbox | ✅ | ✅ | ❌ | List Box1 | [List Box1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/NewScrapEntry/ObjectMethods/List%20Box1.4dm) |
| Button | Button | 🔘 button | ✅ | ✅ | ❌ | Submit | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/NewScrapEntry/ObjectMethods/Button.4dm) |
| Text5 | SELECT THE SCRAP REASON | 📄 text | ✅ | ✅ | ❌ | - | - |
| Variable3 | - | 📝 input | ✅ | ✅ | ❌ | vFob | [Variable3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/NewScrapEntry/ObjectMethods/Variable3.4dm) |
| Variable4 | - | 📝 input | ✅ | ✅ | ❌ | vSearch | [Variable4.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/NewScrapEntry/ObjectMethods/Variable4.4dm) |
| Button2 | Cancel | 🔘 button | ✅ | ✅ | ❌ | Can | [Button2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/NewScrapEntry/ObjectMethods/Button2.4dm) |
| Variable5 | - | 📝 input | ✅ | ✅ | ❌ | vComment | - |
| Text6 | ADDITIONAL COMMENT | 📄 text | ✅ | ✅ | ❌ | - | - |
| Variable6 | - | 📝 input | ✅ | ✅ | ❌ | NewScrapEntry_RCSequence | - |
| Text7 | ROUTE CARD SEQUENCE | 📄 text | ✅ | ✅ | ❌ | - | - |
| Variable7 | - | 📝 input | ✅ | ✅ | ❌ | vCommentDisplay | [Variable7.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/NewScrapEntry/ObjectMethods/Variable7.4dm) |
| Variable8 | - | 📝 input | ✅ | ✅ | ❌ | vSearchX | [Variable8.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/NewScrapEntry/ObjectMethods/Variable8.4dm) |
| Button3 | Manage Scrap Faults / Reasons | 🔘 button | ✅ | ✅ | ❌ | ScrapReasonButton | [Button3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/NewScrapEntry/ObjectMethods/Button3.4dm) |

#### Page 1

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Button1 | NEW ENTRY | 🔘 button | ✅ | ✅ | ❌ | scrapbutton | [Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/NewScrapEntry/ObjectMethods/Button1.4dm) |

---

*Generated from form.4DForm*
