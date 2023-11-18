## Assignment in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture(SOA).
- Service-oriented architecture (SOA) is an architectural style in which applications and systems are built from loosely coupled, interoperable services.

2. List and discuss the characteristics of SOA.
- Applications are created as a group of self-contained services.
- Standardized interfaces are used by services to communicate, which reduces the 
reliance on the implementation details.
- SOA relies to a standardized protocols and technologies which ensures the discoverability of the services.
- Services can be created using different programming langguages for an easy integration.
- Services are discoverable and connected to service registries and some discovery tools.
- Services are adaptable to different application and integrations for a better efficiency and to lower costs.
- Location of the services are hidden from the consumers to enable a flexible and scalable deployment.
- Services has their own lifecycle, management, and structures.

3. Define Microservices.
- Microservices is a software development approach that structures an application as a suite of small, independent services.

4. List and discuss the benefits of using Microservices.
- Microservices allow teams to work independently on smaller parts of the application, enabling a quicker development.
- Microservices lets you scale up only the parts of the application that needs it.
- If one microservice fails, the rest of the application keeps working, making the entire system more durable.
- With microservices, you can choose the best tools for the job, without being locked into a specific vendor.
- Microservices help teams work better together, leading to better code and more features.
- Microservices make it easy to release new features and fizes bug quickly, which keeps users updated and maintained.
- Microservices make it easier to keep sensitive data secure and compliant with data privacy regulations.
- Microservices make it easy to change your application as your business grows.

5. List and discuss the similarities and differences of SOA and Microservices.
- Both SOA and microservices are architectural styles that break down complex applications into smaller and  more manageable components. This makes applications easier to develop, deploy, and maintain.
- Both SOA and microservices focus on using services, which are independent units of functionality that interact with each other through well-defined interfaces.
- Both SOA and microservices advocate for loosely coupled and highly cohesive services. This means that services should operate independently and focus on a singular, clearly defined function.
- SOA services are typically broader and less granular than microservices. Microservices are designed to be narrow and granular, with each service performing a specific task.
- SOA services interacts using diverse protocols, including synchronous and asynchronous. Microservices primarily rely on asynchronous protocols, such as HTTP and REST, for communication.
- The deployment of SOA services is typically centralized, utilizing an enterprise service bus (ESB) as the central point. While Microservices offers  flexibility in deployment that allowing them to be deployed on-premises, in cloud environments, or in a hybrid combination of both.
- SOA services typically store their data in a centralized data repository. While Microservices employ various data management approaches including distributed databases, CQRS (Command Query Responsibility Segregation), and event sourcing.