# **CRUD**

## **Status Codes Based On REST Methods**

### In your own words, describe what each group of status code represents:

- 100s: Information
- 200s: Success
- 300s: Redirect
- 400s: Client Error
- 500s: Server Error

### What is a status code 202?

The 202 status means Accepted.

### What is a status code 308?

308 status code is for a permanent redirect

### What code would you use if an update didn’t return data to a client?

204 (No Content) should be sent when no data is returned.

### What code would you use if a resource used to exist but no longer does?

204 (No Content) should be sent upon a successful deletion.

### What is the ‘Forbidden’ status code?

403 (Forbidden) is returned when the client has proper authorization but can't access the resource.

## **Build A REST API With Node.js, Express, & MongoDB**

### Why do we need to pull our MongoDB database string out of our server and put it into our .env?

The database address should be stored in .env because it can change based on your deployed environment.

### What is middleware?

Middleware is any code that runs after the server gets a request, but before it is passed to the routes.

### What does app.use(express.json()) do?

It allows the server to accept json data as a body.

### What does the /:id mean in a route?

It represents one or more parameters that can be accessed in the request.

### What is the difference between PUT and PATCH?

PUT updates all information at once. PATCH updates only the information that was passed.

### How do you make a default value in a schema?

A default value can be set by creating the `default:` property and assigning it your default value.

### What does a 500 error status code mean?

The 500 status code means that there was an error with the server and it has nothing to do with the client.

### What is the difference between a status 200 and a status 201?

Code 200 means OK and Code 201 means Created. 201 should be sent instead of 200 whenever you are creating something because it is a more specific status code that better represents the results.

## **Things I want to know  more about**

I want to continue learning more about RESTful code and how to use it with APIs. It is really cool to start seeing how REST allows different actions to be taken and I'm looking forward to furthering my understanding.
