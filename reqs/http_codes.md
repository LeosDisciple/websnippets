# HTTP codes
This list contains all error return codes used in Websnippets.

## 2xx Success
These codes indicate that the client's request was successfully received, understood, and accepted.
- 200 OK: The request has succeeded.

## Error codes
### 4xx Client Error Status Codes
These indicate that the client seems to have erred.
- 400 Bad Request: The server cannot or will not process the request due to something that is perceived to be a client error (e.g., malformed request syntax).
- 404 Not Found: The server hasn't found anything matching the Request-URI.
- 405 Method Not Allowed: The method specified in the Request-Line is not allowed for the resource identified by the Request-URI.
- 408 Request Timeout: The server timed out waiting for the request.
- 413 Payload Too Large: The request is larger than the server is willing or able to process.
- 415 Unsupported Media Type: The server is refusing to service the request because the entity of the request is in a format not supported by the requested resource for the requested method.
- 418 I'm a teapot (April Fools' joke, but codified): The server refuses the attempt to brew coffee with a teapot.
- 422 Unprocessable Entity: The request was well-formed but was unable to be followed due to semantic errors.
- 423 Locked: The resource that is being accessed is locked.
- 429 Too Many Requests: The user has sent too many requests in a given amount of time.

### 5xx Server Error Status Codes
These indicate that the server failed to fulfill an apparently valid request.
- 500 Internal Server Error: The server encountered an unexpected condition which prevented it from fulfilling the request.
- 503 Service Unavailable: The server is currently unable to handle the request due to a temporary overloading or maintenance of the server.
- 507 Insufficient Storage: The server is unable to store the representation needed to complete the request.


