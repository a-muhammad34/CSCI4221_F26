## Amirah Muhammad_G1

## Meeting 4 — October 22 2026 11:00 AM-12:00 PM | Duration 1 Hour

We discussed the issues given in the project 4 instructions and our next tasks individually.

 ## Discussion
Question 1. What is included in the architecture design?
The overall organization of the software
How the software is decomposed into components
The server organization
The technologies used to build the software

Question 2. What is the architecture of a software?
Architecture is the fundamental organization of a software system, embodied in its components, their relationships to each other and to the environment, and the principles guiding its design and evolution. Architecture can be the structure of a system or the process of defining that structure.

Question 3. What is a component of the software architecture?
A component is an element that implements a coherent set of functionality or features. It can be seen as a collection of one or more services that other components may use. When designing the architecture you design the component’s interface and leave its implementation to a later stage.

Question 4. What are the non-functional system quality attributes?
Responsiveness: returns results to users in a reasonable time.
Reliability: features behave as developers and users expect.
Availability: the system can deliver its services when requested.
Security: protects itself and users’ data from unauthorized attacks and intrusions.
Usability: users can access the features they need and use them quickly and without errors.
Maintainability: the system can be updated and new features added without undue cost.
Resilience: the system keeps delivering services during partial failure or external attack.

Question 5. What are the architecture design issues?
Non-functional product characteristics: they affect all users, and some oppose each other, so you can optimize only the most important.
Product lifetime: a long lifetime needs an architecture that can evolve to take on new features and technology.
Software reuse: reusing large components saves effort but constrains your architectural choices.
Number of users: the user count can change quickly, so the system must scale up and down easily.
Software compatibility: compatibility with other software may limit choices, such as which database you can use.


Question 6. What architectural design questions should be asked?
How should the system be organized as a set of architectural components, each providing a subset of the functionality, while delivering the security, reliability and performance you need?
How should these components be distributed and communicate with each other?
What technologies should you use to build the system, and which components should be reused?

Question 7. How are components organized in architecture design?
Abstraction and decomposition: at the architectural level you focus on large-scale components, then break them into finer-grain components.
Layered models: these are commonly used to show how a system is composed. Each layer is a separate area of concern. Components within a layer are independent and don’t overlap in functionality. Lower layers provide general functionality so it isn’t replicated higher up. Components at level X should interact only with the APIs of level X-1.
Design guidelines: separation of concerns, stable interfaces, and implement once.
Cross-cutting concerns: concerns such as security affect every layer, which is why improving security after design is often difficult.
Typical web application layers: browser/mobile user interface, authentication and UI management, application-specific functionality, basic shared services, and database and transaction management.
Distribution architecture: it defines the servers and the allocation of components to them. Examples are multi-tier client-server and service-oriented architectures.


Question 8. Where does the architectural complexity come from?
Complexity arises from the number and nature of the relationships between components

Localize relationships: define related components in the same module.
Reduce shared dependencies: a change to a shared component or data affects every component that depends on it, so prefer local data and avoid sharing where possible. The more complex a system, the harder and more expensive it is to understand and change, and the more likely programmers are to introduce bugs and vulnerabilities.

Question 9. Name four architecture designs.

Layered architecture
Client-server architecture
Multi-tier client-server architecture
Service-oriented architecture


Question 10. What are the technology choices in architecture design?

Database: a relational SQL database (e.g. MySQL, suited to transactions and predictable, simple data) or a NoSQL database (e.g. MongoDB, more flexible and efficient for big data).
Platform: a mobile app, a web platform, or both. Mobile brings issues such as intermittent connectivity, limited processor power, battery life and slow on-screen keyboards.
Server: in-house servers or a public cloud, and if cloud, which provider (Amazon, Google, Microsoft or another).
Open source: whether to reuse open-source components. This cuts cost and time to market but constrains you, and licenses, maturity and support matter.
Development tools: these embed architectural assumptions that can limit your choices, and team familiarity also influences decisions.

End of discussion

The assignments remain the same. We are continuing to finish our tasks

| PBI                                                          | Status                   | Sprint  | Estimate                       | Assigned     | Reviewer        |
| ------------------------------------------------------------ | ------------------------ | ------- | ------------------------------ | ------------ | --------------- |
| 1. HTML/CSS: finish Building detail / Floor selection screen | In progress              | 2 weeks | One senior person for 8 hours  | Jada Rodgers | Garret Godwin   |
| 2. HTML/CSS: connect Floor 1 row to Floor / Location list    | In progress              | 2 weeks | One senior person for 4 hours  | Jada Rodgers | Amirah Muhammad |
| 3. Compare screens to Figma designs and fix differences      | In progress              | 2 weeks | One senior person for 8 hours  | Jada Rodgers | Amirah Muhammad |
| 4. HTML/CSS: Settings page from Garret's Figma design        | In progress              | 2 weeks | One senior person for 12 hours | Jada Rodgers | Garret Godwin   |
| 5. JavaScript: navigation between screens and behavior       | Ready for implementation | 2 weeks | One senior person for 24 hours | Jada Rodgers | Garret Godwin   |
