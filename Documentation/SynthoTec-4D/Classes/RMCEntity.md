---
layout : default
title : RMCEntity
parent : Classes
---
# RMCEntity [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/RMCEntity.4dm)

📊 **Overview:** 2 Functions

**Extends:** `Entity`

🕐 *Last updated: 2026-01-13T16:04:13.310Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [delete](#delete) 🖥️
    - [requestCertificate](#requestcertificate) 🖥️
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### delete {#delete}
 `[🖥️ local]`

```4d
Function delete
```

Deletes this RMC record after checking it hasn't been used in material stock takes or checks

---

#### requestCertificate {#requestcertificate}
 `[🖥️ local]`

```4d
Function requestCertificate
```

Sends an email to the supplier requesting a certificate of analysis for this material batch

---

## Related Items {#related-items}

### 🗂️ Tables

- [RMC](../Tables/RMC.md) - ORDA Entity class for RMC table

### � Forms

- [CreateRMC](../Forms/CreateRMC.md) - Data source for CreateRMC form
- [MaterialManagement](../Forms/MaterialManagement.md) - Data source for MaterialManagement form
- [RMCs](../Forms/RMCs.md) - Data source for RMCs form
- [StockTakeInput](../Forms/StockTakeInput.md) - Data source for StockTakeInput form

---

*Generated from RMCEntity.4dm*
