{% include_relative _breadcrumb.html current="delete(url,body,var)" %}


### Description
This command is used to send a HTTP DELETE request to perform delete operation with the given url and query string.

To learn about how to utilize the response returned from the target URL, click [here](index.html#http-response).


### Parameters
- **url** \- the target URL
- **body** \- is the payload to be sent to target endpoint.  If not required, use `(empty)` to denote no payload to 
  be sent.
- **var** \- the variable to hold the [response](index.html#http-response)


### Example


### See Also
- [`get(url,queryString,var)`](get(url,queryString,var))
- [`head(url,var)`](head(url,var))
- [`patch(url,body,var)`](patch(url,body,var))
- [`post(url,body,var)`](post(url,body,var))
- [`put(url,body,var)`](put(url,body,var))