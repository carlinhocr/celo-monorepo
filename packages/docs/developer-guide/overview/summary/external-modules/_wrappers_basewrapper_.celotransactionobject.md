# CeloTransactionObject

## Type parameters

▪ **O**

## Hierarchy

* **CeloTransactionObject**

## Index

### Constructors

* [constructor](../classes/_wrappers_basewrapper_.celotransactionobject.md#constructor)

### Properties

* [defaultParams](../classes/_wrappers_basewrapper_.celotransactionobject.md#optional-defaultparams)
* [txo](../classes/_wrappers_basewrapper_.celotransactionobject.md#txo)

### Methods

* [send](../classes/_wrappers_basewrapper_.celotransactionobject.md#send)
* [sendAndWaitForReceipt](../classes/_wrappers_basewrapper_.celotransactionobject.md#sendandwaitforreceipt)

## Constructors

### constructor

+ **new CeloTransactionObject**\(`kit`: [ContractKit](../classes/_kit_.contractkit.md), `txo`: TransactionObject‹O›, `defaultParams?`: [CeloTransactionParams](_wrappers_basewrapper_.md#celotransactionparams)\): [_CeloTransactionObject_](../classes/_wrappers_basewrapper_.celotransactionobject.md)

_Defined in_ [_contractkit/src/wrappers/BaseWrapper.ts:240_](https://github.com/celo-org/celo-monorepo/blob/master/packages/contractkit/src/wrappers/BaseWrapper.ts#L240)

**Parameters:**

| Name | Type |
| :--- | :--- |
| `kit` | [ContractKit](../classes/_kit_.contractkit.md) |
| `txo` | TransactionObject‹O› |
| `defaultParams?` | [CeloTransactionParams](_wrappers_basewrapper_.md#celotransactionparams) |

**Returns:** [_CeloTransactionObject_](../classes/_wrappers_basewrapper_.celotransactionobject.md)

## Properties

### `Optional` defaultParams

• **defaultParams**? : [_CeloTransactionParams_](_wrappers_basewrapper_.md#celotransactionparams)

_Defined in_ [_contractkit/src/wrappers/BaseWrapper.ts:244_](https://github.com/celo-org/celo-monorepo/blob/master/packages/contractkit/src/wrappers/BaseWrapper.ts#L244)

### txo

• **txo**: _TransactionObject‹O›_

_Defined in_ [_contractkit/src/wrappers/BaseWrapper.ts:243_](https://github.com/celo-org/celo-monorepo/blob/master/packages/contractkit/src/wrappers/BaseWrapper.ts#L243)

## Methods

### send

▸ **send**\(`params?`: [CeloTransactionParams](_wrappers_basewrapper_.md#celotransactionparams)\): _Promise‹_[_TransactionResult_](../classes/_utils_tx_result_.transactionresult.md)_›_

_Defined in_ [_contractkit/src/wrappers/BaseWrapper.ts:248_](https://github.com/celo-org/celo-monorepo/blob/master/packages/contractkit/src/wrappers/BaseWrapper.ts#L248)

send the transaction to the chain

**Parameters:**

| Name | Type |
| :--- | :--- |
| `params?` | [CeloTransactionParams](_wrappers_basewrapper_.md#celotransactionparams) |

**Returns:** _Promise‹_[_TransactionResult_](../classes/_utils_tx_result_.transactionresult.md)_›_

### sendAndWaitForReceipt

▸ **sendAndWaitForReceipt**\(`params?`: [CeloTransactionParams](_wrappers_basewrapper_.md#celotransactionparams)\): _Promise‹TransactionReceipt›_

_Defined in_ [_contractkit/src/wrappers/BaseWrapper.ts:253_](https://github.com/celo-org/celo-monorepo/blob/master/packages/contractkit/src/wrappers/BaseWrapper.ts#L253)

send the transaction and waits for the receipt

**Parameters:**

| Name | Type |
| :--- | :--- |
| `params?` | [CeloTransactionParams](_wrappers_basewrapper_.md#celotransactionparams) |

**Returns:** _Promise‹TransactionReceipt›_
