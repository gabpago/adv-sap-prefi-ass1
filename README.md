## Assignment in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture(SOA).
Service-oriented Architecture is a method of software development that uses software components called services to create business applications. Each service provides a business capability, and services can also communicate with each other across platforms and languages.


2. List and discuss the characteristics of SOA.
Loose Coupling: are designed to be loosely coupled, meaning that they operate independently of one another.
Interoperability: enabling different systems and platforms to communicate and exchange data seamlessly
Reusability encourages the creation of services that are designed to be reusable in various contexts and applications.
Abstraction: are abstracted from their underlying implementation details, exposing only the necessary information and functionality.
Discoverability: meaning that service consumers can find and understand available services and their capabilities.
Composability: create more complex business processes and applications.
Standardized Communication: often relies on standardized communication protocols and formats, such as SOAP (Simple Object Access Protocol) or REST (Representational State Transfer).
Scalability:  supports scalability, allowing for the efficient scaling of individual services to handle varying levels of demand.
Security: emphasizes the importance of security at both the service level and during communication between services.
Lifecycle Management:  involves managing the entire lifecycle of services, from design and development to deployment, maintenance, and retirement.



3. Define Microservices.
Microservices is an architectural approach to software development where a complex application is broken down into small, independent, and loosely coupled services.


4. List and discuss the benefits of using Microservices.
Modularity and Independence: With the help of microservices, it is possible to create compact, targeted services that let teams concentrate on particular features or tasks on their own.

Scalability: Microservices maximize resource consumption by having the ability to expand independently based on the demand for certain services.

Faster Deployment and Continuous Delivery: Because microservices can be delivered individually, there is less chance of an error occurring and features can be released more quickly.

Fault Isolation and Resilience: The entire application may not necessarily be impacted if one microservice fails. Because the failure is limited to that particular service, system resilience is increased.

Enhanced Developer Productivity: By concentrating on particular microservices, developers can simplify the code they work on and make it simpler to comprehend and update.


Easier Maintenance and Upgrades: One microservice's updates and modifications may not always have an impact on

Adaptability to Business Changes: Microservices enable the addition or adjustment of individual services without requiring a complete rewrite of the application, enabling quick adaption to shifting business requirements.


Optimized Technology Stack: For each microservice, developers can select the best technologies to maximize development efficiency, scalability, and performance.


5. List and discuss the similarities and differences of SOA and Microservices.
SIMILARITIES

Service-Based Architecture: Both SOA and microservices are built on the concept of organizing software functionality as a set of services.

Distributed Systems: oth architectures involve the distribution of services across a network, allowing for more scalable and resilient systems.

DIFFERENCES

Technology Stack: SOA allows for a more homogeneous technology stack across services. In contrast, microservices

Data Management: SOA tends to centralize data management, with shared databases or enterprise service buses (ESBs). Microservices favor decentralized data management, with each service having its own database

