## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture (SOA).
Based on my understanding from the handout, Service-Oriented Architecture (SOA) is a software development approach that focuses on creating reusable software components, or services. These services are specialized to handle distinct business tasks or functions, each dedicated to performing a specific process or job.

2. List and discuss the characteristics of SOA.
There are 9 characteristics of SOA which are: Standardized Service Contracts: In this characteristic, the contracts should be formal and standardized. It should express their purpose and capabilities Loose Coupling: This is a way of connecting different services in a system which minimize on each other. It create specific relationships in which each services, in my opinion, has a specific role or job to do that helps reduce dependencies. Abstraction: This characteristic perform actions without revealing all the actions that they do to the outside world. They hide those unnecessary informations to avoid overwhelming users. Service Reusability: This characteristic is intended to maximize service reuse Authonomy: The services should have control to the logic and to achieve that, the services must be more isolated. Statelessness: The services should not have a state. Discoverability: The services should be discoverable. Composability: The services divides complex problems into smaller, more manageable pieces. It allows flexible service contracts to accommodate various types of interactions and integrations. Interoperability: It ensures that services adhere to widely accepted standards, enabling various users or systems with different technologies to effectively utilize the service. It's so commonly expected in modern practices that its significance as a guiding principle is sometimes overlooked.

3. Define Microservices.
Microservises is similar to SOA, however, instead of implementing them across an entire enterprise, microservices are commonly employed to construct individual applications that enhance their agility, scalability, and resilience.

4. List and discuss the benefits of using Microservices.
There are 3 benefits of using Microservices Independently Deployable: Microservices offers organizations a solution to the frustration of long delays associated with implementing minor changes, because of their smaller size and standalone nature. Organizations can swiftly operate in response to changing needs, benefiting from clearer communication patterns and easily integrating new team members into the codebase, boosting both speed and team morale by forming smole and agile teams around individual services. Right tool for the job: Traditional designs make it difficult to optimize for certain activities because applications frequently share a common stack and database. The independent operation of each component in a microservices architecture, on the other hand, enables customized technology stack optimization for distinct services. Because of this flexibility, applications made out of smaller services may adjust to changing technologies more easily and at a lower cost. Precise Scaling: Microservices minimize infrastructure needs by enabling the independent deployment and scalability of individual services. This precision in scaling lowers infrastructure costs by scaling only the essential components rather than the complete application.

5. List and discuss the similarities and differences of SOA and Microservices.
Both SOA and Microservices are approaches that focuses on building software systems by decomposing their functionalities into smaller components that are easier to manage. Both are reusable. Also, these two promotes service autonomy where it can operate independently. Differences
SOA typically focuses on creating larger, standardized services that can encompass multiple functionalities within an organization. It often involves a more centralized approach to service management and interoperability standards, aiming for broad integration across the enterprise. Conversely, Microservices emphasize fine-grained, single-purpose services deployed independently, with a strong focus on individual service autonomy, technology diversity, and agility within smaller, more specialized teams.

6. Define Web Services.
Web services can be likened to productss offered for sale either in physical stores or online, but in this case, they are exclusively accessible through the internet. Web services are software programs created to facilitate standard protocols-based communication over the internet between various devices or applications, allowing for the smooth transfer of information and functionality.

7. List and discuss the benefits of using Web Services.
Benefits of Using Web Services
Exposing the Existing Function on the network
- By exposing functions on the network,  it become accessible to other applications.

Interoperability
- Web services act as a bridge between various applications, fostering communication and enabling the exchange of data and services among disparate systems. 

Standardized Protocol
- This ensures compatibility and consistency in data exchange between systems.

Low Cost Communication 
- This optimizes resource utilization and minimizes additional expenditure, making it a cost-effective solution for enabling communication and data exchange between applications.


8. List and discuss the characteristics of Web Services.
Characteristics of Web Services  
XML-Based
- Web services use a language called XML for sharing and transporting data, allowing different systems to communicate without being restricted by specific technologies or platforms.

Loosely Coupled
- Web services enable connections between systems that can evolve independently, allowing changes to the service without disrupting its users, promoting adaptability.

Coarse-Grained
- They organize tasks in a way that makes sense for businesses, focusing on larger operations rather than small individual tasks for efficient functioning.

Ability to be Synchronous or Asynchronous
- Web services can operate in real-time or delayed modes, either waiting for tasks to finish or proceeding without waiting for immediate completion, offering flexibility in execution.

Supports Remote Procedure Calls (RPCs)
They enable systems to call and use functions located on other systems through a standardized method, ensuring interoperability.

Supports Document Exchange
Web services allow the exchange of various kinds of information, from simple data like addresses to complex documents such as contracts, promoting seamless business integration.


9. List and discuss the distinct roles in Web Services Architecture.
WEB SERVICES ARCHITECTURE  
Provider - Creates and offers the web service to client applications seeking specific functionalities.

Requestor - Represents the client application that seeks functionality through a web service.

Broker - Acts as an intermediary system that grants access to a service directory (UDDI), aiding client 
applications in finding web services.

Publish - Providers notify the broker (service registry) of their web service's existence, making it accessible to potential clients.

Find - Requestors consult the broker to discover available web services.

Bind - Using the information obtained from the broker, requestors connect or invoke the web service to utilize its functionalities.

10. List and discuss the Web Services Components.
SOAP
 It's a messaging protocol used for exchanging structured information in web services, facilitating communication between different systems over the internet.

WSDL
WSDL is a standardized language used to describe the functionalities, operations, and endpoints offered by a web service, aiding in understanding how to interact with the service.

UDDI
UDDI serves as a directory service allowing businesses to register and locate web services, helping clients discover and connect with available services.

Soap Web Services
These are web services that utilize SOAP as their messaging protocol, allowing diverse systems to communicate by exchanging structured information over standardized protocols like HTTP.

