# Accommodation Booking Cancelled

### 

## Javascript Code
```js
window.dataLayerE = window.dataLayerE || [];
dataLayerE.push({ ecommerce: null });  // Clear the previous ecommerce object.
dataLayerE.push({
  "event": "refund",
  "apollo_event": "Accommodation Booking Cancelled",
    "ecommerce": {
        "currency": "<currency>",
        "items": [
            {
                "item_id": "<item_id>",
                "item_name": "<item_name>",
                "lodging_location_id": "<lodging_location_id>",
                "number_of_adults": <number_of_adults>
            }
        ],
        "transaction_id": "<transaction_id>",
        "value": <value>
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|ecommerce.currency|string|The currency, in 3-letter ISO 4217 format.||||||||
|ecommerce.items[n].item_id|string|Item ID \(context-specific\).The product primary ID \(SKU or UPC\)|SKU\_12345|||||||
|ecommerce.items[n].item_name|string|Item Name \(context-specific\).|jeggings|||||||
|ecommerce.items[n].lodging_location_id|string|Captures a unique ID of a physical location such as a store, banking branch, atm, hotel, office, or other.|155, 65588, 987764448|||||||
|ecommerce.items[n].number_of_adults|integer|Count of times that visitors canceled a room booking.|1, 2, 3, 4, 5||||1|||
|ecommerce.transaction_id|string|The unique identifier of a transaction.|T\_12345, 19283j2nm9jdjs|^[a-zA-Z0-9]{6,20}$|6|20||||
|ecommerce.value|number|The monetary value of the event.|7.77, 239.55, 659|||||||

## Attached Notes

<p>11111&nbsp;</p>
<p>&nbsp;</p>
<p>11111</p>
