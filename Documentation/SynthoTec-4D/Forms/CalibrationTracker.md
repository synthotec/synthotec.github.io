---
layout : default
title : CalibrationTracker
parent : Forms
---
# CalibrationTracker [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/tree/main/Project/Sources/Forms/CalibrationTracker)

📊 **Overview:** 37 Objects | 6 Types | 4 Pages | 17 Events | 11 Object Methods

## ℹ️ Form Information

| Property | Value |
|:---------|:------|
| **Destination** | detailScreen |
| **Window Sizing** | X: fixed, Y: fixed |
| **Pages** | 4 |
| **Form Method** | ✅ [method.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CalibrationTracker/method.4dm) |
| **Object Methods** | 11 |
| **Generated** | 🕐 2025-11-19T20:54:38.108Z |

---

## 📑 Table of Contents

- [🎯 Form Events](#-form-events) (17)
- [🧩 Form Objects](#-form-objects) (37)
- [🔗 Related Items](#-related-items)
  - [Tables](#️-tables) (4)

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

### Interactive Objects by Page

#### Page 0 (Visible on All Pages)

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Button | Add Equipment | 🔘 button | ✅ | ✅ | ❌ | - | [Button.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CalibrationTracker/ObjectMethods/Button.4dm) |
| Button4 | Refresh | 🔘 button | ✅ | ✅ | ❌ | - | [Button4.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CalibrationTracker/ObjectMethods/Button4.4dm) |
| List Box | - | 📋 listbox | ✅ | ✅ | ❌ | EquipmentListBox | [List Box.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CalibrationTracker/ObjectMethods/List%20Box.4dm) |
| Variable | - | 📝 input | ✅ | ✅ | ❌ | "EQUIPMENT ID #"+String:C10(CalibrationTracker_VisibleID) | - |
| ButtonLog | Log Calibration | 🔘 button | ✅ | ✅ | ❌ | ButtonLog | [ButtonLog.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CalibrationTracker/ObjectMethods/ButtonLog.4dm) |
| List Box1 | - | 📋 listbox | ✅ | ✅ | ❌ | - | [List Box1.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CalibrationTracker/ObjectMethods/List%20Box1.4dm) |
| Variable2 | - | 📝 input | ✅ | ✅ | ❌ | vLocation | - |
| Popup Dropdown List4 | - | 📥 dropdown | ✅ | ✅ | ❌ | aCalibrationType | - |
| bMethods | Edit Calibration Methods | 🔘 button | ✅ | ✅ | ❌ | MethodsButton | [bMethods.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CalibrationTracker/ObjectMethods/bMethods.4dm) |
| Popup Dropdown List | - | 📥 dropdown | ✅ | ✅ | ❌ | aUsageFrequency | - |
| Popup Dropdown List1 | - | 📥 dropdown | ✅ | ✅ | ❌ | aWearRate | - |
| Popup Dropdown List2 | - | 📥 dropdown | ✅ | ✅ | ❌ | aEnvironment | - |
| Popup Dropdown List3 | - | 📥 dropdown | ✅ | ✅ | ❌ | aSensitivity | - |
| Variable6 | - | 📝 input | ✅ | ✅ | ❌ | vContact | - |
| Variable4 | - | 📝 input | ✅ | ✅ | ❌ | vNotes | - |
| Button5 | Edit Equipment | 🔘 button | ✅ | ✅ | ❌ | EditButton | [Button5.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CalibrationTracker/ObjectMethods/Button5.4dm) |
| Button3 | Cancel Changes | 🔘 button | ✅ | ✅ | ❌ | CancelButton | [Button3.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CalibrationTracker/ObjectMethods/Button3.4dm) |
| Button2 | Save Changes | 🔘 button | ✅ | ✅ | ❌ | SaveButton | [Button2.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CalibrationTracker/ObjectMethods/Button2.4dm) |
| Text1 | Equipment Name | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text2 | Equipment Location | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text3 | Usage Frequency | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text4 | Wear Rate | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text5 | Environment | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text6 | Sensitivity | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text7 | Calibration Type | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text8 | Calibration Contact | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text9 | Notes | 📄 text | ✅ | ✅ | ❌ | - | - |
| Text10 | Equipment ID | 📄 text | ✅ | ✅ | ❌ | - | - |
| Variable3 | - | 📝 input | ✅ | ✅ | ❌ | CalibrationTracker_VisibleID | - |
| ArchiveButton* | ArchiveButton | 🔘 button | ✅ | ✅ | ❌ | ArchiveButton | [ArchiveButton%2A.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CalibrationTracker/ObjectMethods/ArchiveButton%2A.4dm) |
| Popup Dropdown List5 | - | 📥 dropdown | ✅ | ✅ | ❌ | EquipmentStatusArray | [Popup Dropdown List5.4dm](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Forms/CalibrationTracker/ObjectMethods/Popup%20Dropdown%20List5.4dm) |
| Text11 | Serial # | 📄 text | ✅ | ✅ | ❌ | - | - |
| Variable5 | - | 📝 input | ✅ | ✅ | ❌ | vSerial | - |
| Variable1 | - | 📝 input | ✅ | ✅ | ❌ | vName | - |
| Text12 | Right click a calibration line to delete it or rename its document | 📄 text | ✅ | ✅ | ❌ | - | - |

#### Page 1

| Name | Title | Type | Enabled | Visible | Enterable | Data Source | Method |
|:-----|:------|:-----|:-------:|:-------:|:---------:|:------------|:-------|
| Text | Select an equipment item to view its calibration information | 📄 text | ✅ | ✅ | ❌ | - | - |

## 🔗 Related Items

### 🗂️ Tables

- [CalibrationEquipment](../Tables/CalibrationEquipment.md) - Data source for CalibrationTracker form
- [CalibrationProcedures](../Tables/CalibrationProcedures.md) - Data source for CalibrationTracker form
- [Calibrations](../Tables/Calibrations.md) - Data source for CalibrationTracker form
- [CalibrationResults](../Tables/CalibrationResults.md) - Data source for CalibrationTracker form

---

*Generated from form.4DForm*
