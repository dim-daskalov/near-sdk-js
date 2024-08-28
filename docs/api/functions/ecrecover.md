[**api**](../README.md) • **Docs**

***

[near-sdk-js v2.0.0](../../packages.md) / [api](../README.md) / ecrecover

# Function: ecrecover()

> **ecrecover**(`hash`, `sig`, `v`, `malleabilityFlag`): `Uint8Array` \| `null`

Recovers an ECDSA signer address from a 32-byte message hash and a corresponding
signature along with v recovery byte. Takes in an additional flag to check for
malleability of the signature which is generally only ideal for transactions.

## Parameters

• **hash**: `Uint8Array`

32-byte message hash

• **sig**: `Uint8Array`

signature

• **v**: `number`

number of recovery byte

• **malleabilityFlag**: `number`

whether to check malleability

## Returns

`Uint8Array` \| `null`

64 bytes representing the public key if the recovery was successful.

## Defined in

[packages/near-sdk-js/src/api.ts:908](https://github.com/LimeChain/near-sdk-js/blob/7f4c32d152c77ff1750b2fd1709e062f4bbc3e1e/packages/near-sdk-js/src/api.ts#L908)
