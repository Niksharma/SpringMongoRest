# SpringMongoRest

1. Add a person to the noSql DB i.e. Mongo DB.
curl -i -X POST -H "Content-Type:application/json" -d '{  "userName" : "hello",  "email" : "hello@springmongo.com" }' http://localhost:8080/login

2. Verify that the user exists with a call to login controller. The controller will return a boolean success that the user exists else failure. 
curl-i -X POST -H "Content-Type:application/json" -d '{  "userName" : "Hello",  "email" : "hello@springmongo.com" }' http://localhost:8080/login
