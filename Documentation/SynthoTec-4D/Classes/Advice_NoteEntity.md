---
layout : default
title : Advice_NoteEntity
parent : Classes
---
# Advice_NoteEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/Advice_NoteEntity.4dm)

📊 **Overview:** 4 Functions

## 📝 Description

Entity representing a despatch advice note (delivery note), with support for generating EDI DESADV messages in NTN-SNR format, printing advice notes, and emailing material certificates to customers.

**Extends:** `Entity`

🕐 *Last updated: 2026-03-09T14:45:28.974Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [generateNTNSNR_DESADV](#generatentnsnr_desadv) 🖥️
    - [print](#print) 🖥️
    - [tryEmailMaterialCertificates](#tryemailmaterialcertificates) 🖥️
    - [cancel](#cancel) → `$Cancelled : Boolean` 🖥️
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### generateNTNSNR_DESADV {#generatentnsnr_desadv}
 `[🖥️ local]`

```4d
Function generateNTNSNR_DESADV
```

Generates an EDI DESADV (Despatch Advice) message in NTN-SNR format for this advice note

---

#### print {#print}
 `[🖥️ local]`

```4d
Function print
```

Prints advice note via Print Advice dialog; generates NTN-SNR DESADV file if customer requires EDI format

---

#### tryEmailMaterialCertificates {#tryemailmaterialcertificates}
 `[🖥️ local]`

```4d
Function tryEmailMaterialCertificates
```

Sends material certificates of analysis (RMC CofA files) to current user if customer requires them; shows confirmation dialog

---

#### cancel {#cancel}
 `[🖥️ local]`

```4d
Function cancel -> $Cancelled : Boolean
```

Cancels advice note by cancelling all associated CoCs; returns true if successful, false if any CoC cancel fails

**Returns:** `Boolean`

---

## Related Items {#related-items}

### 🗂️ Tables

- [Advice_Note](../Tables/Advice_Note.md) - ORDA Entity class for Advice_Note table

### � Forms

- [ConsignmentCallOff](../Forms/ConsignmentCallOff.md) - Data source for ConsignmentCallOff form
- [OrderDelivery](../Forms/OrderDelivery.md) - Data source for OrderDelivery form
- [PalletDespatchList](../Forms/PalletDespatchList.md) - Data source for PalletDespatchList form

---

*Generated from Advice_NoteEntity.4dm*
