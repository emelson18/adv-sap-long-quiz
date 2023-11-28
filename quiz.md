1. define service oriented architecture?
	Service Oriented Architecture or SOA is a method of software development which uses Services to create business applications. Services is a software component that provides functionality or data exchange to their consumer. Services are basically the building blocks in a SOA. 

2. 	-SOA enables the exchange of data between services and also the use of the data that is sent through that exchange.
	-SOA helps in providing methods for service encapsulation which helps in making a cleaner and simpler look to an object. Sevice encapsulation is done by hiding the internal representation of an object.
	-SOA allows service discovery which is a process in which web service providers can be located and web services descriptions can be retrieved. This is done with the use of service registry which is a database that holds the relevant metatdata as well as the available and upcoming services available in an application.
	-SOA allows service composition which is the process of combining multiple small services to create a bigger and  more complex service with the purpose of providing a dunction for  bigger business requirement. This helps businesses in avoiding the need for developing an entire solution for a business need.
	-SOA provides loosely coupled services meaning services are working independently without relying to other services. This allows changes on a service to be applied without directly affecting other services since each service are working independently.
	- SOA provides ease of maintenance and reduced cost development and deployment. SOA is easy to maintain since its services are lossly coupled and changes on a service doesnt affect other service. Services can also be reused meaning lesser time for development which leads to lesser cost. 

3. Define Microservices 
	Microservices is an architectural style of developing applications which allows large applications to be divided into smaller independednt parts where each parts has its own responsibilities or functions. 

4.	- Microservices provide improved scalability since it is divided into parts, it avoids traffic from user requests because different parts od the application has it own resources. 
	- Failure Isolation is also observed in a microservices architecture. Microservices being divided into parts avoids the possibility of one service failure to affect the rest of the application.
	- Microservice is programming langunage and technology agnostic meaning it can be connected to any programming language and can also be run on any platform.
	- Microservice provides better data and security by storing data of services in each respective database instead of storing dadta in a single database that can be accessed as a whole by the application.
	- Services in a microservice architecture can be worked on by the developers for development and upgrade without thinking of coding conflicts simply because services are working independently of one another. This provides faster time to market for applications. 
	
5. 
SIMILARITIES:
	SOA and Microservices are similar in terms of how they divided applications into smaller parts which serves for a single function of the application. This also leads to their ability of bbeing interopearble. SOA and Microservices both have their own communication protocols which allows the services to communicate and echange data with onw another. They are also both scalable because services can be changed without worrying about the other.

DIFFERENCES:
	Eventhough SOA and Microservices both divides application into smaller parts with the use of services, SOA uses larger services since it covers the whole enterprise compared to microservices that only covers application scope and uses small services focused on a single function. The services that SOA and microservices also differ with how they manage their data. Since SOA does use service composition, SOA services does have common data storage for multiple services unlike in microservice where one service have its own data management database. Failure of one service in SOA can also affect the other services specially services that are joined togteher through service composition unlike in microservices which makes sure that one service failure wont affect others because services works independently of one another.  

6. Define Web Services.
	The web services architecture is based on interactions between three components: a service provider, a service requester, and an optional service registry. Web service is a standardized medium to propagate communication between the client and server applications on the WWW (World Wide Web). A web service is a software module that is designed to perform a certain set of tasks.

7. List and discuss the benefits of using Web Services.
	-Web services can make use of existing functions on a network meaning other programs can make use of the codes that are already working and are present in the network can be accessed and used by using HTTP requests.
	-Web Services allows communication between different applications making web services a interoperable architecture. This simply means that web services makes it possible for applications to share services and data with each other.
	- Web Services uses SOAP or Simple Object Access Protocol but can also be implemented with other reliable transport mechanism. Compared to other protocols, SOAP is relatively less costly.

8.List and discuss the characteristics of Web Services.
	- Web Service makes use of XML which makes it possible to use without the need of any operating system. This makes communication between different applications much easier since difference between OS will never exist in this concept.
	- Web Services is also loosely coupled in nature meaning changes in the client would not directly afffect the server and vice versa. This makes it easier to make changes and updates with web services since client and server does not affect each other directly.
	- Web Services supports documnet exchange eventhough the difference between the two documents is massive. Web Services also use to represent data in two forms which is generic and complex. 

9. List and discuss the different distinct roles in Web Services. 
	- Provider is the one taht si responsible for creating the web service and make it available for the client and anyone who needs the web service created.
	- Requestor is a client application that can be any language based application that that is looking for a functionality through the web. Basically the requestor is the one that contacts the web service that is created by the service provider. 
	- Broker is the service application that is responsible in providing the access to the UDDI. UDDI is a platform which enables the ecliet application to locate the web service it was looking for.

10. List and discuss the Web Services components.
	- SOAP or Simple Object Access Protocol is a message protocol which allows the communication between different applications elements. Soap is used to enable communication between applications through the internet.
	- UDDI or Universal Description, Discovery and Integration is a standard based on XML that is used for describing, publishing adnd finding web services. UDDI uses Web Service Definition Language or WSDL to describe interfaces to web services. UDDI allows businesses to locate each other and define hoe they interact with each other over the internet. 
	- WDSL or Web Service Definition Language is the standard format used to describe web services. It is an XML based protocol which focuses in the exchange of information in decentralized and distributed environments. WSDL is used to describe a web service and what operations it can perform. WSDL is the language that UDDI uses.
	
	


	         