[**api**](../README.md) • **Docs**

***

[near-sdk-js v2.0.0](../../packages.md) / [api](../README.md) / promiseCreateRaw

# Function: promiseCreateRaw()

> **promiseCreateRaw**(`accountId`, `methodName`, `args`, `amount`, `gas`): [`PromiseIndex`](../../utils/type-aliases/PromiseIndex.md)

Create a NEAR promise call to a contract on the blockchain.

## Parameters

• **accountId**: `string`

The account ID of the target contract.

• **methodName**: `string`

The name of the method to be called.

• **args**: `Uint8Array`

The arguments to call the method with.

• **amount**: [`NearAmount`](../../utils/type-aliases/NearAmount.md)

The amount of NEAR attached to the call.

• **gas**: [`NearAmount`](../../utils/type-aliases/NearAmount.md)

The amount of Gas attached to the call.

## Returns

[`PromiseIndex`](../../utils/type-aliases/PromiseIndex.md)

## Defined in

[packages/near-sdk-js/src/api.ts:439](https://github.com/dim-daskalov/near-sdk-js/blob/7e00e38bf9adddbe759a3d4d474ca9731ec4052b/packages/near-sdk-js/src/api.ts#L439)
