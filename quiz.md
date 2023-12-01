## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture (SOA).
- SOA allows everything to run through a single interface. That means you can reuse code. You do not have to worry about making new code and costing company money.
2. List and discuss the characteristics of SOA.
- _Standardized Service Contracts:_ an agreement between parties where one party sets the terms.
- _Loose Coupling:_ reducing dependencies between different systems.
- _Abstraction:_ Hiding design details and implementation logic from the outside world
- _Service Reusability:_ means it have an intention on maximizing reuse.
- _Autonomy:_ A service should be self-contained.
- _Statelessness:_ The use of document-style messages.
- _Discoverability:_ provide a discovery mechanism, such as a service registrt or directory.
- _Composability:_ creating new service while combining existing services.
- _Interoperability:_ allows different distributed web services to run on a variety of software platforms and hardware architectures.
3. Define Microservices.
- It divides SOA service into a smaller services.
4. List and discuss the benefits of using Microservices.
- _Independently Deployable:_ it enables the organization to create small, cross-functional teams around one service.
- _Right tool for the job:_ Each service can use its own language, framework, or ancillary services while still being able to communicate easily with the other service in the application.
- _Precise Scaling:_ Each microservice operates as an independent entity with its own boundaries and responsibilities.
5. List and discuss the similarities and differences of SOA and Microservices.
- they both allow development teams to build, deploy, and manage modern applications efficiently for cloud environments, mean while their difference is SOA model, are shared and reused enterprise-wide, while microservice is built on individual services that function independently.
6. Define Web Services.
- Web Service is a software system allowing communication between different applications over a network,often using standardized protocols.
7. List and discuss the benefits of using Web Services.
- Exposing the Existing Funtion on the Network: Web services enable remote invocation of managed code over HTTP, exposing program functionality for use by other applications.
- Interoperability: Applications communicate and share data seamlessly through web services, promoting platform independence. For instance, VB and .NET can interact with Java services.
- Standardized Protocol: Web services employ industry-standard protocols across layers (Service Transport, XML Messaging, Service Description, and Service Discovery), fostering competition, choice, and quality.
- Low Cost Communication: Utilizing SOAP over HTTP, web services leverage existing low-cost internet infrastructure, offering a economical alternative to proprietary solutions like EDI/B2B.

8. List and discuss the characteristics of Web Services.
- XML-BASED: Web services utilize XML for data representation and transportation, ensuring interoperability across diverse networks, operating systems, and platforms.
- Loosely Coupled: Web service consumers remain independent as the interface can evolve without affecting client interaction, unlike tightly coupled systems requiring simultaneous updates.
- Coarse-Grained: Web services, unlike fine-grained methods in Java, define broad services accessing optimal business logic, enhancing efficiency and practicality.
- Synchronous or Asynchronous: Synchronous calls involve client waiting, while asynchronous operations allow clients to perform other functions before retrieving results later, supporting loosely coupled systems.
- Supports RPCs: Web services enable clients to invoke remote procedures through an XML-based protocol, exposing input and output parameters for support.
- Support Document Exchange: Web services facilitate seamless exchange of XML-based documents, from simple data representation to complex documents, enhancing business integration.
9. List and discuss the distinct roles in Web Services Architecture.
- Provider: Creates and offers web services to client applications seeking functionality, facilitating accessibility and use.
- Requestor: Client application, regardless of language, seeking functionality through web services like .Net or Java.
- Broker: Application providing UDDI access, aiding client applications in discovering web services efficiently.
- Publish: Providers notify the broker (service registry) of web service existence, making it accessible to clients.
- Find: Requestors consult the broker to discover published web services, streamlining the search process.
- Bind: Requestors, armed with broker-provided information, invoke or bind with discovered web services effectively.
10. List and discuss the Web Services Components.
- UDDI: Essential protocol and platform framework for web service discovery, offering a standardized method for providers to publish information seamlessly.

- SOAP:Utilizing XML for messages, this protocol enables structured data exchange between services, fostering standardized formatting within messages for seamless communication.
