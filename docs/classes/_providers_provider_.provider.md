

# Hierarchy

**Provider**

↳  [JsonRpcProvider](_providers_json_rpc_provider_.jsonrpcprovider.md)

# Methods

<a id="getnetwork"></a>

## `<Abstract>` getNetwork

▸ **getNetwork**(): `Promise`<[Network](../modules/_utils_network_.md#network)>

*Defined in [providers/provider.ts:26](https://github.com/nearprotocol/nearlib/blob/b1675ba/src.ts/providers/provider.ts#L26)*

**Returns:** `Promise`<[Network](../modules/_utils_network_.md#network)>

___
<a id="query"></a>

## `<Abstract>` query

▸ **query**(path: *`string`*, data: *`string`*): `Promise`<`any`>

*Defined in [providers/provider.ts:29](https://github.com/nearprotocol/nearlib/blob/b1675ba/src.ts/providers/provider.ts#L29)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| path | `string` |
| data | `string` |

**Returns:** `Promise`<`any`>

___
<a id="sendtransaction"></a>

## `<Abstract>` sendTransaction

▸ **sendTransaction**(signedTransaction: *`SignedTransaction`*): `Promise`<[FinalTransactionResult](../modules/_providers_provider_.md#finaltransactionresult)>

*Defined in [providers/provider.ts:28](https://github.com/nearprotocol/nearlib/blob/b1675ba/src.ts/providers/provider.ts#L28)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| signedTransaction | `SignedTransaction` |

**Returns:** `Promise`<[FinalTransactionResult](../modules/_providers_provider_.md#finaltransactionresult)>

___
