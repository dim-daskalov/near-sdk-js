[**api**](../README.md) • **Docs**

***

[near-sdk-js v2.0.0](../../packages.md) / [api](../README.md) / altBn128G1Multiexp

# Function: altBn128G1Multiexp()

> **altBn128G1Multiexp**(`value`): `Uint8Array`

Computes multiexp on alt_bn128 curve using Pippenger's algorithm \sum_i
mul_i g_{1 i} should be equal result.

## Parameters

• **value**: `Uint8Array`

equence of (g1:G1, fr:Fr), where
G1 is point (x:Fq, y:Fq) on alt_bn128,
alt_bn128 is Y^2 = X^3 + 3 curve over Fq.
`value` is encoded as packed, little-endian
`[((u256, u256), u256)]` slice.

## Returns

`Uint8Array`

multi exp sum

## Defined in

[packages/near-sdk-js/src/api.ts:978](https://github.com/dim-daskalov/near-sdk-js/blob/d4e93da29f43ee9e262e0388b0ccb37cc87b3bae/packages/near-sdk-js/src/api.ts#L978)
