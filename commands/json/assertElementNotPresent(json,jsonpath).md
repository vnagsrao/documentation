---
title: json &raquo; assertElementNotPresent(json,jsonpath)
parent: json
tags: command json jsonpath
comments: true
---
{% include _breadcrumb_command.html %}


### Description
This command asserts the given JSON element as described via `jsonpath` is not present in `json`.


### Parameters
- **json** - JSON content or file
- **jsopath** - the path to the JSON element in question


### Example
**Book Store Data in JSON**<br/>
![bookStoreData](image/bookStoreData.png)

Script:<br/>
![script](image/assertElementNotPresent_01.png)

Result:<br/>
![output](image/assertElementNotPresent_02.png)

