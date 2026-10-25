# CS-230: Operating Platforms

## Project Overview

This repository contains the software design document developed for **The Gaming Room**, a client of Creative Technology Solutions (CTS), as part of Southern New Hampshire University's CS-230: Operating Platforms course.

The project focuses on evaluating operating platforms, applying object oriented design principles, and recommending an appropriate architecture for a scalable, cross platform gaming application.

The Gaming Room was a client seeking to expand its existing Android based game, *Draw It or Lose It*, into a web based application accessible across multiple operating platforms. The game involves teams competing to identify images displayed progressively during timed rounds.

The client required support for multiple games, teams, and players while ensuring unique game and team names. The application also needed to maintain consistent game information, manage player interactions, and support access through desktop and mobile browsers. The primary objective was to design a scalable solution that could accommodate a larger user base without requiring separate native applications for each operating system.

One aspect I believe I handled particularly well was connecting the client's business requirements to specific technical design decisions. Rather than simply identifying different operating platforms, I evaluated their capabilities, limitations, licensing considerations, and suitability for hosting the application.

I also demonstrated an understanding of object-oriented programming principles by documenting the relationships between the Game, Team, Player, Entity, and GameService classes. Incorporating the Singleton and Iterator design patterns helped establish a structured approach to managing game instances and searching collections. These decisions supported the client's requirements while maintaining an organized software design.

Developing the software design document helped me understand the importance of establishing requirements and system architecture before beginning implementation. By identifying the responsibilities of individual classes and their relationships, I was able to better visualize how the application components should interact.

The UML class diagram was particularly useful because it translated abstract requirements into a structured representation of the software. This approach helped clarify how inheritance, encapsulation, and design patterns could support code organization and maintainability. I also found that documenting design constraints encouraged me to consider potential problems before they became implementation challenges.

If I could revise one aspect of the project, I would expand the system architecture documentation to provide a more detailed representation of the application's distributed environment.

Although the existing design explains the relationships between classes and recommends an appropriate hosting platform, an additional architecture diagram could illustrate communication between browser clients, application servers, and the database. I would also explore how load balancing and centralized data storage could support increasing numbers of concurrent users.

These improvements would make the document more useful to a development team preparing to implement the application in a production environment.

I approached the client's requirements by first identifying the primary business objectives and translating them into technical specifications. For example, the need to support users across different operating systems influenced my recommendation to use a browser based application with a centralized server.

The requirement for unique game and team names influenced the design of the application's classes and collection management methods. Similarly, the need to maintain consistent game information contributed to the use of the Singleton pattern in the Java prototype.

Considering user needs is essential because technical functionality alone does not guarantee that an application will be successful. A well designed system must also be accessible, reliable, maintainable, and capable of supporting the client's long term objectives.

My approach involved reviewing the client's requirements, identifying design constraints, developing a UML class diagram, and evaluating potential operating platforms before recommending a deployment strategy.

I used object oriented design principles to organize application responsibilities and considered how operating system characteristics could influence performance, security, and scalability. Comparing Linux, Windows, macOS, and mobile platforms helped me understand the importance of selecting technologies based on project requirements rather than personal familiarity.

In future projects, I would continue using requirements analysis, UML modeling, and platform evaluation as foundational design techniques. I would also incorporate early security assessments, performance considerations, and more detailed architecture diagrams to identify potential limitations before implementation.

Overall, this project reinforced my understanding that successful software development requires thoughtful planning, clear documentation, and a strong connection between business requirements and technical decisions.

AI Usage Acknowledgment
Generative AI was used to assist with organizing and refining the written portfolio reflection, improving clarity, and reviewing alignment with the assignment requirements. The final content was reviewed for accuracy and consistency with the completed course project.
