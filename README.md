# Steam GraphQL Wrapper

This project intends to create a GraphQL endpoint that servers the [Steam Web API](https://developer.valvesoftware.com/wiki/Steam_Web_API#Interfaces_and_method).

## Why
### Practice
While the underlying scheme isn't that complex (basically players, games and game related entities such as stats and news), this is a fine little project to learn how to wrap this API with GraphQL.
### Steam News Client
I started to build my own Steam News Client as an electron app several years ago. What started as a simple "fetch all news for my games" has been grown into a bigger thingy since. Now seems to be a good moment to split things up so all the API logic will life in its own little project and might be used by other clients.

## What
The Steam Web API allows several data formats, including JSON and XML. I'm about to take the API docu, build a proper scheme and maybe add some utility queries later on. So nothing fancy at all :P

## How
I want to get used to some tools for this, so namely these are:
* GraphQL / Express
* Axios
* Now.sh

These tutorials from [Zeit](https://zeit.co/docs/examples/graphql) and [Prisma](https://www.prisma.io/blog/how-to-wrap-a-rest-api-with-graphql-8bf3fb17547d/) will be kickstarting things.
