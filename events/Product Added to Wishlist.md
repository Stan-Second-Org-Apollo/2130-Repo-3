# Product Added to Wishlist

### 

## Javascript Code
```js
window.appEventData777 = window.appEventData777 || [];
appEventData777.push({
  "event": "Product Added to Wishlist",
    "eventDetails": {
        "multiAdditions": "<multiAdditions>"
    },
    "product": [
        {
            "productInfo": {
                "productID": "<productID>"
            }
        }
    ]
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|multiAdditions|boolean|Flag indicating whether multilple products where added to carts, wishlists, registries, etc.|true, false|||||||
|productID|string|Unique Identifier of a product or offering.  Must match the format of back-end systems if used as a key for import of product meta data. Most often, one level above SKU for products with SKU variants. |155, 65588, 987764448|||||||
