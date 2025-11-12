# PackagingCatsEntity

**Extends:** `Entity`

## Table of Contents

### Functions

- [getMigrationRules()](#getmigrationrules)
- [syncMigrationSelections()](#syncmigrationselections)

---

## Functions

### getMigrationRules {#getmigrationrules}
 `[local]`

```4d
Function getMigrationRules($RemoteEntity : cs.PackagingCatsEntity) -> Collection
```

**Returns:** `Collection`

---

### syncMigrationSelections {#syncmigrationselections}
 `[local]`

```4d
Function syncMigrationSelections($RemoteEntity : cs.PackagingCatsEntity)
```

var $EntityMigration:=cs.EntityMigration.new(ds.Supplies; $RemoteEntity.SuppliesSelection)

---

---

*Generated from PackagingCatsEntity.4dm*
*Last updated: 2025-11-12T17:04:21.912Z*
