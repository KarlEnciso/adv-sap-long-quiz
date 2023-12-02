## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture(SOA).
* A compilation of a bunch of services in one application to create a new process of application.

2. List and discuss the characteristics of SOA.
* Standardized Service Contracts = creating an agreement to follow specific tasks or rules to have clear communication by one or more service descriptions.
* Loose Coupling = some services need dependencies on each other to avoid any unnecessary impairment in the system.
* Service Abstraction = encapsulating a logic service that is unknown by the user since it should not show how it will perform its functionalities.
* Service Reusability = they reusing existing services.
* Service Autonomy = services is the one who can control all the encapsulated services.
* Service Statelessness = All services need to be stateless when it comes to sending a request from one state to the other. Since it should not keep any data.
* Service Discoverability = labeling specific tasks to help the user understand how the system works. So that, the user discovered easily the functionalities.
* Service Composability = a set of massive problems that split into small problems.
* Service Interoperability = services need to use standards to give the users their desired service.

3. Define Microservices.
* Also known as the microservice architecture - is an architectural style that structures an application as a collection of services that are Independent, deployable, Loosely coupled, Organized around business capabilities, and Owned by a small team

4. List and discuss the benefits of using Microservices.
* Independently Deployable = It can deploy without relying on other services.
* Right tool for the Job = It's the right tool because it's an architecture pattern that will help developers/ users use their desired applications. 
* Precise Scaling = It can deploy each service individually within its running time.

5. List and discuss the similarities and differences between SOA and Microservices.
- Differences - 
* When it comes to the architecture SOA is designed to share resources across services, while the Microservices are designed to host different services so that they can function independently.
* SOA shares data storage between services. While the Microservices can have independent data storage.
* SOA communicates via ESB and Microservices use the API layer to communicate.
* SOA depends on sharing resources, while the Microservices depend on the bounded context of coupling.
* SOA uses protocols and the Microservices use REST and JMS.

- Similarities - 
* They are both collection services.
* They are both efficiently used for cloud services.
* They are both architectural methods when it comes to managing and building applications.

6. Define Web Services.
* A software that allows communication between client and server that uses XML  for the messaging system on the World Wide Web.

7. List and discuss the benefits of using Web Services.
* Web service administrations give the authority to reveal the accessibility of a present code over the framework and other applications can use the accessibility of the program.
* Interoperability gives consistency and programmed relation with other programming applications into the next. It's like sharing information and administrations among themselves.
* Use the institutionalized industry standard show for connection and use all four layers to describe displays in the web organization.
* Instead HTTP protocol used SOAP for existing low-cost internet.

8. List and discuss the characteristics of Web Services.
* Using XML terminates any network since web services are highly interoperable.
* It supports loosely coupled connections between systems by passing XML messages to others through web API.
* It gives broader functionality in comparison to fine-grained service. It covers single or more fine-grained services together into a coarse-grained service to hold a lot of related data.
* Synchronous refers to existing web protocols in that the client waits for the response and is served by RPCoriented messaging while Asynchronous is the client who does not wait for the response and often uses document-oriented messaging.
* Supports RPC it can access a web service using platform-independent and language-neutral web protocols that allow clients to use procedures, functions, and methods using XML protocol.
* Make easier document exchange, that allows to transfer of structured data between different systems.

9. List and discuss the distinct roles in Web Services Architecture.
* Provider creates a web service for clients.
* Requestor a client that needs to interact with a web service. 
* Broker the application to allow the client to have access to the UDDI.

10. List and discuss the Web Services Components.
* SOAP is the one that exchanges information between systems.
* WSDL is a web service that helps to describe how to access them.
* UDDI is an XML framework that integrates and discovers web services.
