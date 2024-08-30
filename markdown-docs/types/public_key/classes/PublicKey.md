[**types/public_key**](../README.md) • **Docs**

***

[near-sdk-js v2.0.0](../../../packages.md) / [types/public\_key](../README.md) / PublicKey

# Class: PublicKey

A abstraction on top of the NEAR public key string.

## Constructors

### new PublicKey()

> **new PublicKey**(`data`): [`PublicKey`](PublicKey.md)

#### Parameters

• **data**: `Uint8Array`

The string you want to create a PublicKey from.

#### Returns

[`PublicKey`](PublicKey.md)

#### Defined in

[packages/near-sdk-js/src/types/public\_key.ts:91](https://github.com/dim-daskalov/near-sdk-js/blob/d72c9c5d6e6863e8c60ad0aa42a57e43d9805f07/packages/near-sdk-js/src/types/public_key.ts#L91)

## Properties

### data

> **data**: `Uint8Array`

The actual value of the public key.

#### Defined in

[packages/near-sdk-js/src/types/public\_key.ts:85](https://github.com/dim-daskalov/near-sdk-js/blob/d72c9c5d6e6863e8c60ad0aa42a57e43d9805f07/packages/near-sdk-js/src/types/public_key.ts#L85)

## Methods

### curveType()

> **curveType**(): [`CurveType`](../enumerations/CurveType.md)

The curve type of the public key.

#### Returns

[`CurveType`](../enumerations/CurveType.md)

#### Defined in

[packages/near-sdk-js/src/types/public\_key.ts:105](https://github.com/dim-daskalov/near-sdk-js/blob/d72c9c5d6e6863e8c60ad0aa42a57e43d9805f07/packages/near-sdk-js/src/types/public_key.ts#L105)

***

### fromString()

> `static` **fromString**(`publicKeyString`): [`PublicKey`](PublicKey.md)

Create a public key from a public key string.

#### Parameters

• **publicKeyString**: `string`

The public key string you want to create a PublicKey from.

#### Returns

[`PublicKey`](PublicKey.md)

#### Defined in

[packages/near-sdk-js/src/types/public\_key.ts:114](https://github.com/dim-daskalov/near-sdk-js/blob/d72c9c5d6e6863e8c60ad0aa42a57e43d9805f07/packages/near-sdk-js/src/types/public_key.ts#L114)
