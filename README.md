# spring-cloud-zuul
Routing and Filtering | SpringBoot

Through this, the client can access the API through tokenisation.

- Run all three applications - 2 are API endpoint and 1 is ZUUL gateway.
- Our web browser will act like a client here
- To access the API on client, access the below endpoints:

http://localhost:8080/doctor-api/getDS
http://localhost:8080/diagnosis-service

Actual services are running on http://localhost:8081 and https://localhost:8082 but through this gateway tokenisation,
we are able to access these APIs through the ZUUL.