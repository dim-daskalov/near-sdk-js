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

[packages/near-sdk-js/src/promise.ts:24](https://github.com/dim-daskalov/near-sdk-js/blob/f8f6e35ac266a6f748747b51c0b9a0192677684e/packages/near-sdk-js/src/promise.ts#L24)
