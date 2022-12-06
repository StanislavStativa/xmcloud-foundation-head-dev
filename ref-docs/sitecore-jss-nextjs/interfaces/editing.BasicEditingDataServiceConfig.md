[@sitecore-jss/sitecore-jss-nextjs](../README.md) / [editing](../modules/editing.md) / BasicEditingDataServiceConfig

# Interface: BasicEditingDataServiceConfig

[editing](../modules/editing.md).BasicEditingDataServiceConfig

## Table of contents

### Properties

- [editingDataCache](editing.BasicEditingDataServiceConfig.md#editingdatacache)

## Properties

### editingDataCache

• `Optional` **editingDataCache**: [`EditingDataCache`](editing.EditingDataCache.md)

An instance of the `EditingDataCache` implementation to use.
By default, this is `editingDataDiskCache` (an `EditingDataDiskCache` singleton).

**`default`** editingDataDiskCache

**`see`** EditingDataCache

**`see`** EditingDataDiskCache

#### Defined in

[sitecore-jss-nextjs/src/editing/editing-data-service.ts:59](https://github.com/Sitecore/jss/blob/f3aaeea83/packages/sitecore-jss-nextjs/src/editing/editing-data-service.ts#L59)