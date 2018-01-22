# GraphQl

> why it will be better than our rest architecture ?

Think about the twitter home page , to make a page like that our app will have to send multiple rest calls to backend for 

- my status
- my profile pic
- some of my latest tweets
- stats of the tweets example likes comments etc
- no of messages
- no of friend requests

No doubt I can write a rest endpoint that will send all of these in one call , but think about the complexity plus Rest APIs are meant to expose only one resource for one endpoint

Moreover if I need only small amount of data from above endpoint like suppose for a mobile page example :
What if I just need my profile pic , or just my tweets without stats ? 


# Ans is i'll have to write separate endpoints but Graphql is here to save the day !!!
Because A client can’t, for example, specify which fields to select for a record in that resource. That information is in the REST API service itself and the REST API service will always return all of the fields regardless of which ones the client actually needs. GraphQL’s term for this problem is <b>over-fetching</b> of information that’s not needed. <b>It’s a waste of network and memory resources for both the client and server.</b>


<b>Another point is in a REST API, there is no client request language. Clients do not have control over what data the server will return. There is no language through which they can do so.</b>

A client can’t, for example, specify which fields to select for a record in that resource. That information is in the REST API service itself and the REST API service will always return all of the fields regardless of which ones the client actually needs. GraphQL’s term for this problem is over-fetching of information that’s not needed. It’s a waste of network and memory resources for both the client and server.


# Graphql makes restend like a database , where frontend devs can query for different resources in different formats ( attributes ) taht too from the same endpoint .

With GraphQL, we can basically shift this multi-request complexity to the server-side and have the GraphQL layer deal with it. The client asks the GraphQL layer a single question and gets a single response that has exactly what the client needs.

> Graphql focuses of breaking down the whole resources into a schema just like db schema , after the Rest guys develop an endpoint according to it , Frontend guys can query it using this query language to achieve desired resources in desired shapes and sizes


learn more over here
 - https://dev-blog.apollodata.com/graphql-vs-rest-5d425123e34b
 - https://www.howtographql.com/basics/1-graphql-is-the-better-rest/
 
> How to ? 

Before you start developing learn about the schema from over here : http://graphql.org/learn/schema/

> after this :

clone the repo and start learning
