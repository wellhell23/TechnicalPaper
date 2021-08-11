# **Rest**: Representation State Transfer
Rest stand for **Re**presentation **S**tate **T**ransfer. It was created by Roy Fielding. Rest is architecture style in a distributed hypermedia systems. Rest is a way to communicate between components on the web. It is a style, design you can follow but it's not a formal specification and don't have formal document.   
Rest consists of HttpMethods, Status codes, Response Types. Rest API uses HTTP Methods for sending and receiving data over a network. 
Rest use HTTP for all four **CRUD** operations.

## **Architectural Constraints**

There are 6 constraints applied to the elements within the architectural. These architectual constraints make any web service a RESTfull Api:

* **Client-Server**- This constraint state that the application should have saperate cliend and server. Client and Server completrly decoupled. By this we improve the portability of user interface. Client and Server developed independently without disturbing the each other.
* **Stateless**- This constraint state that the communication between client-server in stateless means that server is not store the state of the application. Request feom client to server must contain all necessary information to understand the request. Client is responsible to store the state of application. 
* **Cache**- Cache constraint state that the data with in responses should be labled as cacheable or non-cacheable. If the response is cacheable than the client store the response data and have right to reuse it. By this some intraction between client and serve is eliminated and improve efficiency.
* **Uniform Interface**- Uniform Interface is the key to distinguishes the Rest architectural style to the others. Its is basically means that the different types of application or components need a uniform way of interacting to the server in same way. There are 4 elements of uniform interface: Identification of resources, Manipulation of resources through representations, Self-descriptive messages, Hypermedia as the engine of application state(HATEOS).
*  **Layered System**- It allows an architecture to be composed of hierarchical layers and each layers cannot know anything beyond the immediate layer with which they are interacting. 
*  **Code-On-Demand**- It is an optional constraint. It state that the Rest allow the client to downloading and executing the code in the form of scripts. This reduce the visibility.
  

>*Rest architecture provide a HTTP methods to a web application in a very light, simple and effective way*.

### HTTP methods use by Rest for **CRUD** operation are:

    Create -> Post
    Read   -> Get
    Update -> Put
    Delete -> Delete

## ***Reference***

*[REST API Tutorial](https://restfulapi.net/)*  
*[Telusko: What is REST](https://www.youtube.com/watch?v=qVTAB8Z2VmA)*  
*[REST Dissertation](https://www.ics.uci.edu/~fielding/pubs/dissertation/rest_arch_style.htm)*   
*[Mastering REST Architecture ](https://ahmetozlu93.medium.com/mastering-rest-architecture-rest-architecture-details-e47ec659f6bc)*