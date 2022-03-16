# Quiz Started

### 

## Javascript Code
```js
window.dataLayerE = window.dataLayerE || [];
dataLayerE.push({ event_data: null });  // Clear the previous event_data object.
dataLayerE.push({
  "event": "survey_start",
  "apollo_event": "Quiz Started",
    "event_data": {
        "name": "<name>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.name|string|Captures the human-friendly quiz name.|Floor Chooser, Swim Finder, Movie Decider, My Next Book|||||||




