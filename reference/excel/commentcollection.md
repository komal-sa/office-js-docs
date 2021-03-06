# CommentCollection Object (JavaScript API for Excel)

Represents a collection of comment objects that are part of the workbook.

## Properties

| Property	   | Type	|Description| Req. Set|
|:---------------|:--------|:----------|:----|
|items|[Comment[]](comment.md)|A collection of comment objects. Read-only.|[beta](../requirement-sets/excel-api-requirement-sets.md)|

_See property access [examples.](#property-access-examples)_

## Relationships
None


## Methods

| Method		   | Return Type	|Description| Req. Set|
|:---------------|:--------|:----------|:----|
|[add(content: string, cellAddress: object, contentType: ContentType)](#addcontent-string-celladdress-object-contenttype-contenttype)|[Comment](comment.md)|Creates a new comment(comment thread) based on the cell location and content. Invalid argument will be thrown if the location is larger than one cell.|[beta](../requirement-sets/excel-api-requirement-sets.md)|
|[getCount()](#getcount)|int|Gets the number of comments in the collection.|[beta](../requirement-sets/excel-api-requirement-sets.md)|
|[getItem(commentId: string)](#getitemcommentid-string)|[Comment](comment.md)|Returns a comment identified by its ID. Read-only.|[beta](../requirement-sets/excel-api-requirement-sets.md)|
|[getItemAt(index: number)](#getitematindex-number)|[Comment](comment.md)|Gets a comment based on its position in the collection.|[beta](../requirement-sets/excel-api-requirement-sets.md)|
|[getItemByCell(cellAddress: object)](#getitembycellcelladdress-object)|[Comment](comment.md)|Gets a comment on the specific cell in the collection.|[beta](../requirement-sets/excel-api-requirement-sets.md)|
|[getItemByReplyId(replyId: string)](#getitembyreplyidreplyid-string)|[Comment](comment.md)|Gets a comment related to its reply ID in the collection.|[beta](../requirement-sets/excel-api-requirement-sets.md)|

## Method Details


### add(content: string, cellAddress: object, contentType: ContentType)
Creates a new comment(comment thread) based on the cell location and content. Invalid argument will be thrown if the location is larger than one cell.

#### Syntax
```js
commentCollectionObject.add(content, cellAddress, contentType);
```

#### Parameters
| Parameter	   | Type	|Description|
|:---------------|:--------|:----------|
|content|string|The comment content.|
|cellAddress|object|Cell to insert comment to. May be an Excel Range object, or a string. If string, must contain the full address, including the sheet name|
|contentType|ContentType|Optional. Optional. Type of the comment content|

#### Returns
[Comment](comment.md)

### getCount()
Gets the number of comments in the collection.

#### Syntax
```js
commentCollectionObject.getCount();
```

#### Parameters
None

#### Returns
int

### getItem(commentId: string)
Returns a comment identified by its ID. Read-only.

#### Syntax
```js
commentCollectionObject.getItem(commentId);
```

#### Parameters
| Parameter	   | Type	|Description|
|:---------------|:--------|:----------|
|commentId|string|The identifier for the comment.|

#### Returns
[Comment](comment.md)

### getItemAt(index: number)
Gets a comment based on its position in the collection.

#### Syntax
```js
commentCollectionObject.getItemAt(index);
```

#### Parameters
| Parameter	   | Type	|Description|
|:---------------|:--------|:----------|
|index|number|Index value of the object to be retrieved. Zero-indexed.|

#### Returns
[Comment](comment.md)

### getItemByCell(cellAddress: object)
Gets a comment on the specific cell in the collection.

#### Syntax
```js
commentCollectionObject.getItemByCell(cellAddress);
```

#### Parameters
| Parameter	   | Type	|Description|
|:---------------|:--------|:----------|
|cellAddress|object|Cell which the comment is on. May be an Excel Range object, or a string. If string, must contain the full address, including the sheet name|

#### Returns
[Comment](comment.md)

### getItemByReplyId(replyId: string)
Gets a comment related to its reply ID in the collection.

#### Syntax
```js
commentCollectionObject.getItemByReplyId(replyId);
```

#### Parameters
| Parameter	   | Type	|Description|
|:---------------|:--------|:----------|
|replyId|string|The identifier of comment reply.|

#### Returns
[Comment](comment.md)
