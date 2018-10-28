# API Design with Node
> Build with Node, Express, Mongo

## Own notes

TESTING AUTHENTICATION
Signup (get the token)
http POST localhost:3000/auth/signin username=Jimmylo password=test

Middleware order:
decodeToken
get FreshUser
