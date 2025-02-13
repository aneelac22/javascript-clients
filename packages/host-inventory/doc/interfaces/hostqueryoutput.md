[@redhat-cloud-services/host-inventory-client](../README.md) › [Globals](../globals.md) › [HostQueryOutput](hostqueryoutput.md)

# Interface: HostQueryOutput

A paginated host search query result with host entries and their Inventory metadata.

**`export`** 

**`interface`** HostQueryOutput

## Hierarchy

* **HostQueryOutput**

## Index

### Properties

* [count](hostqueryoutput.md#count)
* [page](hostqueryoutput.md#page)
* [per_page](hostqueryoutput.md#per_page)
* [results](hostqueryoutput.md#results)
* [total](hostqueryoutput.md#total)

## Properties

###  count

• **count**: *number*

*Defined in [packages/host-inventory/api.ts:744](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/host-inventory/api.ts#L744)*

The number of items on the current page

**`memberof`** HostQueryOutput

___

###  page

• **page**: *number*

*Defined in [packages/host-inventory/api.ts:750](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/host-inventory/api.ts#L750)*

The page number

**`memberof`** HostQueryOutput

___

###  per_page

• **per_page**: *number*

*Defined in [packages/host-inventory/api.ts:756](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/host-inventory/api.ts#L756)*

The number of items to return per page

**`memberof`** HostQueryOutput

___

###  results

• **results**: *Array‹[HostOut](hostout.md)›*

*Defined in [packages/host-inventory/api.ts:768](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/host-inventory/api.ts#L768)*

Actual host search query result entries.

**`memberof`** HostQueryOutput

___

###  total

• **total**: *number*

*Defined in [packages/host-inventory/api.ts:762](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/host-inventory/api.ts#L762)*

Total number of items

**`memberof`** HostQueryOutput
