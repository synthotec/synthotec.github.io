---
layout: default
title: EntityMigrationRule ⌛
parent: Classes
---

# EntityMigrationRule

|   |
|:---|
|[**.new**()](#new)<br>|
|[**.overwrite**( *PropertyName* : Text ) : cs.EntityMigrationRule](#overwrite)<br>|
|[**.addFormula**( *Formula* : 4D.Function; *SecondParameter* : Variant; *CheckProperty* : Text ) : cs.EntityMigrationRule](#addformula)<br>|
|[**.fillIfBlank**( *PropertyName* : Text ) : cs.EntityMigrationRule](#fillifblank)<br>|
|[**.addEntity**( *DataClass* : 4D.DataClass; *LocalEntity* : 4D.Entity; *Formula* : 4D.Function; *Sync* : Boolean ) : cs.EntityMigrationRule](#addentity)<br>|
|[**.addCriteria**( *Formula* : 4D.Function ) : cs.EntityMigrationRule](#addcriteria)<br>|
|[**.apply**( *LocalEntity* : 4D.Entity; *RemoteEntity* : 4D.Entity )](#apply)<br>|
|[FormulaObjectCollection : Collection](#formulaobjectcollection)<br>|
|[CriteriaCollection : Collection](#criteriacollection)<br>|


## new()
**.new**()


## overwrite()
**.overwrite**( *PropertyName* : Text ) : cs.EntityMigrationRule

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|PropertyName|Text|->|<Description>|
||cs.EntityMigrationRule|<-|<Description>|

## addFormula()
**.addFormula**( *Formula* : 4D.Function; *SecondParameter* : Variant; *CheckProperty* : Text ) : cs.EntityMigrationRule

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|Formula|4D.Function|->|<Description>|
|SecondParameter|Variant|->|<Description>|
|CheckProperty|Text|->|<Description>|
||cs.EntityMigrationRule|<-|<Description>|

## fillIfBlank()
**.fillIfBlank**( *PropertyName* : Text ) : cs.EntityMigrationRule

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|PropertyName|Text|->|<Description>|
||cs.EntityMigrationRule|<-|<Description>|

## addEntity()
**.addEntity**( *DataClass* : 4D.DataClass; *LocalEntity* : 4D.Entity; *Formula* : 4D.Function; *Sync* : Boolean ) : cs.EntityMigrationRule

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|DataClass|4D.DataClass|->|<Description>|
|LocalEntity|4D.Entity|->|<Description>|
|Formula|4D.Function|->|<Description>|
|Sync|Boolean|->|<Description>|
||cs.EntityMigrationRule|<-|<Description>|

## addCriteria()
**.addCriteria**( *Formula* : 4D.Function ) : cs.EntityMigrationRule

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|Formula|4D.Function|->|<Description>|
||cs.EntityMigrationRule|<-|<Description>|

## apply()
**.apply**( *LocalEntity* : 4D.Entity; *RemoteEntity* : 4D.Entity )

|Parameter|Type|   |Description|
|:---|:---:|:---:|:---:|
|LocalEntity|4D.Entity|->|<Description>|
|RemoteEntity|4D.Entity|->|<Description>|

## FormulaObjectCollection
FormulaObjectCollection : Collection


## CriteriaCollection
CriteriaCollection : Collection

