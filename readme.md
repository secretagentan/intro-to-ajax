# Intro to AJAX

## 🔬 Research!

In your squads research and answer the following questions:

### What does the acronym AJAX stand for?

```
- Asynchronous JavaScript and XML
- Not a programming language 
- Apps that use: Google Maps, image gallery

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
- AJAX is the technique for making a request

[Source](https://developer.mozilla.org/en-US/docs/AJAX/Getting_Started)

```

### What is the most common data interchange format? 
```
- Although the "X" in AJAX stands for XML, any type of data can be sent and received. JSON (JavaScript Object Notation) has replaced XML as the data interchange format of choice. A major reason for this is that JavaScript natively parses JSON, while XML must be parsed by a much slower and cumbersome set of client libraries.

[Source](http://stackoverflow.com/tags/ajax/info)

```

### What HTTP verbs or "methods" can be used?
```
// Secure methods: OPTIONS, GET, HEAD, POST, PUT, and DELETE
// Insecure methods: TRACE, CONNECT

- XMLHttpRequest.abort()
Aborts the request if it has already been sent.

- XMLHttpRequest.getAllResponseHeaders()
Returns all the response headers, separated by CRLF, as a string, or null if no response has been received.

- XMLHttpRequest.getResponseHeader()
Returns the string containing the text of the specified header, or null if either the response has not yet been received or the header doesn't exist in the response.

- XMLHttpRequest.open()
Initializes a request. This method is to be used from JavaScript code; to initialize a request from native code, use openRequest() instead.

- XMLHttpRequest.overrideMimeType()
Overrides the MIME type returned by the server.

- XMLHttpRequest.send()
Sends the request. If the request is asynchronous (which is the default), this method returns as soon as the request is sent.

- XMLHttpRequest.setRequestHeader()
Sets the value of an HTTP request header. You must call setRequestHeader()after open(), but before send().

[Source](https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest)

```

### What are some ways to make Ajax calls?
```
- An AJAX request is made using the XMLHttpRequest object and its open() and send() methods. 

```

### What is XML?
```
- "eXtensible Markup Language"
- Markup language much like HTML
- Designed to store and transport data
- Self-descriptive:
    - Sender info
    - Receiver info
    - Heading
    - Body 
- XML doesn't DO anything - just info wrapped in tags
- XML vs. HTML: 
    - XML does not have predefined tags
    - Tags are "invented" by the author of the XML doc
    - Author must define both tags and document structure
- XML simplifies: 
    - Data sharing
    - Data transport
    - Platform changes
    - Data availability
- Set of rules used to standardize how document is marked up

[Source](http://www.w3schools.com/xml/xml_whatis.asp)

```

### Where does an XMLHttpRequest fit in the client/server - request/response cycle?
```
- Out of band
- 

```

### Are there libraries make working with XMLHttpRequests easier? 
```
- axios
[Source](http://jamesknelson.com/six-essential-javascript-libraries/)

- jQuery

- Angular.js
[Source](https://toddmotto.com/writing-a-standalone-ajax-xhr-javascript-micro-library/)

```

### How is an XMLHttpRequest different from a regular HTTP request in the browser?
```
// When the browser makes a regular HTTP request, the browser clears the
// current window and loads the server response into the new window.
// A XMLHttpRequest does not affect the current window and the js code can 
// examine the results of the request and do whatever the code states 
// without re-loading the current window.

```

### What is the Same-origin policy and how does it relate to Ajax?
```
- Same-Origin Policy: 
    - Restricts how a document or script loaded from one origin can interact with a resource from another origin
    - Critical security mechanism for isolating potentially malicious documents
    - Two pages have the same origin of the protocol, port (if specified, and host are the same for both pages 

- AJAX - JSONP - method of script injection 
// Ajax requests to a different domain would normally be prevented under the same-origin policy. But using script-injection through JSONP can be enabled to make ajax calls to other domains.

[Source](https://developer.mozilla.org/en-US/docs/Web/Security/Same-origin_policy)

```

### Compare and contrast a server's response to an XMLHttpRequest vs a regular HTTP request
```
- On the server side - 

```

### Where can we find XMLHttpRequests in the Chrome Developer Tools?
```
- Chrome Dev Tools > Settings > Console > Log XMLHTTPRequests (checked)
    - The console will log each XMLHttpRequest
- Or: Chrome Dev Tools > Sources > XHR Breakpoints

[Source](https://developers.google.com/web/tools/chrome-devtools/console/)

```

### Who designed XMLHttpRequests?
```
- XMLHttpRequest was originally designed by Microsoft and adopted by Mozilla, Apple, and Google. It's now being standardized at the WHATWG ["Web Hypertext Application Technology Working Group"](https://whatwg.org/). 

[Source](https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest)

```

### BONUS: Use jQuery to make an XHR GET request 
```


```


## 🙋 Answers!

When you think your squad knows all the answers raise your hands and we'll come check.






