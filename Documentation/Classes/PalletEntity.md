# PalletEntity

**Extends:** `Entity`

## Table of Contents

### Functions

- [NetWeightKg() [getter]](#netweightkg)
- [GrossWeightKg() [getter]](#grossweightkg)
- [createPrintJob()](#createprintjob)
- [getWorksOrderCollection()](#getworksordercollection)
- [getTotalQuantity()](#gettotalquantity)
- [getTotalBoxes()](#gettotalboxes)
- [QRObject() [getter]](#qrobject)
- [generateQR()](#generateqr)
- [getStockListBoxObject()](#getstocklistboxobject)
- [getMigrationRules()](#getmigrationrules)
- [syncMigrationSelections()](#syncmigrationselections)
- [HasMigrationID() [getter]](#hasmigrationid)
- [transfer()](#transfer)

---

## Functions

### NetWeightKg {#netweightkg}
 `[local]` `[getter]`

```4d
Function NetWeightKg -> Real
```

**Returns:** `Real`

---

### GrossWeightKg {#grossweightkg}
 `[local]` `[getter]`

```4d
Function GrossWeightKg -> Real
```

**Returns:** `Real`

---

### createPrintJob {#createprintjob}


```4d
Function createPrintJob($StaffID : Integer; $PrinterID : Integer) -> Boolean
```

**Returns:** `Boolean`

---

### getWorksOrderCollection {#getworksordercollection}


```4d
Function getWorksOrderCollection -> Collection
```

**Returns:** `Collection`

---

### getTotalQuantity {#gettotalquantity}


```4d
Function getTotalQuantity($WorksOrderEntity : Integer) -> Integer
```

**Returns:** `Integer`

---

### getTotalBoxes {#gettotalboxes}


```4d
Function getTotalBoxes($WorksOrderEntity : Integer) -> Integer
```

**Returns:** `Integer`

---

### QRObject {#qrobject}
 `[getter]`

```4d
Function QRObject -> Object
```

**Returns:** `Object`

---

### generateQR {#generateqr}
 `[local]`

```4d
Function generateQR -> Picture
```

**Returns:** `Picture`

---

### getStockListBoxObject {#getstocklistboxobject}
 `[local]`

```4d
Function getStockListBoxObject -> Object
```

**Returns:** `Object`

---

### getMigrationRules {#getmigrationrules}
 `[local]`

```4d
Function getMigrationRules($RemoteEntity : cs.PalletEntity) -> Collection
```

**Returns:** `Collection`

---

### syncMigrationSelections {#syncmigrationselections}
 `[local]`

```4d
Function syncMigrationSelections($RemoteEntity : cs.PalletEntity)
```

---

### HasMigrationID {#hasmigrationid}
 `[local]` `[getter]`

```4d
Function HasMigrationID -> Boolean
```

**Returns:** `Boolean`

---

### transfer {#transfer}
 `[local]`

```4d
Function transfer($ToLocation : Integer) -> Boolean
```

**Returns:** `Boolean`

---

---

*Generated from PalletEntity.4dm*
*Last updated: 2025-11-12T17:04:22.017Z*
