# API Design Best Practices

1) What does REST stand for?

REST is an architectural style for building distributed systems based on hypermedia. REST is independent of any underlying protocol and is not necessarily tied to HTTP.

2) REST APIs are designed around a ____.

REST APIs are designed around **resources**, which are any kind of object, data, or service that can be accessed by the client.

3) What is an identifer of a resource? Give an example.

 It is a URI that uniquely identifies that resource.  For example, the URI for a particular customer order might be: `https://adventure-works.com/orders/1`.

 4) What are the most common HTTP verbs?

* **GET** retrieves a representation of the resource at the specified URI. The body of the response message contains the details of the requested resource.

* **POST** creates a new resource at the specified URI. The body of the request message provides the details of the new resource. 

* **PUT** either creates or replaces the resource at the specified URI. The body of the request message specifies the resource to be created or updated.

* **PATCH** performs a partial update of a resource. The request body specifies the set of changes to apply to the resource.

* **DELETE** removes the resource at the specified URI.

5) What should the URIs be based on?

resource URIs should be based on the resource.

6) What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

Web APIs that expose a large number of small resources and it ii a bad thing.

7) What status code does a successful GET request return?

A successful GET method typically returns HTTP status code 200(OK).

8) What status code does an unsuccessful GET request return?

If the resource cannot be found, the method should return 404 (Not Found).

9) What status code does a successful POST request return?

If a POST method creates a new resource, it returns HTTP status code 201 (Created).

10) What status code does a successful DELETE request return?

If the delete operation is successful, the web server should respond with HTTP status code 204.