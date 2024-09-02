[**collections/vector**](../README.md) • **Docs**

***

[near-sdk-js v2.0.0](../../../packages.md) / [collections/vector](../README.md) / VectorIterator

# Class: VectorIterator\<DataType\>

An iterator for the Vector collection.

## Type Parameters

• **DataType**

## Constructors

### new VectorIterator()

> **new VectorIterator**\<`DataType`\>(`vector`, `options`?): [`VectorIterator`](VectorIterator.md)\<`DataType`\>

#### Parameters

• **vector**: [`Vector`](Vector.md)\<`DataType`\>

The vector collection to create an iterator for.

• **options?**: [`GetOptions`](../../../types/collections/interfaces/GetOptions.md)\<`DataType`\>

Options for retrieving and storing data.

#### Returns

[`VectorIterator`](VectorIterator.md)\<`DataType`\>

#### Defined in

[packages/near-sdk-js/src/collections/vector.ts:251](https://github.com/dim-daskalov/near-sdk-js/blob/f8f6e35ac266a6f748747b51c0b9a0192677684e/packages/near-sdk-js/src/collections/vector.ts#L251)

## Methods

### next()

> **next**(): `object`

#### Returns

`object`

##### done

> **done**: `boolean`

##### value

> **value**: `DataType`

#### Defined in

[packages/near-sdk-js/src/collections/vector.ts:256](https://github.com/dim-daskalov/near-sdk-js/blob/f8f6e35ac266a6f748747b51c0b9a0192677684e/packages/near-sdk-js/src/collections/vector.ts#L256)
