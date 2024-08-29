[**api**](../README.md) • **Docs**

***

[near-sdk-js v2.0.0](../../packages.md) / [api](../README.md) / promiseBatchActionDeployContract

# Function: promiseBatchActionDeployContract()

> **promiseBatchActionDeployContract**(`promiseIndex`, `code`): `void`

Attach a deploy contract promise action to the NEAR promise index with the provided promise index.

## Parameters

• **promiseIndex**: [`PromiseIndex`](../../utils/type-aliases/PromiseIndex.md)

The index of the promise to attach a deploy contract action to.

• **code**: `Uint8Array`

The WASM byte code of the contract to be deployed.

## Returns

`void`

## Defined in

[packages/near-sdk-js/src/api.ts:583](https://github.com/LimeChain/near-sdk-js/blob/5530eb605b430589e35fde22ec4943fa536f58d1/packages/near-sdk-js/src/api.ts#L583)
