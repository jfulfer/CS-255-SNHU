# CS-255-SNHU
CS-255 System Analysis and Design

1. Briefly summarize the DriverPass project. Who was the client? What type of system did they want you to design?

The DriverPass project was designed for DriverPass, a company aimed at improving DMV test preparation for customers through both online and on-the-road training services. The system required features to allow customers to schedule driving lessons, track progress, and receive DMV updates. It also supported role-based access for various users, including administrators, secretaries, IT staff, and students. This cloud-based system needed to be accessible via web browsers and mobile devices, with secure login, scheduling functionalities, and reporting tools.

2. What did you do particularly well?

I excelled in creating a detailed and organized System Design Document. This included clear UML diagrams—Use Case Diagrams, Activity Diagrams, and a Class Diagram—that effectively captured user interactions, system workflows, and data structures. Additionally, I addressed technical requirements comprehensively by balancing functionality, security, and scalability in my design. I also ensured alignment with client needs, such as role-based access controls and DMV update notifications.

3. If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

If I could revise one part, it would be the Class Diagram. While it covers the major components such as Users, Lessons, and Tests, I would refine the relationships and cardinalities between classes to better represent data flows and ensure more flexibility for future system expansions. For example, introducing a more modular approach to the "Packages" class could allow easier customization without developer intervention.

4. How did you interpret the user’s needs and implement them into your system design? Why is it so important to consider the user’s needs when designing?

I interpreted the user’s needs by carefully analyzing the DriverPass interview transcript and identifying key requirements such as lesson scheduling, package selection, DMV compliance, and role-based access. The Activity Diagrams and Use Case Diagrams helped map these needs into practical workflows. For example, I ensured that customers could easily book, cancel, or modify lessons online and that admins could manage system usage.

Considering the user's needs is essential because it ensures that the system is usable, efficient, and directly solves the client’s problems. Ignoring user needs can result in a system that fails to meet expectations, causing frustration and financial losses.

5. How do you approach designing software? What techniques or strategies would you use in the future to analyze and design a system?

I approach designing software systematically, starting with:

1.) Requirement Analysis: Gathering detailed user and system requirements through interviews, documents, and feedback.
2.) Design Phase:
  - Creating UML Diagrams (Use Case, Activity, and Class diagrams) to visualize system structure and workflows.
  - Planning a modular architecture that balances functionality and scalability.
3.) Security and Performance Focus: Incorporating security measures such as role-based access control (RBAC) and encryption to protect user data.
4.) Iterative Development: Using Agile principles to adapt the design based on client feedback.
