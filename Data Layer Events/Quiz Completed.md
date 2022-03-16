# Quiz Completed

### 

## Javascript Code
```js
window.dataLayerE = window.dataLayerE || [];
dataLayerE.push({ ecommerce: null });  // Clear the previous ecommerce object.
dataLayerE.push({ event_data: null });  // Clear the previous event_data object.
dataLayerE.push({
  "event": "survey_complete",
  "apollo_event": "Quiz Completed",
    "ecommerce": {
        "items": [
            {
                "item_finding_method": "<item_finding_method>"
            }
        ]
    },
    "event_data": {
        "name": "<name>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|ecommerce.items[n].item_finding_method|string|Captures the ID associated with exit links used.||||||||
|event_data.name|string|Captures the human-friendly quiz name.|Floor Chooser, Swim Finder, Movie Decider, My Next Book|||||||




