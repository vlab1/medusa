---
displayed_sidebar: pricingReference
badge:
  variant: orange
  text: Beta
slug: /references/pricing/deleteCurrencies
sidebar_label: deleteCurrencies
---

# deleteCurrencies - Pricing Module Reference

This documentation provides a reference to the deleteCurrencies method. This belongs to the Pricing Module.

This method is used to delete currencies based on their currency code.

## Parameters

- `currencyCodes`: An array of strings, each being a code of a currency to delete.
- `sharedContext`: (optional) An object of type [Context](../../interfaces/Context.md) used to share resources, such as transaction manager, between the application and the module. It accepts the following properties:
	- `enableNestedTransactions`: (optional) a boolean value indicating whether nested transactions are enabled.
	- `isolationLevel`: (optional) A string indicating the isolation level of the context. Possible values are `READ UNCOMMITTED`, `READ COMMITTED`, `REPEATABLE READ`, or `SERIALIZABLE`.
	- `manager`: (optional) An instance of a manager, typically an entity manager, of type `TManager`, which is a typed parameter passed to the context to specify the type of the `manager`.
	- `transactionId`: (optional) a string indicating the ID of the current transaction.
	- `transactionManager`: (optional) An instance of a transaction manager of type `TManager`, which is a typed parameter passed to the context to specify the type of the `transactionManager`.

## Returns

A promise that resolves once the currencies are deleted.

## Example

```ts
import { 
  initialize as initializePricingModule,
} from "@medusajs/pricing"

async function deleteCurrencies () {
  const pricingService = await initializePricingModule()

  await pricingService.deleteCurrencies(["USD"])

}
```
