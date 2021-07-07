# Page Load Started

### Page Load Started is part of the page load sequence, including virtual page loads in the case of single page apps, and must be the first event pushed in the page load event sequence.

## Javascript Code
```js
window.appEventData777 = window.appEventData777 || [];
appEventData777.push({
  "event": "Page Load Started",
    "page": {
        "siteName": "<siteName>",
        "siteType": "<siteType>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|siteName|string|Common language used within the business to refer to the website. May be specific County Sites.|Prospecting-EU, Prospecting-US, Member Portal, Shop-CA, Shop-US, Shop-EU|||||||
|siteType|string|Common language description of the site type of purpose. May be used to group siteName.|Prospecting, Shop, Members, Brand|||||||
