[**api**](../README.md) • **Docs**

***

[near-sdk-js v2.0.0](../../packages.md) / [api](../README.md) / promiseBatchActionStake

# Function: promiseBatchActionStake()

> **promiseBatchActionStake**(`promiseIndex`, `amount`, `publicKey`): `void`

Attach a stake promise action to the NEAR promise index with the provided promise index.

## Parameters

• **promiseIndex**: [`PromiseIndex`](../../utils/type-aliases/PromiseIndex.md)

The index of the promise to attach a stake action to.

• **amount**: [`NearAmount`](../../utils/type-aliases/NearAmount.md)

The amount of NEAR to stake.

• **publicKey**: `Uint8Array`

The public key with which to stake.

## Returns

`void`

## Defined in

[packages/near-sdk-js/src/api.ts:663](https://github.com/dim-daskalov/near-sdk-js/blob/d4e93da29f43ee9e262e0388b0ccb37cc87b3bae/packages/near-sdk-js/src/api.ts#L663)
