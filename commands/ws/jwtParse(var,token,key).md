---
title: ws &raquo; jwtParse(var,token,key)
parent: ws
tags: command csv
comments: true
---


### Description
This command parses the the JWT Token to get the payload with provided digitally signed key, and stores it to `var`.


### Parameters
- **var** \- the data variable to hold the parsed JWT Token
- **token** \- the JWT Token for the content that is to parsed
- **key** \- JWT secret key


### Example
**Script**:<br/>
![](image/jwtParse_01.png)

**Result**:<br/>
![](image/jwtParse_02.png)


### See Also
- [`delete(url,body,var)`](delete(url,body,var))
- [`put(url,body,var)`](put(url,body,var))