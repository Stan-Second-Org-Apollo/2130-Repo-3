# Portal Objects Displayed

### This event is part of the page load sequence, including virtual page loads in the case of single page apps, and must be pushed between the `Page Load Started` and `Page Load Completed` events.

## Javascript Code
```js
window.appEventData777 = window.appEventData777 || [];
appEventData777.push({
  "event": "Portal Objects Displayed",
    "portalDisplayed": {
        "portalObject": [
            {
                "portalObjectId": "<portalObjectId>"
            }
        ]
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|portalObjectId|string|Unique identifier of a portal object|My Accounts, Transactions, Messages, My Reports|||||||