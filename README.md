# PyGraphQL
Server GraphQL in Python using a Flask, GraphQL, Graphene, MySQL, and Docker starter kit

## Project Setup
Ensure that docker v1.3 and above is installed

```
$ git clone https://github.com/harryjanz/PyGraphQL.git {cloneFolder}
$ cd {cloneFolder}
$ docker-compose build
$ docker-compose up
```
### Obs
Do note that it's never a good idea to commit your database user and password credentials in the repository, use a .env file instead. This repository is just for reference purpose.

## References
* [How to develop a Flask, GraphQL, Graphene, MySQL, and Docker starter kit](https://medium.com/free-code-camp/how-to-develop-a-flask-graphql-graphene-mysql-and-docker-starter-kit-4d475f24ee76)
