# What is an API?
Application programming interface (API) is a super lofty term. It can mean a lot of things. Abstractly, it's anything with an abstraction or face, if you will. It can be a function, a library, or literally my face. The most important thing to know is that API is generally a term used for machine-to-machine communication. In the context of EPICS, it's often auth0 API, NuxtAuth API, or in this section, RESTful API.
# What is the REST API?
REST stands for Representational State Transfer. Its core principles are:

* **Client-server architecture**: A system divided into clients requesting services and servers providing them.
* **Statelessness**: Each request contains all necessary information independently, without reliance on server-stored state. (functional programming paradigm)
* **Cacheability**: Data can be stored locally to speed up future requests to the same data.
* **Layered system**: The system is organized into layers, with each layer serving the one above it and using services from the one below (n-tier architecture)


 ## Resources
 Resources are indentified by URLs. For example, we have `http://localhost:9999/restfulservices/v1/users/{id}`.

 ![graphic](https://github.com/user-attachments/assets/1069384d-9da3-4499-a380-a2ee3580652e)

You will see something like this very often. 
```bash
/api/user
/api/users/admin
/api/shippingaddress
```

# HTTP Methods
**GET** -> Retrieves resources
**POST** -> Creates new resources
**PUT** -> Updates entire resources
**PATCH** -> Partially updates resources
**DELETE** -> Removes resources

# Status Codes
Common Codes are `200 OK`, `404 Not Found`, and `500 Internal Server Error`. 

# Design Best Practices
* Keep CONSISTENT NAMING CONVENTIONS
* Version your APIs (version control)
* Use nouns instead of verbs in your endpoint paths (you do this because the verb is probably already specified in the HTTP method)
* Filtering, sorting, and pagination

# Auth + Security
Common authentication methods include json webtoken (jwt) and OAuth. HTTPS (secure HTTP) is secure communication.

# Postman
Postman can help you develop and test the API. You can download it here: [https://www.postman.com/downloads/](url)
