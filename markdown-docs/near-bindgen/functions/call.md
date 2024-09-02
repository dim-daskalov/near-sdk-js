[**near-bindgen**](../README.md) • **Docs**

***

[near-sdk-js v2.0.0](../../packages.md) / [near-bindgen](../README.md) / call

# Function: call()

> **call**(`options`): `DecoratorFunction`

Tells the SDK to expose this function as a call function.
Adds the neccessary checks if the function is private or payable.

## Parameters

• **options**

Options to configure the function behaviour.

• **options.payableFunction?**: `boolean`

Whether the function can accept an attached deposit.

• **options.privateFunction?**: `boolean`

Whether the function can be called by other contracts.

## Returns

`DecoratorFunction`

## Defined in

[packages/near-sdk-js/src/near-bindgen.ts:73](https://github.com/dim-daskalov/near-sdk-js/blob/cbf6345c5a6e60ddad31f7dbba6d352a4fea5124/packages/near-sdk-js/src/near-bindgen.ts#L73)
