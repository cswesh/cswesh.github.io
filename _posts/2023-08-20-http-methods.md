---
title: What are HTTP Methods in APIs
date: 2023-08-20 12:00:00 +0530
categories: [technical]
tags: [API,HTTP Methods, GET, POST, PUT, PATCH, DELETE, methods, http verbs, http request methods, what are HTTP Methods, how api calls, different types of api calls, various http request methods, quick revision of apis, interview preperations]
published: true
---

# What are HTTP Methods ?

HTTP methods (also known as HTTP verbs or HTTP request methods) play a crucial role in designing APIs and web applications because they define how clients (such as browsers or other applications) interact with servers. When you make a request to an API endpoint, you're typically using one of these methods to perform a specific action on a resource.

Understanding these methods is fundamental when working with APIs because APIs expose various functionalities through specific endpoints, and the HTTP methods define what action you're trying to perform

   - HTTP methods are an essential part of the Hypertext Transfer Protocol (HTTP), which is the foundation of data communication on the World Wide Web. 
   - HTTP methods define the types of actions that can be performed on resources (such as documents, images, data) located on web servers. 
   - Each method corresponds to a specific action, and APIs (Application Programming Interfaces) often use these methods to perform various operations on resources.

The primary HTTP methods are:

1. **GET**: Retrieves data from the server. It's used to request resources like web pages, images, etc.

2. **POST**: Sends data to the server for processing. Commonly used to submit form data, upload files, or create new resources.

3. **PUT**: Updates or replaces an existing resource on the server with new data.

4. **PATCH**: Similar to PUT, but it's used to apply a partial update to a resource, typically for updating specific fields rather than the whole resource.

5. **DELETE**: Removes a resource from the server.

6. **HEAD**: Similar to GET, but it only requests the headers of a resource without the actual content. It's often used to check if a resource has been modified since a certain time.

7. **OPTIONS**: Retrieves the communication options for the target resource, indicating what methods and headers are allowed.

For example:

- If you're retrieving data from an API, you would use the GET method.
- If you're submitting a new record to a database through an API, you would use the POST method.
- If you're updating an existing record, you might use PUT or PATCH.
- If you're removing a record, you would use DELETE.

By knowing and understanding these HTTP methods, you can effectively communicate with APIs, build applications that interact with remote servers, and design APIs that provide the necessary functionality in a standardized and intuitive way.

[Some explanations are AI Generated, Proof-read & Verified](#)