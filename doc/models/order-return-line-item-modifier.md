## Order Return Line Item Modifier

A line item modifier being returned.

### Structure

`OrderReturnLineItemModifier`

### Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `Uid` | `string` | Optional | Unique ID that identifies the return modifier only within this order. |
| `SourceModifierUid` | `string` | Optional | `uid` of the Modifier from the LineItem from the Order which contains the<br>original sale of this line item modifier. |
| `CatalogObjectId` | `string` | Optional | The catalog object id referencing [CatalogModifier](#type-catalogmodifier). |
| `Name` | `string` | Optional | The name of the item modifier. |
| `BasePriceMoney` | [`Models.Money`](/doc/models/money.md) | Optional | Represents an amount of money. `Money` fields can be signed or unsigned.<br>Fields that do not explicitly define whether they are signed or unsigned are<br>considered unsigned and can only hold positive amounts. For signed fields, the<br>sign of the value indicates the purpose of the money transfer. See<br>[Working with Monetary Amounts](https://developer.squareup.com/docs/build-basics/working-with-monetary-amounts)<br>for more information. |
| `TotalPriceMoney` | [`Models.Money`](/doc/models/money.md) | Optional | Represents an amount of money. `Money` fields can be signed or unsigned.<br>Fields that do not explicitly define whether they are signed or unsigned are<br>considered unsigned and can only hold positive amounts. For signed fields, the<br>sign of the value indicates the purpose of the money transfer. See<br>[Working with Monetary Amounts](https://developer.squareup.com/docs/build-basics/working-with-monetary-amounts)<br>for more information. |

### Example (as JSON)

```json
{
  "uid": null,
  "source_modifier_uid": null,
  "catalog_object_id": null,
  "name": null,
  "base_price_money": null,
  "total_price_money": null
}
```
