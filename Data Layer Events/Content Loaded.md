# Content Loaded

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({ page_data: null });  // Clear the previous page_data object.
dataLayer.push({
  "event": "Content Loaded",
    "event_data": {
        "content_id": "<content_id>",
        "content_id_merchandising": "<content_id_merchandising>",
        "content_modified_date": "<content_modified_date>"
    },
    "page_data": {
        "content_author": "<content_author>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|content_author|string|The context in which the listing is displayed \(Onsite Search, Curated Assortment,  Navigation\)|Betsy Ross, Ben Franklin, Howard Hughes, Tipper Gore|||||||
|content_id|string|Captures the unique ID of content items \(i.e. article or blog post\).||||||||
|content_id_merchandising|string|Captures the optimization test IDs as concatenated list for active tests.||||||||
|content_modified_date|string|Captures the number of content items displayed in a content listing.|1-1-2020, 2-2-2019|||||||




