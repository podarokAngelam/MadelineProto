---
title: inputMediaPhoto
description: inputMediaPhoto attributes, type and example
---
## Constructor: inputMediaPhoto  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|id|[InputPhoto](../types/InputPhoto.md) | Optional|
|ttl\_seconds|[int](../types/int.md) | Optional|



### Type: [InputMedia](../types/InputMedia.md)


### Example:

```
$inputMediaPhoto = ['_' => 'inputMediaPhoto', 'id' => InputPhoto, 'ttl_seconds' => int];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "inputMediaPhoto", "id": InputPhoto, "ttl_seconds": int}
```


Or, if you're into Lua:  


```
inputMediaPhoto={_='inputMediaPhoto', id=InputPhoto, ttl_seconds=int}

```


