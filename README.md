GraphQL Workshop Links and Resources
==========

* [Slides](https://docs.google.com/presentation/d/1PyIctm0YPtaBleDxNkNXTEBvHSK5WNjMwzJaif2nmL4/edit?usp=sharing)

## Day 1

### Query Language
* [Snowtooth Playground](http://snowtooth.herokuapp.com/playground)
* [Github GraphQL Explorer](https://developer.github.com/v4/explorer/)
* [SWAPI: Star Wars API](http://graphql.org/swapi-graphql/)

### Designing A Schema
* [City to City Through Types - Launchpad](https://launchpad.graphql.com/lk3qk3zq7q)
* [Union Types - Launchpad](https://launchpad.graphql.com/r94qxj5q4n)
* [Interfaces - Launchpad](https://launchpad.graphql.com/j8r375km3p)
* [SWAPI - Launchpad](http://bit.ly/swapi-launchpad)

### Building an API
* [Photos JSON File](https://github.com/graphqlworkshop/photo-share-api/blob/f98c31580f19db9814c04899945942b155e7b619/data/sample-photos.json)
* [Users JSON File](https://github.com/graphqlworkshop/photo-share-api/blob/f98c31580f19db9814c04899945942b155e7b619/data/sample-users.json)

### Database Integration
* [Mongo Installation for Mac](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-os-x/)
* [Mongo Installation for PC](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-windows/)
* [mLab](https://mlab.com/)
* [Local Instructions for Mongo & mLab](https://gist.github.com/eveporcello/98f9e37a65f05b9d0866137d80ed9653)
* Typical Mongo Service Route: `mongodb://localhost:27017/photo-share`
* Typical mLab Service Route: `mongodb://test:password@ds215089.mlab.com:15089/photo-share` (yours will differ slightly, find on mLab)

#### .env file

```
DB_HOST=mongodb://*** or `mongodb://******
CLIENT_ID=<GITHUB_CLIENT_ID>
CLIENT_SECRET=<GITHUB_CLIENT_SECRET>
```

## Day 2

### Client Examples
* curl Request
```
curl -X POST \
     -H "Content-Type: application/json" \
     --data '{ "query": "{allPhotos{name}}" }' \
     http://localhost:4000/graphql
 ```
 
* [Fetch Sample](https://codesandbox.io/s/wy9mq00q9w)
* [graphql-request](https://codesandbox.io/s/4qzq5z2vz0)
* [Lab Start](https://codesandbox.io/s/kmmz8om2xv)
* [Lab Finished](https://codesandbox.io/s/q8l7wp6m0w)

### Apollo Client Examples
* [Simple Apollo Setup](https://codesandbox.io/s/3q245om1q6)
* [Sending Client Queries](https://codesandbox.io/s/4xnkxmnw7w)
* [writeQuery](https://codesandbox.io/s/oo3z008kzy)

### Activity Endpoints
| Example             | endpoint                               | test                                     |
|---------------------|----------------------------------------|------------------------------------------|
| City Sample         | https://lk3qk3zq7q.lp.gql.zone/graphql | https://launchpad.graphql.com/lk3qk3zq7q |
| Study Group (union) | https://r94qxj5q4n.lp.gql.zone/graphql | https://launchpad.graphql.com/r94qxj5q4n |
| Alex's Ski Days     | https://api.graph.cool/simple/v1/cja33bgdf6g8i0109u1k4913c | https://www.graphqlbin.com |


### Apollo Link Examples
* [Observable Intro](https://codesandbox.io/s/176q4zpl4)
* [Observable + Link](https://codesandbox.io/s/ql5xqkojyj)
* [HTTP Link](https://codesandbox.io/s/koj24j5l07)
* [Concatenating Links](https://codesandbox.io/s/ql4jlz54yq)


### GitHub Auth
window.location = https://github.com/login/oauth/authorize?client_id=${clientID}&scope=user

### Evaluation
* [Final Day Eval](http://bit.ly/graphql-fluent)


## GraphQL Articles & Documentation

### Graph Theory

* [From REST to GraphQL](https://0x2a.sh/from-rest-to-graphql-b4e95e94c26b)
* [A Gentle Introduction to Graph Theory](https://dev.to/vaidehijoshi/a-gentle-introduction-to-graph-theory)
* [Euler's Solution to the Konigsberg Bridge Problem](www.maa.org/press/periodicals/convergence/leonard-eulers-solution-to-the-konigsberg-bridge-problem)

### GraphQL

* [GraphQL Docs](http://graphql.org/)
* [How To GraphQL](https://www.howtographql.com/)
* [Schema Language Cheat Sheet](https://github.com/sogko/graphql-schema-language-cheat-sheet)

### Apollo

* [Apollo GraphQL](https://www.apollographql.com/)
* [React Apollo](https://github.com/apollographql/react-apollo)

### Relay

* [Relay Modern](https://facebook.github.io/relay/)
* [Relay Tutorial](https://facebook.github.io/relay/docs/tutorial.html)
