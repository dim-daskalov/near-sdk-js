[**api**](../README.md) • **Docs**

***

[near-sdk-js v2.0.0](../../packages.md) / [api](../README.md) / promiseBatchActionFunctionCall

# Function: promiseBatchActionFunctionCall()

> **promiseBatchActionFunctionCall**(`promiseIndex`, `methodName`, `args`, `amount`, `gas`): `void`

Attach a function call promise action to the NEAR promise index with the provided promise index.

## Parameters

• **promiseIndex**: [`PromiseIndex`](../../utils/type-aliases/PromiseIndex.md)

The index of the promise to attach a function call action to.

• **methodName**: `string`

The name of the method to be called.

• **args**: `string`

The utf-8 string arguments to call the method with.

• **amount**: [`NearAmount`](../../utils/type-aliases/NearAmount.md)

The amount of NEAR to attach to the call.

• **gas**: [`NearAmount`](../../utils/type-aliases/NearAmount.md)

The amount of Gas to attach to the call.

## Returns

`void`

## Defined in

[packages/near-sdk-js/src/api.ts:627](https://github.com/dim-daskalov/near-sdk-js/blob/7e00e38bf9adddbe759a3d4d474ca9731ec4052b/packages/near-sdk-js/src/api.ts#L627)
