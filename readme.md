# Intro to AJAX

## 🔬 Research!

In your squads research and answer the following questions:

### What does the acronym AJAX stand for?

```
- Asynchronous JavaScript and XML

[Source](https://developer.mozilla.org/en-US/docs/AJAX/Getting_Started)

```

### What is an XMLHttpRequest?

```
- 'XHR'

- An API in the form of an object whose methods transfer data between a web browser and web server 

- Can be used to request data from a web server

- Benefits: 
    - Update a web page without reloading the page
    - Request data from a server - after the page has loaded
    - Receive data from a server - after the page has loaded
    - Send data to a server - in the background

[Source](http://www.w3schools.com/xml/xml_http.asp)

```

### What is the relationship between AJAX and an XMLHttpRequest?
```
- The keystone of AJAX is the XMLHttpRequestObject
- AJAX is the use of the XMLHttpRequest object to communicate with server-side scripts

[Source](https://developer.mozilla.org/en-US/docs/AJAX/Getting_Started)

```

### What is the most common data interchange format? 
```
- Although the "X" in AJAX stands for XML, any type of data can be sent and received. JSON (JavaScript Object Notation) has replaced XML as the data interchange format of choice. A major reason for this is that JavaScript natively parses JSON, while XML must be parsed by a much slower and cumbersome set of client libraries.

[Source](http://stackoverflow.com/tags/ajax/info)

```

### What HTTP verbs or "methods" can be used?
```
- abort()
    Cancels the current request.

- getAllResponseHeaders()
    Returns the complete set of HTTP headers as a string.

- getResponseHeader( headerName )
    Returns the value of the specified HTTP header.

- open( method, URL )
- open( method, URL, async )
- open( method, URL, async, userName )
- open( method, URL, async, userName, password )
    Specifies the method, URL, and other optional attributes of a request.

    The method parameter can have a value of "GET", "POST", or "HEAD". Other HTTP methods, such as "PUT" and "DELETE" (primarily used in REST applications) may be possible.

    The "async" parameter specifies whether the request should be handled asynchronously or not. "true" means that the script processing carries on after the send() method without waiting for a response, and "false" means that the script waits for a response before continuing script processing.

- send( content )
    Sends the request.

- setRequestHeader( label, value )

    Adds a label/value pair to the HTTP header to be sent.

[Source](https://www.tutorialspoint.com/ajax/what_is_xmlhttprequest.htm)
```

### What are some ways to make Ajax calls?
```

```

### What is XML?
```

```

### Where does an XMLHttpRequest fit in the client/server - request/response cycle?
```

```

### Are there libraries make working with XMLHttpRequests easier? 
```

```

### How is an XMLHttpRequest different from a regular HTTP request in the browser?
```

```

### What is the Same-origin policy and how does it relate to Ajax?
```
- Same-Origin Policy: 
    - Restricts how a document or script loaded from one origin can interact with a resource from another origin
    - Critical security mechanism for isolating potentially malicious documents
    - Two pages have the same origin of the protocol, port (if specified, and host are the same for both pages 

[Source](https://developer.mozilla.org/en-US/docs/Web/Security/Same-origin_policy)

```

### Compare and contrast a server's response to an XMLHttpRequest vs a regular HTTP request
```

```

### Where can we find XMLHttpRequests in the Chrome Developer Tools?
```
- Chrome Dev Tools > Settings > Console > Log XMLHTTPRequests (checked)
- The console will log each XMLHttpRequest

[Source](https://developers.google.com/web/tools/chrome-devtools/console/)

```

### Who designed XMLHttpRequests?
```
- XMLHttpRequest was originally designed by Microsoft and adopted by Mozilla, Apple, and Google. It's now being standardized at the WHATWG ["Web Hypertext Application Technology Working Group"](https://whatwg.org/). 

[Source](https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest)
```


## 🙋 Answers!

When you think your squad knows all the answers raise your hands and we'll come check.

