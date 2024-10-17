[**promise**](../README.md) • **Docs**

***

[near-sdk-js v2.0.0](../../packages.md) / [promise](../README.md) / CreateAccount

# Class: CreateAccount

A create account promise action.

## Extends

- [`PromiseAction`](PromiseAction.md)

## Constructors

### new CreateAccount()

> **new CreateAccount**(): [`CreateAccount`](CreateAccount.md)

#### Returns

[`CreateAccount`](CreateAccount.md)

#### Inherited from

[`PromiseAction`](PromiseAction.md).[`constructor`](PromiseAction.md#constructors)

## Methods

### add()

> **add**(`promiseIndex`): `void`

The method that describes how a promise action adds it's _action_ to the promise batch with the provided index.

#### Parameters

• **promiseIndex**: [`PromiseIndex`](../../utils/type-aliases/PromiseIndex.md)

The index of the promise batch to attach the action to.

#### Returns

`void`

#### Overrides

[`PromiseAction`](PromiseAction.md).[`add`](PromiseAction.md#add)

#### Defined in

[packages/near-sdk-js/src/promise.ts:24](https://github.com/dim-daskalov/near-sdk-js/blob/c95f5e9eab115df82feb9d8dca403e7b9c8c9534/packages/near-sdk-js/src/promise.ts#L24)
