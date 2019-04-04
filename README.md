# go-rest-api

A simple rest-api built using GoLang. This api is not attached with any database. Just using sample data generated in a globle variable itself named as people. 

### Usage
1. Clone or download to your `go/src/` directory
2. Use `go get github.com/gorilla/mux` to get the dependency called **mux** used to route requests
3. Build using `go build`
4. Run the API using `./go-rest-api`
5. Use **postman** or any  API development environment to test the endpoints

### End points: 

GET: ``localhost:8000/people``

GET: ``localhost:8000/people/{id}``

POST: ``localhost:8000/people/{id}``

PUT: ``localhost:8000/people/{id}``

DELETE: ``localhost:8000/people/{id}``


