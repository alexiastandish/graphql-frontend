# client/client.js

#### Things we need

1.  LINK

    - network interface to access graphql server
    - httplink takes a uri and points to server
    - uri points to API (url to our server)

2.  CACHE

    - **In memory Cache** default from apollo
    - Interface that anyone can extend (setter, getter, delete)

3.  CLIENT _(initialize a client)_
    - **ApolloClient**
      > properties: link, cache ^^^

# client/index.js

#### ApolloProvider

- whatever part of our app we want to expose to apollo is wrapped in ApolloProvider
