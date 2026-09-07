What is API response?
- API response is the data and status message that a server sends back to a client after processing an API Request and Response.
- For example: 
	- We send GET request for list of book available (Client)
	- Server will response with status code and data
	- Example: Server response with status code (200) which mean ok for success, and also will provide the data from the server often in JSON format.

Status Code
- 200 OK - Success, The request was successful, and the server returned the requested data
- 201 Created - Created, The request succeeded and a new resource was successfully created

- 400 Bad Request - Client Error, The server could not understand the request due to invalid syntax or missing required fields
- 401 Unauthorized - Client Error, Authentication is required. You need to log in or provide a valid API key
- 403 Forbidden - Client Error, The server understands who you are, but you do not have permission to access this resource
- 404 Not Found - Client Error, The server cannot find the requested resource or URL page

- 500 Internal Server Error - Server Error, The request was fine, but the server encountered an unexpected error on its end
- 503 Service Unavailable - Server Error, The server is temporarily overloaded or down for maintenance