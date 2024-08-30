[**cli/utils**](../README.md) • **Docs**

***

[near-sdk-js v2.0.0](../../../packages.md) / [cli/utils](../README.md) / validateContract

# Function: validateContract()

> **validateContract**(`contractPath`, `verbose`): `Promise`\<`boolean`\>

Validates the contract by checking that all parameters are initialized in the constructor. Works only for contracts written in TypeScript.

## Parameters

• **contractPath**: `string`

Path to the contract.

• **verbose**: `boolean` = `false`

Whether to print verbose output.

## Returns

`Promise`\<`boolean`\>

## Defined in

[packages/near-sdk-js/src/cli/utils.ts:62](https://github.com/dim-daskalov/near-sdk-js/blob/d72c9c5d6e6863e8c60ad0aa42a57e43d9805f07/packages/near-sdk-js/src/cli/utils.ts#L62)
