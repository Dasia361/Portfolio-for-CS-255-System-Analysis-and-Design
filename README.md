## CS 255 DriverPass Project Reflection

### Briefly summarize the DriverPass project. Who was the client? What type of system did they want you to design?

The client for this project was DriverPass, a company that wanted to provide students with better preparation for their driving tests. The goal was to design a system that would allow customers to create accounts, purchase training packages, take practice tests, and schedule driving lessons. The system also needed to support employees, drivers, administrators, and updates from the DMV.

### What did you do particularly well?

I think I did particularly well at taking the requirements for DriverPass and turning them into a system design. Creating the UML diagrams helped me understand how different parts of the system would interact with each other. I was also able to organize the requirements so that the needs of both customers and employees were represented in the design.

### If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

If I could revise one part of my work, I would improve some of my UML diagrams. As I worked through the course, I became more comfortable understanding how relationships, actions, and decisions should be represented. I would go back through the diagrams and make some of the connections clearer and make sure the layout is as easy to follow as possible.

### How did you interpret the user's needs and implement them into your system design? Why is it so important to consider the user's needs when designing?

I interpreted the user's needs by identifying what each type of user needed to accomplish within the DriverPass system. For example, customers needed to schedule lessons and access training materials, while employees needed tools to manage reservations, accounts, drivers, and other system information. Considering the user's needs is important because a system can technically work but still fail if it is difficult to use or does not solve the problems the users actually have. 

### How do you approach designing software? What techniques or strategies would you use in the future to analyze and design a system?

I approach software design by first understanding the problem and identifying the requirements before deciding how the system should be built. I would continue using techniques such as reviewing business requirements, identifying different users and their needs, and creating UML diagrams to visualize the system before implementation. In future projects, I would also continue reviewing and revising my designs as I learn more about the system because the design process can reveal requirements or problems that were not obvious in the beginning.


# CS 230 The Gaming Room Project Reflection

## Client and Software Requirements

The client was The Gaming Room, which wanted to expand its Android game, Draw It or Lose It, into a web\-based application accessible across different platforms\. The game needed to support multiple teams and players, unique identifiers, and checks for duplicate names\. My documentation described the Java domain prototype and recommended an approach for future browser access, timed gameplay, persistent storage, and security.

## What I Did Well

I did particularly well at connecting the client’s requirements to specific design decisions\. I explained the relationships between games, teams, and players and how inheritance and the singleton pattern supported the prototype\. I also compared operating platforms and explained my recommendations for a Linux\-based server, storage, memory management, and security\. The document clearly distinguished existing prototype features from proposed production features\.

## How the Design Document Helped With Development

Working through the design document helped me organize the application’s classes and responsibilities\. Defining how games contain teams and teams contain players provided a clear structure for the Java code\. Documenting name checks and identifiers also helped clarify how objects should be created and managed\. Having these decisions written down made it easier to connect the code to the client’s requirements\.

## What I Would Revise

I would expand the system architecture section with a deployment diagram showing the browser clients, application servers, database, and image storage\. Although the recommendations explain these components, a diagram would make their connections easier to understand\. I would also include a sample request flow showing how a player’s guess reaches the server and how the updated game state returns to players\.

## Interpreting and Addressing User Needs

I translated the client’s needs into requirements for organizing games, teams, and players while planning for access from different devices\. The prototype addressed the domain structure and duplicate\-name checks, while the proposed design addressed responsive browser access and server\-controlled timing\. Considering user needs is important because the system must support how people actually play\. A technically functional application would still fall short if players experienced confusing controls, inconsistent scores, or unfair timing\.

## My Design Approach and Future Strategies

I approached the design by identifying requirements and constraints, examining the domain model, and comparing platforms before making recommendations\. I considered compatibility, cost, performance, and security alongside the application’s functionality\. For future projects, I would use UML diagrams, small prototypes, and a requirements checklist to connect each design decision to a client need\. I would also plan measurable tests for concurrent users, recovery, and browser compatibility so recommendations could be evaluated before a full deployment\.

## AI Acknowledgment

I used OpenAI ChatGPT to assist with drafting and organizing this README reflection based on my completed software design document\. AI assistance used during the projects is acknowledged separately in the design document\.
