---
layout : default
title : Warehouse
parent : Classes
---
# Warehouse [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Warehouse.4dm)

📊 **Overview:** 8 Functions

**Extends:** `DataClass`

🕐 *Last updated: 2026-01-13T16:04:13.746Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [restExecutePromptFormula](#restexecutepromptformula) (1 param) → `Object`
    - [restExecuteFormula](#restexecuteformula) (1 param) → `Object`
    - [restTest](#resttest) (1 param) → `Object`
    - [restStartPage](#reststartpage) (1 param) → `Object`
    - [restInitialScan](#restinitialscan) (1 param) → `Object`
    - [restDisplayPrinterList](#restdisplayprinterlist) (1 param) → `Object`
    - [restSetLabelPrinter](#restsetlabelprinter) (1 param) → `Object`
    - [restScanTest](#restscantest) (1 param) → `Object`
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### restExecutePromptFormula {#restexecutepromptformula}


```4d
Function restExecutePromptFormula($RestPostDataObject : Object) -> Object
```

Displays a prompt dialog for user input and executes a formula on the result; returns WarehouseViewData with optional redirect

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RestPostDataObject` | `Object` | - | - |

**Returns:** `Object`

---

#### restExecuteFormula {#restexecuteformula}


```4d
Function restExecuteFormula($RestPostDataObject : Object) -> Object
```

Executes a formula with provided parameters and context; returns WarehouseViewData with optional alert or redirect

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RestPostDataObject` | `Object` | - | - |

**Returns:** `Object`

---

#### restTest {#resttest}


```4d
Function restTest($RestPostDataObject : Object) -> Object
```

Test REST endpoint displaying a prompt dialog and showing test data; used for development/debugging

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RestPostDataObject` | `Object` | - | - |

**Returns:** `Object`

---

#### restStartPage {#reststartpage}


```4d
Function restStartPage($RestPostDataObject : Object) -> Object
```

Displays the warehouse app start page with initial UI and scanner setup; entry point for warehouse workflows

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RestPostDataObject` | `Object` | - | - |

**Returns:** `Object`

---

#### restInitialScan {#restinitialscan}


```4d
Function restInitialScan($RestPostDataObject : Object) -> Object
```

Routes scanned barcode to appropriate handler (BoxLabel, Pallet, MaterialStock) or prompts to rescan if invalid

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RestPostDataObject` | `Object` | - | - |

**Returns:** `Object`

---

#### restDisplayPrinterList {#restdisplayprinterlist}


```4d
Function restDisplayPrinterList($RestPostDataObject : Object) -> Object
```

Displays UI to select active label printer from available label printers in system; updates user settings

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RestPostDataObject` | `Object` | - | - |

**Returns:** `Object`

---

#### restSetLabelPrinter {#restsetlabelprinter}


```4d
Function restSetLabelPrinter($RestPostDataObject : Object) -> Object
```

Sets the active label printer for the current staff member; confirms selection and returns to start page

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RestPostDataObject` | `Object` | - | - |

**Returns:** `Object`

---

#### restScanTest {#restscantest}


```4d
Function restScanTest($RestPostDataObject : Object) -> Object
```

Test endpoint for scanner functionality; returns mock data and enables scanner for testing

**Parameters:**

| Name | Type | Optional | Description |
|:-----|:-----|:---------|:------------|
| `$RestPostDataObject` | `Object` | - | - |

**Returns:** `Object`

---

## Related Items {#related-items}

### 🗂️ Tables

- [Warehouse](../Tables/Warehouse.md) - ORDA DataClass class for Warehouse table

---

*Generated from Warehouse.4dm*
