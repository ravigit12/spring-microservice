## Part 1: Creating microservice using Spring Cloud, Eureka and Zuul.

Detailed description can be found here: [Part 1: Creating microservice using Spring Cloud, Eureka and Zuul](https://piotrminkowski.wordpress.com/2017/02/05/part-1-creating-microservice-using-spring-cloud-eureka-and-zuul/) 


---------Notes by Ravi-------------
1.How to start server :
	a.Go to target folder of each project and run the command :
			java -jar customer-service.jar
			java -jar account-service.jar
			java -jar discovery-service.jar
			java -jar gateway-service.jar
1.url :http://localhost:3333/customers/2    ---customer service
		http://localhost:2222/accounts/customer/1  --account service
		http://localhost:8761/ ---Eureka