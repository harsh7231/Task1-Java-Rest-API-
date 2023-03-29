# Kaiburr Task1 (Java REST API example)
---
Implement an application in java which provides a REST API with endpoints for searching,
creating and deleting “server” objects:

● GET servers. Should return all the servers if no parameters are passed. When server id
is passed as a parameter - return a single server or 404 if there’s no such a server.

● PUT a server. The server object is passed as a json-encoded message body. Here’s an
example:
{
“name”: ”my name,
“id”: “001”,
“language”:”java”,
“framework”:”django”
}

● DELETE a server. The parameter is a server ID.

● GET (find) servers by name. The parameter is a string. Must check if a server name
contains this string and return one or more servers found. Return 404 if nothing is found.

“Server” objects should be stored in MongoDB database.

Be sure that you can show how your application responds to requests using postman, curl or
any other HTTP client.

---

# Details & Documentation for Kaiburr Task 1

1. REST APIs are important in software development as they provide a simple and universal interface for applications to communicate with each other.

2. REST APIs are based on the HTTP protocol and use HTTP verbs to interact with resources.

3. A REST API provides a uniform interface, hiding implementation details of the server from the client.

4. To implement a REST API for searching, creating, and deleting "server" objects, we need to define endpoints for each action.

5. The GET request should retrieve all servers when no parameters are passed, or a single server by ID when a server ID is passed.

6. The PUT request should create a new server object, which is passed as a JSON-encoded message body.

7. The DELETE request should delete a server object by its ID.

8. An endpoint should be implemented to find servers by name, accepting a string parameter.

9. All server objects should be stored in a MongoDB database, which allows for flexible and scalable storage of data.

10. Implementing a REST API with MongoDB requires careful planning and attention to detail to create a simple and universal interface for applications to communicate with each other.
---