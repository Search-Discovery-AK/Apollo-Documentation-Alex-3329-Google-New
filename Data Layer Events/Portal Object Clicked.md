# Portal Object Clicked

### 

## Javascript Code
```js
window.dataLayerE = window.dataLayerE || [];
dataLayerE.push({ event_data: null });  // Clear the previous event_data object.
dataLayerE.push({
  "event": "select_component",
  "apollo_event": "Portal Object Clicked",
    "event_data": {
        "identifier": "<identifier>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.identifier|string|Captures the name or ID of portal \(intranet\) objects. Objects are typically tiles or boxes.|My Accounts, Transactions, Messages, My Reports|||||||




