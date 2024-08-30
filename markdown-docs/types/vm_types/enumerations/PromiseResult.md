[**types/vm_types**](../README.md) • **Docs**

***

[near-sdk-js v2.0.0](../../../packages.md) / [types/vm\_types](../README.md) / PromiseResult

# Enumeration: PromiseResult

A Promise result in near can be one of:
- NotReady = 0 - the promise you are specifying is still not ready, not yet failed nor successful.
- Successful = 1 - the promise has been successfully executed and you can retrieve the resulting value.
- Failed = 2 - the promise execution has failed.

## Enumeration Members

### Failed

> **Failed**: `2`

#### Defined in

[packages/near-sdk-js/src/types/vm\_types.ts:19](https://github.com/dim-daskalov/near-sdk-js/blob/d72c9c5d6e6863e8c60ad0aa42a57e43d9805f07/packages/near-sdk-js/src/types/vm_types.ts#L19)

***

### NotReady

> **NotReady**: `0`

#### Defined in

[packages/near-sdk-js/src/types/vm\_types.ts:17](https://github.com/dim-daskalov/near-sdk-js/blob/d72c9c5d6e6863e8c60ad0aa42a57e43d9805f07/packages/near-sdk-js/src/types/vm_types.ts#L17)

***

### Successful

> **Successful**: `1`

#### Defined in

[packages/near-sdk-js/src/types/vm\_types.ts:18](https://github.com/dim-daskalov/near-sdk-js/blob/d72c9c5d6e6863e8c60ad0aa42a57e43d9805f07/packages/near-sdk-js/src/types/vm_types.ts#L18)
