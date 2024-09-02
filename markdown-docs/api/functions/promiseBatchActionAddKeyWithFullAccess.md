[**api**](../README.md) • **Docs**

***

[near-sdk-js v2.0.0](../../packages.md) / [api](../README.md) / promiseBatchActionAddKeyWithFullAccess

# Function: promiseBatchActionAddKeyWithFullAccess()

> **promiseBatchActionAddKeyWithFullAccess**(`promiseIndex`, `publicKey`, `nonce`): `void`

Attach a add full access key promise action to the NEAR promise index with the provided promise index.

## Parameters

• **promiseIndex**: [`PromiseIndex`](../../utils/type-aliases/PromiseIndex.md)

The index of the promise to attach a add full access key action to.

• **publicKey**: `Uint8Array`

The public key to add as a full access key.

• **nonce**: `number` \| `bigint`

The nonce to use.

## Returns

`void`

## Defined in

[packages/near-sdk-js/src/api.ts:682](https://github.com/dim-daskalov/near-sdk-js/blob/7e00e38bf9adddbe759a3d4d474ca9731ec4052b/packages/near-sdk-js/src/api.ts#L682)
