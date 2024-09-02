[**api**](../README.md) • **Docs**

***

[near-sdk-js v2.0.0](../../packages.md) / [api](../README.md) / promiseBatchActionFunctionCallWeight

# Function: promiseBatchActionFunctionCallWeight()

> **promiseBatchActionFunctionCallWeight**(`promiseIndex`, `methodName`, `args`, `amount`, `gas`, `weight`): `void`

Attach a function call with weight promise action to the NEAR promise index with the provided promise index.

## Parameters

• **promiseIndex**: [`PromiseIndex`](../../utils/type-aliases/PromiseIndex.md)

The index of the promise to attach a function call with weight action to.

• **methodName**: `string`

The name of the method to be called.

• **args**: `string`

The utf-8 string arguments to call the method with.

• **amount**: [`NearAmount`](../../utils/type-aliases/NearAmount.md)

The amount of NEAR to attach to the call.

• **gas**: [`NearAmount`](../../utils/type-aliases/NearAmount.md)

The amount of Gas to attach to the call.

• **weight**: `bigint`

The weight of unused Gas to use.

## Returns

`void`

## Defined in

[packages/near-sdk-js/src/api.ts:792](https://github.com/dim-daskalov/near-sdk-js/blob/306b0e9106179b8fa9fa5a5e519a844314d6230e/packages/near-sdk-js/src/api.ts#L792)
