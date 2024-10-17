[**near-bindgen**](../README.md) • **Docs**

***

[near-sdk-js v2.0.0](../../packages.md) / [near-bindgen](../README.md) / middleware

# Function: middleware()

> **middleware**\<`Arguments`\>(...`middlewares`): `DecoratorFunction`

Tells the SDK to apply an array of passed in middleware to the function execution.

## Type Parameters

• **Arguments** *extends* `any`[]

## Parameters

• ...**middlewares**: `Middleware`\<`Arguments`\>[]

The middlewares to be executed.

## Returns

`DecoratorFunction`

## Defined in

[packages/near-sdk-js/src/near-bindgen.ts:132](https://github.com/dim-daskalov/near-sdk-js/blob/c95f5e9eab115df82feb9d8dca403e7b9c8c9534/packages/near-sdk-js/src/near-bindgen.ts#L132)
