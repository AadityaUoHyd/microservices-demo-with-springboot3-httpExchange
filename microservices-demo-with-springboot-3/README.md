# microservices-demo-with-springboot-3
This is sample microservice project, with eureka server, api-gateway, native configured config-server, and two services- employee & department.
Developed just to demonstrate the how microservices can be developed using springboot-3. Used load balanced Http-Exchange and zipkin too.
Didn't used here any DB, as its for demo purpose.

# How to run this project:

- Run all the individual services as springboot @IDE, then to cross check in eureka server, hit this url at browser => localhost:8761/
![](https://github.com/AadityaUoHyd/microservices-demo-with-springboot3-httpExchange/blob/master/microservices-demo-with-springboot-3/eureka.jpg)

- Now add & fetch some data from postman (Adding department):
![](https://github.com/AadityaUoHyd/microservices-demo-with-springboot3-httpExchange/blob/master/microservices-demo-with-springboot-3/dep1.jpg)

- Get department by ID:
![](https://github.com/AadityaUoHyd/microservices-demo-with-springboot3-httpExchange/blob/master/microservices-demo-with-springboot-3/dep2.jpg)

- Get employees:
![](https://github.com/AadityaUoHyd/microservices-demo-with-springboot3-httpExchange/blob/master/microservices-demo-with-springboot-3/emp1.jpg)

- Get employee vis-a-vis department id:
![](https://github.com/AadityaUoHyd/microservices-demo-with-springboot3-httpExchange/blob/master/microservices-demo-with-springboot-3/emp2.jpg)

- Get department with employees:
![](https://github.com/AadityaUoHyd/microservices-demo-with-springboot3-httpExchange/blob/master/microservices-demo-with-springboot-3/dep3.jpg)

- Get department with employees via API GATEWAY :
![](https://github.com/AadityaUoHyd/microservices-demo-with-springboot3-httpExchange/blob/master/microservices-demo-with-springboot-3/WithApiGateway.jpg)

- See details in Zipkin (direct):
![](https://github.com/AadityaUoHyd/microservices-demo-with-springboot3-httpExchange/blob/master/microservices-demo-with-springboot-3/zipkin.jpg)
(through api-gateway using HTTP-EXCHANGE)
![](https://github.com/AadityaUoHyd/microservices-demo-with-springboot3-httpExchange/blob/master/microservices-demo-with-springboot-3/zip2.jpg)
