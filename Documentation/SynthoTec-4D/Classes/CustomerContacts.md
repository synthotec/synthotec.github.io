---
layout : default
title : CustomerContacts
parent : Classes
---
# CustomerContacts [![GitHub](../../github-mark-white.png)](https://github.com/synthotec/SynthoTec-4D/blob/main/Project/Sources/Classes/CustomerContacts.4dm)

📊 **Overview:** 1 Functions

## 📝 Description

DataClass for customer contact records, storing email addresses and other contact details for individuals at customer accounts. Supports entity migration (linking disabled).

**Extends:** `DataClass`

🕐 *Last updated: 2026-03-09T14:45:29.196Z*

---

## 📑 Table of Contents

- [⚙️ Functions](#functions)
  - **Regular Functions**
    - [getMigrationSettings](#getmigrationsettings) → `Object` 🖥️
- [🔗 Related Items](#related-items)


---

## Functions {#functions}

### Regular Functions

#### getMigrationSettings {#getmigrationsettings}
 `[🖥️ local]`

```4d
Function getMigrationSettings -> Object
```

Returns configuration settings for entity migration (linking disabled for this dataclass)

**Returns:** `Object`

---

## Related Items {#related-items}

### 🗂️ Tables

- [CustomerContacts](../Tables/CustomerContacts.md) - ORDA DataClass class for CustomerContacts table

### � Related Classes

- [CustomerContactsEntity](CustomerContactsEntity.md) - ORDA Entity class for CustomerContacts table

### � Forms

- [%2AMigration](../Forms/%2AMigration.md) - Data source for %2AMigration form
- [CustomerInput](../Forms/CustomerInput.md) - Data source for CustomerInput form
- [CustomerOrders](../Forms/CustomerOrders.md) - Data source for CustomerOrders form

---

*Generated from CustomerContacts.4dm*
