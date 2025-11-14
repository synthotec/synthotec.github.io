---
layout : default
title : CustomerInput
parent : Forms
---
# CustomerInput [![GitHub](../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/CustomerInput)

📊 **Overview:** 57 Objects | 8 Types | 2 Pages | 16 Events | 14 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Sizing** | X: variable, Y: variable |
| **Pages** | 2 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerInput/method.4dm) |
| **Object Methods** | 14 |
| **Generated** | 🕐 2025-11-14T16:36:00.500Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (16)
- [🧩 Form Objects](#-form-objects) (57)

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
| Field | - | 📝 input | ✅ | ✅ | ❌ | [Customer:1]Customer_Code:1 | - |
| Text | Customer Code
 | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text1 | Customer Name | 📄 text | ✅ | ✅ | ❌ | - | - |
| Field1 | - | 📝 input | ✅ | ✅ | ❌ | [Customer:1]Cust Name:2 | - |
| Variable | - | 📝 input | ✅ | ✅ | ❌ | vTitleText | - |
| Field2 | - | 📝 input | ✅ | ✅ | ❌ | [Customer:1]DeliveryAddress_txt:27 | - |
| Text2 | Delivery Address | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text3 | Delivery Time (Days) | 📄 text | ✅ | ✅ | ❌ | - | - |
| Field3 | - | 📝 input | ✅ | ✅ | ❌ | [Customer:1]DeliveryDays:29 | - |
| Text12 | Contact | 📄 text | ✅ | ✅ | ❌ | - | - |
| Popup Drop down List | - | 📥 dropdown | ✅ | ✅ | ❌ | vContactChooser | [Popup Drop down List.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerInput/ObjectMethods/Popup%20Drop%20down%20List.4dm) |
| Text4 | Name | 📄 text | ✅ | ✅ | ❌ | - | - |
| Field4 | - | 📝 input | ✅ | ✅ | ❌ | vContactName | [Field4.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerInput/ObjectMethods/Field4.4dm) |
| Text5 | Position | 📄 text | ✅ | ✅ | ❌ | - | - |
| Field5 | - | 📝 input | ✅ | ✅ | ❌ | vContactPosition | [Field5.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerInput/ObjectMethods/Field5.4dm) |
| Text6 | Phone Number | 📄 text | ✅ | ✅ | ❌ | - | - |
| Field6 | - | 📝 input | ✅ | ✅ | ❌ | vContactPhone | [Field6.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerInput/ObjectMethods/Field6.4dm) |
| Text7 | Email | 📄 text | ✅ | ✅ | ❌ | - | - |
| Field7 | - | 📝 input | ✅ | ✅ | ❌ | vContactEmail | [Field7.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerInput/ObjectMethods/Field7.4dm) |
| Hierarchical List | - | 📋 listbox | ✅ | ✅ | ❌ | Hierarchical List | - |
| Button | Save | 🔘 button | ✅ | ✅ | ❌ | Button | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerInput/ObjectMethods/Button.4dm) |
| Field19 | - | 📝 input | ✅ | ✅ | ❌ | [Customer:1]SupplierCode:28 | - |
| Text16 | Supplier Code | 📄 text | ✅ | ✅ | ❌ | - | - |
| Field9 | - | 📝 input | ✅ | ✅ | ❌ | [Customer:1]Cust Fax:9 | - |
| Text8 | Fax Number | 📄 text | ✅ | ✅ | ❌ | - | - |
| Field10 | - | 📝 input | ✅ | ✅ | ❌ | [Customer:1]Cust Notes:12 | - |
| Text9 | Main Address | 📄 text | ✅ | ✅ | ❌ | - | - |
| Field11 | - | 📝 input | ✅ | ✅ | ❌ | vCustomerAddress | [Field11.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerInput/ObjectMethods/Field11.4dm) |
| Text10 | Post Code | 📄 text | ✅ | ✅ | ❌ | - | - |
| Field12 | - | 📝 input | ✅ | ✅ | ❌ | [Customer:1]Cust Postcode:7 | - |
| Text13 | Label Heading Option 1 | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text14 | Label Heading Option 2 | 📄 text | ✅ | ✅ | ❌ | - | - |
| Field13 | - | 📝 input | ✅ | ✅ | ❌ | [Customer:1]Cust Label1:15 | - |
| Field14 | - | 📝 input | ✅ | ✅ | ❌ | [Customer:1]Cust Label2:16 | - |
| Button1 | Cancel | 🔘 button | ✅ | ✅ | ❌ | Button | [Button1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerInput/ObjectMethods/Button1.4dm) |
| Field16 | Archived | ☑️ checkbox | ✅ | ✅ | ❌ | [Customer:1]Archive:20 | - |
| Field17 | Certificate of Conformity Required | ☑️ checkbox | ✅ | ✅ | ❌ | [Customer:1]CofCRequired_b:26 | - |
| Button2 | Copy Address | 🔘 button | ✅ | ✅ | ❌ | Button2 | [Button2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerInput/ObjectMethods/Button2.4dm) |
| Cust_Cancel_l_b1 | Print Label | 🔘 button | ✅ | ✅ | ❌ | Cust_PrintLabel_l_b | [Cust_Cancel_l_b1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerInput/ObjectMethods/Cust_Cancel_l_b1.4dm) |
| Field18 | - | 📝 input | ✅ | ✅ | ❌ | [Customer:1]BoxesPerPallet:46 | - |
| Text11 | Boxes Per Pallet | 📄 text | ✅ | ✅ | ❌ | - | - |
| List Box | - | 📋 listbox | ✅ | ✅ | ❌ | $ListBox | - |
| Button3 | Add | 🔘 button | ✅ | ✅ | ❌ | Button3 | [Button3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerInput/ObjectMethods/Button3.4dm) |
| Button4 | Remove | 🔘 button | ✅ | ✅ | ❌ | Button3 | [Button4.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerInput/ObjectMethods/Button4.4dm) |
| List Box1 | - | 📋 listbox | ✅ | ✅ | ❌ | $ListBox | - |
| Button5 | Add | 🔘 button | ✅ | ✅ | ❌ | Button3 | [Button5.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerInput/ObjectMethods/Button5.4dm) |
| Button6 | Remove | 🔘 button | ✅ | ✅ | ❌ | Button3 | [Button6.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CustomerInput/ObjectMethods/Button6.4dm) |
| Check Box | Customer Requires Material Certificates | ☑️ checkbox | ✅ | ✅ | ❌ | [Customer:1]RequiresMaterialCofA:50 | - |

---

*Generated from form.4DForm*
