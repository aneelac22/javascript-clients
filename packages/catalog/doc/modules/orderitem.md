[@redhat-cloud-services/catalog-client](../README.md) > [OrderItem](../modules/orderitem.md)

# Module: OrderItem

*__export__*: 

*__namespace__*: OrderItem

## Index

### Enumerations

* [StateEnum](../enums/orderitem.stateenum.md)

### Properties

* [completedAt](orderitem.md#completedat)
* [count](orderitem.md#count)
* [createdAt](orderitem.md#createdat)
* [id](orderitem.md#id)
* [orderedAt](orderitem.md#orderedat)
* [owner](orderitem.md#owner)
* [portfolioItemId](orderitem.md#portfolioitemid)
* [providerControlParameters](orderitem.md#providercontrolparameters)
* [serviceParameters](orderitem.md#serviceparameters)
* [servicePlanRef](orderitem.md#serviceplanref)
* [state](orderitem.md#state)
* [updatedAt](orderitem.md#updatedat)

---

## Properties

<a id="completedat"></a>

### `<Optional>` completedAt

**● completedAt**: *`Date`*

*Defined in api.ts:278*

*__type__*: {Date}

*__memberof__*: OrderItem

___
<a id="count"></a>

###  count

**● count**: *`number`*

*Defined in api.ts:230*

*__type__*: {number}

*__memberof__*: OrderItem

___
<a id="createdat"></a>

### `<Optional>` createdAt

**● createdAt**: *`Date`*

*Defined in api.ts:266*

*__type__*: {Date}

*__memberof__*: OrderItem

___
<a id="id"></a>

### `<Optional>` id

**● id**: *`string`*

*Defined in api.ts:224*

*__type__*: {string}

*__memberof__*: OrderItem

___
<a id="orderedat"></a>

### `<Optional>` orderedAt

**● orderedAt**: *`Date`*

*Defined in api.ts:272*

*__type__*: {Date}

*__memberof__*: OrderItem

___
<a id="owner"></a>

### `<Optional>` owner

**● owner**: *`string`*

*Defined in api.ts:290*

*__type__*: {string}

*__memberof__*: OrderItem

___
<a id="portfolioitemid"></a>

###  portfolioItemId

**● portfolioItemId**: *`string`*

*Defined in api.ts:254*

Stores the Portfolio Item ID.

*__type__*: {string}

*__memberof__*: OrderItem

___
<a id="providercontrolparameters"></a>

###  providerControlParameters

**● providerControlParameters**: *`any`*

*Defined in api.ts:242*

The provider specific parameters needed to provision this service. This might include namespaces, special keys.

*__type__*: {any}

*__memberof__*: OrderItem

___
<a id="serviceparameters"></a>

###  serviceParameters

**● serviceParameters**: *`any`*

*Defined in api.ts:236*

*__type__*: {any}

*__memberof__*: OrderItem

___
<a id="serviceplanref"></a>

###  servicePlanRef

**● servicePlanRef**: *`string`*

*Defined in api.ts:248*

Stores the service plan ref from the Topology Service.

*__type__*: {string}

*__memberof__*: OrderItem

___
<a id="state"></a>

### `<Optional>` state

**● state**: *[StateEnum](../enums/orderitem.stateenum.md)*

*Defined in api.ts:260*

Current state of this order item.

*__type__*: {string}

*__memberof__*: OrderItem

___
<a id="updatedat"></a>

### `<Optional>` updatedAt

**● updatedAt**: *`Date`*

*Defined in api.ts:284*

*__type__*: {Date}

*__memberof__*: OrderItem

___
