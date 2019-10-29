# Routing Notes
 [client] == makes a request to an == [api] == sends a response back to the == [client]

What is the interface for a web api? =>  

- URI (uniform Resouce Identifier), 
- URL (Universal Resource Locator),
- Endpoint,
- HTTP === network protocol, a set of rules for communication

REST  == Recommendation of State Transfer ==


 - everything is a `Resource`
 - single URI per resource, ex:`https://web23/channels`, ` https://web23/users` 
 - user HTTP METHODS to preform operations on resources.
 - hypermedia (at this level we are fully REST-ful)

 |non REST|REST|
 |:--|:--|
 |/listALllChannels|:--|
 |/createChannel|GET /channels |
 |/updateChannel|POST /channels|
 |/deleteChannel|DELETE /channels|
 |/findChannel?id=123|GET /channels/123|

 What is an Express Router? why is it useful

## 
