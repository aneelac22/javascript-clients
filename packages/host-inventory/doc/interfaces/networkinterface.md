[@redhat-cloud-services/host-inventory-client](../README.md) › [Globals](../globals.md) › [NetworkInterface](networkinterface.md)

# Interface: NetworkInterface

Representation of one network interface

**`export`** 

**`interface`** NetworkInterface

## Hierarchy

* **NetworkInterface**

## Index

### Properties

* [ipv4_addresses](networkinterface.md#optional-ipv4_addresses)
* [ipv6_addresses](networkinterface.md#optional-ipv6_addresses)
* [mac_address](networkinterface.md#optional-mac_address)
* [mtu](networkinterface.md#optional-mtu)
* [name](networkinterface.md#optional-name)
* [state](networkinterface.md#optional-state)
* [type](networkinterface.md#optional-type)

## Properties

### `Optional` ipv4_addresses

• **ipv4_addresses**? : *Array‹string›*

*Defined in [packages/host-inventory/api.ts:838](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/host-inventory/api.ts#L838)*

**`memberof`** NetworkInterface

___

### `Optional` ipv6_addresses

• **ipv6_addresses**? : *Array‹string›*

*Defined in [packages/host-inventory/api.ts:844](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/host-inventory/api.ts#L844)*

**`memberof`** NetworkInterface

___

### `Optional` mac_address

• **mac_address**? : *string*

*Defined in [packages/host-inventory/api.ts:856](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/host-inventory/api.ts#L856)*

MAC address (with or without colons)

**`memberof`** NetworkInterface

___

### `Optional` mtu

• **mtu**? : *number*

*Defined in [packages/host-inventory/api.ts:850](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/host-inventory/api.ts#L850)*

MTU (Maximum transmission unit)

**`memberof`** NetworkInterface

___

### `Optional` name

• **name**? : *string*

*Defined in [packages/host-inventory/api.ts:862](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/host-inventory/api.ts#L862)*

Name of interface

**`memberof`** NetworkInterface

___

### `Optional` state

• **state**? : *string*

*Defined in [packages/host-inventory/api.ts:868](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/host-inventory/api.ts#L868)*

Interface state (UP, DOWN, UNKNOWN)

**`memberof`** NetworkInterface

___

### `Optional` type

• **type**? : *string*

*Defined in [packages/host-inventory/api.ts:874](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/host-inventory/api.ts#L874)*

Interface type (ether, loopback)

**`memberof`** NetworkInterface
