# **APIs**

## **API Design Best Practices**

### What does REST stand for?

REST stands for Representational State Transfer.

### REST APIs are designed around a ____?

REST APIs are designed around a resource.

### What is an identifier of a resource?

A resource identifier is a URI that uniquely identifies that resource. For example: `https://adventure-works.com/orders/1`

### What are the most common HTTP verbs?

The most commonly used HTTP verbs are GET, POST, PUT, PATCH, and DELETE.

### What should the URIs be based on?

URIs should be based on nouns or the resource itself, not the operations performed on the resource.

### Give an example of a good URI.

A good URI looks like this: `https://adventure-works.com/orders`

### What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

A chatty API is one that exposes a large amount of small resources. This is not good, because it can require a client application to send multiple requests to retrieve all of its required data. This creates extra network traffic, but can be avoided by using properly sized resources that strike a balance between needing to many requests and passing too large of objects.

### What status code does a successful GET request return?

A successful GET returns 200 (OK).

### What status code does an unsuccessful GET request return?

An unsuccessful GET returns 404 (Not Found).

### What status code does a successful POST request return?

A successful POST returns 201 (Created) if it created a new resource. If it did not create a new resource, but just did some processing, then it can return 200 (OK) or 204 (No Content) if there is no result to return.

### What status code does a successful DELETE request return?

A successful DELETE returns 204 (No Content).

## **Things I want to know more about**

I am interested in learning more about how APIs are created. They serve a very cool function and I think they will continue to grow and be very important in the future of communications technology.
