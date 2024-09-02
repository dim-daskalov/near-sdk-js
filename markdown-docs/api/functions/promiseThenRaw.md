[**api**](../README.md) • **Docs**

***

[near-sdk-js v2.0.0](../../packages.md) / [api](../README.md) / promiseThenRaw

# Function: promiseThenRaw()

> **promiseThenRaw**(`promiseIndex`, `accountId`, `methodName`, `args`, `amount`, `gas`): [`PromiseIndex`](../../utils/type-aliases/PromiseIndex.md)

Attach a callback NEAR promise to be executed after a provided promise.

## Parameters

• **promiseIndex**: [`PromiseIndex`](../../utils/type-aliases/PromiseIndex.md)

The promise after which to call the callback.

• **accountId**: `string`

The account ID of the contract to perform the callback on.

• **methodName**: `string`

The name of the method to call.

• **args**: `Uint8Array`

The arguments to call the method with.

• **amount**: [`NearAmount`](../../utils/type-aliases/NearAmount.md)

The amount of NEAR to attach to the call.

• **gas**: [`NearAmount`](../../utils/type-aliases/NearAmount.md)

The amount of Gas to attach to the call.

## Returns

[`PromiseIndex`](../../utils/type-aliases/PromiseIndex.md)

## Defined in

[packages/near-sdk-js/src/api.ts:484](https://github.com/dim-daskalov/near-sdk-js/blob/7e00e38bf9adddbe759a3d4d474ca9731ec4052b/packages/near-sdk-js/src/api.ts#L484)
