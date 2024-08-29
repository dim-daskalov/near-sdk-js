[**api**](../README.md) • **Docs**

***

[near-sdk-js v2.0.0](../../packages.md) / [api](../README.md) / promiseCreate

# Function: promiseCreate()

> **promiseCreate**(`accountId`, `methodName`, `args`, `amount`, `gas`): [`PromiseIndex`](../../utils/type-aliases/PromiseIndex.md)

Create a NEAR promise call to a contract on the blockchain.

## Parameters

• **accountId**: `string`

The account ID of the target contract.

• **methodName**: `string`

The name of the method to be called.

• **args**: `string`

The utf-8 string arguments to call the method with.

• **amount**: [`NearAmount`](../../utils/type-aliases/NearAmount.md)

The amount of NEAR attached to the call.

• **gas**: [`NearAmount`](../../utils/type-aliases/NearAmount.md)

The amount of Gas attached to the call.

## Returns

[`PromiseIndex`](../../utils/type-aliases/PromiseIndex.md)

## Defined in

[packages/near-sdk-js/src/api.ts:464](https://github.com/LimeChain/near-sdk-js/blob/7f4c32d152c77ff1750b2fd1709e062f4bbc3e1e/packages/near-sdk-js/src/api.ts#L464)
