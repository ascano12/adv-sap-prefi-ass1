## Assignment in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture(SOA).
each component in a service-oriented architecture (SOA): service providers develop web services and supply pertinent data to the service registry (or broker) so that they can be found and used again later on. Through the broker, the service requester finds the service it needs and binds with the service provider to trigger the necessary functionality.
SOA allow a single client to leverage several third-party services without having to create all the services from scratch. Let's say someone wants to make a website. A website needs payment gateways, web hosting, and products shipping services. As a result, that person will integrate any payment gateway, such PayPal, utilize any outside delivery providers, and hire a hosting company.
2. List and discuss the characteristics of SOA.
Standardized service contract: 
	•	One of the main principles of Service Oriented Architecture is standardized service contracts. They guarantee that services maintained in accordance with contract design requirements are those that are included in the same inventory of services. In a service-oriented architecture, the services can specify their functions and general goal in the form of a service contract. 
    Loose Coupling: 
	•	An strategy known as "loose coupling" involves linking the pieces, or components, of a system, network, or software program in a way that minimizes their practical dependence on one another. The degree to which one element directly knows another is referred to as coupling.
    Abstraction:
	•	The service abstraction layer is a key component of SOA that hides the implementation details and complexity of the underlying services from  consumers Provides a consistent and simplified interface for accessing service functionality and data.
    Service Reusability: 
	•	The help reusability standard is a plan guideline, applied inside the help direction plan worldview, to make benefits that can be reused across a business. These reusable administrations are planned with the goal that their answer rationale is autonomous of a specific business interaction or innovation.
    Autonomy: 
	•	Autonomy, as a design principle within the service-orientation design paradigm, enhances the independence of services from their execution environments. This increased autonomy fosters greater reliability, allowing services to function with reduced reliance on resources that are beyond one's control or influence.
    Statelessness: 
	•	Statelessness is a design principle employed in the service-orientation design paradigm, aiming to create scalable services by disconnecting them from their state data whenever feasible. This leads to a decrease in the resources utilized by a service, as the management of actual state data is outsourced to an external component or architectural extension. This reduction in resource consumption enables the service to efficiently handle a higher volume of requests in a reliable manner.
    Discoverability: 
	•	Discoverability refers to how easily something, particularly content or information, can be located in a search within a file, database, or other information system. This concept holds significance in library and information science, various facets of digital media, software and web development, as well as in marketing. This is because the utility of products and services is compromised if people struggle to locate them or lack an understanding of their purpose.
    Composability: 
	•	It refers to the development of new services by combining existing ones. Adhering to the design principles outlined in the preceding chapter enhances the capacity of services to be integrated into larger components, facilitating swift reuse of functionality.
    Interoperability: 
	•	Interoperability involves the exchange of data, and the higher the interoperability of software programs, the smoother their information exchange becomes. Software programs lacking interoperability require integration. Hence, SOA integration can be viewed as a procedure facilitating interoperability
3. Define Microservices.
Microservices  is a large application is constructed from modular components or services using the microservices architectural approach to corporate application design and deployment. Each module communicates with other modules and services via a clearly defined communications interface, such as an application programming interface (API), and supports a particular task or business objective. A microservices architecture is characterized by its efficient module creation, deployment, and scalability—features that are especially well-suited to application development for contemporary public clouds. It heavily leverages virtual containers and networking technologies.
4. List and discuss the benefits of using Microservices.
Micro services, which organize an application as a series of services, are sometimes referred to as micro service architecture. 
Large, sophisticated applications may be delivered quickly, often, and reliably thanks to the micro service design. It also makes it possible for a company to upgrade its technology stack. An application is organized as a group of loosely linked services using a micro service architecture, which is a variation of the service-oriented architecture structural style. Micro services architectures have lightweight protocols and fine-grained services. 
Highly maintainable and testable, Loosely coupled, Independently deployable Organized around business capabilities, Owned by a small team 

example-creating an online ordering system that accepts orders from clients, checks credit availability and inventories, and then ships the orders. The program is made up of multiple parts, such as the StoreFrontUI, which implements the user interface, and some
5. List and discuss the similarities and differences of SOA and Microservices.
Generally, core components of SOA are shared by various services. Conversely, microservices typically contain all the necessary components within the service, replicated in each microservice. As a result, microservices operate a little more slowly yet require fewer underlying services to function. The scope of the two techniques is the primary difference between them. In other words, microservices architecture has an application scope, whereas service-oriented architecture (SOA) has an enterprise scope. 

-SOA communication, providing the a channel by which services "talk" to one another. But in SOA, employing an ESB can slow down service communication. Microservices rely on more straightforward messaging mechanisms, such as language-neutral APIs, which facilitate faster communication.
