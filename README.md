# API Gateway in Node JS for Microservice Architecture

This project is a seed for developing Micro Service in Node JS. It makes use of API Gateway for routing to different services.

## Running

```
npm install
npm start # Starts the api gateway at port 8080
npm test # Runs the test suite
```

## Services Endpoint

### `/public/api/*`
Request is forwarded to localhost:7070

### `/api/*`
Request is forwarded to localhost:9090
