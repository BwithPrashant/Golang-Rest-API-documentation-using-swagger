# Golang-Rest-API-documentation-using-swagger

### Why do we need to document Rest APIs?

Clients use Rest APIs exposed by server.
They should have proper information of :-
* End point
* Description of API
* HTTP method
* Parameters
  + type
  + format of input
* Response
  + code
  + content-type
 * Curl command
 
 ### Different ways of documentation 
 
 * create a document file and share across all clients.
    + If we update it in future , again share the updated file to all clients
 * create a web page containing documentation and host it on a server.
    + client can see the documentation only. There is no way to test the api's. Also need to start a different server.
 * Swagger
    + It runs on the same API server. One can see the documentation and test the api's as well.
    + Check a demo application : [Petstote](https://petstore.swagger.io/)
    
### Swagger documentation in Golang

Follow [this](https://github.com/swaggo/gin-swagger)
