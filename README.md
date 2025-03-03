# Course Documentation

![1574369621523](https://github.com/user-attachments/assets/4eae8c90-a124-4962-af48-39c87cca5ec2)

# Table of Contents:

<!-- TOC toc.levels=2 -->

- ## [Software Development Life Cycle](#software-development-life-cycle)
  - #### [Phases](##phases)
  - #### [Roles of SDLC](##roles-of-sdlc)
- ## [Agile And Scrum](#agile-and-scrum)
  - #### [What is Agile Methodology?](#what-is-agile-methodology)
  - #### [Purposes of Agile](#purposes-of-agile)
  - #### [What is waterfall?](#what-iswaterfall)
  - #### [What is agile?](#whatis-agile)
  - #### [Agile Model Advantages](#agile-model-advantages)
  - #### [Waterfall Model Advantages](#waterfall-model-advantages)
  - #### [Waterfall Model Disadvantages](#waterfall-model-disadvantages)
  - #### [When to Use Agile?](#when-to-use-agile)
  - #### [When to Use Waterfall?](#when-to-use-waterfall)
  - #### [Best Practices for Agile](#best-practicesfor-agile)
  - #### [Best Practices for Waterfall](#best-practices-for-waterfall)
  - #### [Agile Frameworks](#agile-frameworks)
  - #### [Scrum Framework in Agile](#scrum-framework-in-agile)
  - #### [Benefits of Scrum](#benefits-of-scrum)
- ## [Web Development Stacks]
- ## [Git Cersion Control]

<!-- /TOC -->
# Software Development Life Cycle
Software Development Life Cycle provides a practical framework you can apply to your product and improve your processes. It helps us meet customers’ demands, needs, and expectations. You can outline and define a detailed plan for stages, phases, and requirements with SDLC. It covers planning, estimating, and scheduling.

![1  SDLC](https://github.com/user-attachments/assets/71f861d8-bfa1-4b4d-baac-cf15cf280133)

## Phases

1- Analysis phase:

- Critical phase within the Software Development Life Cycle (SDLC) where detailed requirements are gathered and analyzed to ensure a clear understanding of the project’s scope and objectives.
- Defines functional and non-functional requirements.
- Establishes clear specifications for the system.
- Gather and document user expectations.

- Input:

   - Customer requirements
   - Business needs

- Output:

  - Software Requirement Specification (SRS)
  - User stories and use case diagrams

2- Design phase: 

- Design phase is all about building the framework. The development team is responsible for software engineering and outlines the software's functionality and aesthetic. This ultimately results in the software product. The emphasis lies on outlining the software's structure, navigation, user interfaces, and database design. This phase ensures that the software is user-friendly and performs its tasks efficiently.
- User Interface (UI) and User Experience (UX) Design Design the user interface to ensure a seamless and user-friendly experience. Consider usability, accessibility, and visual aesthetics in the design process.
- Translates requirements into a blueprint for implementation.
- Create the software’s architecture and user interfaces.

- Input:
   - SRS document

- Output:
  - System design documents
  - Database schema
  - Wireframes and UI mockups

3- Development phase:

- The development stage is the part where developers actually write code and build the application according to the earlier design documents and outlined specifications. In general, Its write the code.
- Converts design into actual software using programming languages.

- Two types:

1-Front-end Developer: someone who creates websites and web applications.

2-Back-end Developer: working on server-side software, which focuses on everything you can’t see on a website.

- Input:
  - Design documents

- Output:
 - Source code
 - Executable software

4- Testing phase:

- The testing is done to ensure that the entire application works according to the customer requirements. After testing, the QA and testing team might find some bugs or defects and communicate the same with the developers.
- Assemble the modules in a testing environment. Check for errors, bugs, and interoperability.
- Ensure that it meets the requirements and works correctly.

- Input:
  - Source code
  - Test cases

- Output:
  - Test reports
  - Bug reports

5- Deployment phase:

- Delivers the final product to the customer in a live production environment.
- Deploy the software in a production environment.
- Makes the software available to end users.

- Input:
   - Tested software

- Output:
   -Live production software

6- Maintenance phase:

- an essential component that ensures continued software functionality, handles vital repairs and updates, and ensures that the software remains relevant and usable. Also, handles enhancements and user support.

- Used for: 
  - Fix bugs
  - Update features
  - Optimize performance

- Input:
   - Feedback from users
   - Bug reports

- Output:
  - Updated versions of software
  - Performance reports


## Roles of SDLC

1-Product Owner

- Responsibilities:
   - Define product vision and roadmap.
   - Prioritize features and manage the product backlog.
   - Work with stakeholders and development teams.
   - Ensure the product meets business needs.

- Tools:
   - Product Management: Jira, Trello, Azure DevOps
   - User Feedback and Analytics: Google Analytics, Hotjar

2-Project Manager

- Responsibilities:

   - Plan, execute, and monitor projects.
   - Define project scope, budget, and timeline.
   - Manage risks and resources.
   - Communicate with stakeholders.

- Tools:

  - Project Management: Microsoft Project, Jira, Trello, Monday.com
  - Collaboration: Slack, Microsoft Teams, Zoom
  - Documentation: Confluence, Google Docs

3-Business Analyst

- Responsibilities:

   - Gather and analyze business requirements.
   - Create functional and non-functional specifications.
   - Document Software Requirement Specification (SRS).
   - Act as a bridge between stakeholders and developers.

- Tools:

   - Documentation: Microsoft Word
   - Diagrams: Microsoft Visio

4-Software Architect

- Responsibilities:

   - Design internal software structure (modules, classes, components).
   - Define coding standards and best practices.
   - Ensure maintainability and scalability of the system.

- Tools:

   - Development: Visual Studio

5-UI/UX Designer

- Responsibilities:

   - Design intuitive user interfaces and experiences.
   - Create wireframes, prototypes, and visual designs.
   - Conduct usability testing and research.

- Tools:

   - Design & Prototyping: Figma, Adobe XD, Sketch
   - Wireframing: Balsamiq, Axure RP
   - User Testing: Hotjar, UserTesting

6-Front-end Developer

- Responsibilities:

  - Develop and implement UI components.
  - Ensure responsiveness and cross-browser compatibility.
  - Optimize web performance.

- Tools:

    - Language: HTML, CSS, JavaScript
    - Framework: React.js, Angular

7-Back-end Developer

- Responsibilities:

   - Develop server-side logic and APIs.
   - Handle database interactions.
   - Ensure security, performance, and scalability.

- Tools:

   - Language: C# (.NET), Java, Python
   - Database: SQL Server, MongoDB

8-Solutions Architect

- Responsibilities:

   - Design high-level software architecture.
   - Choose technology stacks and frameworks.
   - Ensure scalability, security, and performance.
   - Guide developers on system integration.

- Tools:

  - Cloud Platform: Microsoft Azure, Google Cloud
  - Diagramming: Microsoft Visio

9-QA Engineer

- Responsibilities:

   - Develop and execute test cases.
   - Perform manual and automated testing.
   - Report and track defects.

- Tools:

   - Automated Testing: Selenium, Cypress
   - Performance Testing: JMeter, LoadRunner
   - Bug Tracking: Jira, TestRail

10-DevOps Engineer

- Responsibilities:

  - Automate deployment, integration, and monitoring.
  - Manage cloud infrastructure and CI/CD pipelines.
  - Ensure high availability and reliability.

- Tools:

   - CI/CD: Jenkins, GitHub Actions, GitLab CI/CD
   - Containerization: Docker, Kubernetes
   - Cloud Platforms: AWS, Azure, GCP

11-Data Administrator
 
- Responsibilities:

   - Design and manage databases.
   - optimize performance and indexing.
   - Ensure backup, recovery, and security.

- Tools:

    - Database Management: SQL Server Management Studio (SSMS), MySQL Workbench
    - Performance Monitoring: SolarWinds, Redgate SQL Monitor



# Agile And Scrum

![agile2](https://github.com/user-attachments/assets/0fb48620-3540-48a0-a4ab-6cd8d2fe179a) 
![scrum2](https://github.com/user-attachments/assets/e59084bb-fb18-4d5c-8493-01ceac856029)

## What is Agile Methodology?

Agile is a flexible, iterative, and collaborative approach to software development that focuses on delivering small, incremental improvements instead of a big final release. It helps teams respond quickly to changing requirements and continuously improve their software based on feedback.

## Purposes of Agile

- Deliver Value Faster: Instead of waiting months for a full product, Agile delivers small, usable features quickly.
- Adapt to Changes: Agile allows teams to adjust project goals based on customer feedback and market trends.
- Improve Collaboration: Encourages continuous communication between developers, testers, product owners, and stakeholders.
- Ensure High Quality: Frequent testing and feedback help catch bugs early, reducing costly fixes later.
- Enhance Customer Satisfaction: Customers see progress frequently and get a product that meets their real needs.


![download](https://github.com/user-attachments/assets/a6a6d090-4cf6-4105-aad3-42ebbfa3f94d)


## What is waterfall?

The waterfall project management method is a linear, step-by-step approach that's ideal for projects with a clear scope and predictable timeline. It involves rigorous planning upfront to ensure that the project stays on track, with progress tracked closely and issues addressed promptly. The Waterfall model usually includes five project management stages (or phases): initiation, planning, execution, monitoring/control, and closing.

## What is agile?

Agile project management is a flexible and iterative approach that enables teams to quickly adapt to changing project requirements and deliver high-quality results within shorter timeframes. It’s very often used in software development.

Agile methodologies are about teamwork, customer satisfaction, constant refinement, and breaking big projects into bite-sized pieces. By prioritizing collaboration and communication, agile processes enable teams to pivot and respond to evolving customer needs while maintaining a high level of flexibility. The focus on continuous improvement means that teams are always seeking ways to optimize their processes and deliver the best possible results.

### Agile Model Advantages

1- Faster Delivery: Continuous releases provide early software versions.
2- Flexibility & Adaptability: Can change requirements mid-project.
3- Customer Satisfaction: Frequent feedback ensures alignment with business needs.
4- Early Bug Detection: Continuous testing improves quality.
5- Improved Collaboration: Encourages communication between teams.

### Agile Model Disadvantages

1- Requires High Customer Involvement: Needs active participation from stakeholders.
2- Difficult to Estimate Time & Cost: Since requirements evolve, budgets and timelines can shift.
3- Not Ideal for Fixed-Scope Projects: Unnecessary complexity for well-defined requirements.

### Waterfall Model Advantages

1- Clear Structure: Well-defined phases make planning straightforward.
2- Best for Fixed Budgets & Timelines: Predictable costs and schedules.
3- Well-Documented Process: Helps in future maintenance and compliance-heavy industries.
4- Easier to Manage: Defined stages and deliverables make tracking simpler.

### Waterfall Model Disadvantages

1- Hard to Accommodate Changes: Once a phase is completed, it's difficult to go back.
2- Late Testing & Bug Fixing: Issues found late are costly to fix.
3- Higher Risk of Failure: If requirements were misunderstood, major problems arise late in the process.
4- Customer Feedback is Limited: Customers only see the product at the end.

## When to Use Agile?

Best for: Projects with changing requirements, customer involvement, and the need for continuous improvement.

- Use Agile When:

1. Requirements are Uncertain or Evolving:

If the project scope may change based on market needs or stakeholder feedback.
Example: Developing a new mobile app or SaaS platform where features change frequently.

2. Quick Delivery & Iterative Releases Are Needed:

You need fast, incremental releases instead of one big launch.
Example: A web application where features roll out gradually.

3. Customer Involvement is High:

The client or users need to provide continuous feedback.
Example: A startup building an MVP (Minimum Viable Product) with user testing.

4. Complex or High-Risk Projects:

If the project is highly technical, Agile helps mitigate risks early.
Example: AI/ML applications that need regular model retraining and fine-tuning.

5. Teams Need Flexibility & Collaboration:

If the team prefers daily stand-ups, real-time collaboration, and self-management.
Example: Agile software development teams using Scrum or Kanban.


## When to Use Waterfall?

Best for: Projects with well-defined requirements, fixed budgets, and strict regulatory needs.

- Use Waterfall When:

  1. Requirements Are Fixed & Well-Defined:

If all requirements are clear from the start and unlikely to change.
Example: Banking system software with strict compliance rules.

  2. Project Has a Fixed Budget & Timeline:

If the project scope, cost, and schedule must be predefined and controlled.
Example: A government project or defense system with strict deadlines.

  3. Customer Involvement is Limited:

If the client only wants to see the final product and does not need regular updates.
Example: Enterprise software development for internal business use.

  4. High-Risk, High-Precision Projects:

If errors are costly and unacceptable, like in medical software or aerospace projects.
Example: Hospital patient record systems, air traffic control software.

  5. Well-Documented & Predictable Process Needed:

If extensive documentation is a requirement for compliance.
Example: Pharmaceutical software adhering to FDA regulations.

![Agile_vs_Waterfall_Differences_in_Software_Development_Methodologies](https://github.com/user-attachments/assets/b5dcde9d-d91f-44f8-8f88-d0771501cee3)

### Best Practices for Agile

1- Use Scrum or Kanban: Choose the right Agile framework based on project needs.
2- Short Iterations (Sprints): Deliver features in small, incremental steps.
3- Continuous Testing: Automate testing to ensure quality at every stage.
4- Daily Stand-ups: Keep team communication strong to address blockers.
5- Backlog Grooming: Regularly refine and prioritize requirements.
6- Retrospectives: Improve processes after each sprint.

### Best Practices for Waterfall

1- Define Requirements Clearly: Ensure detailed documentation before development starts.
2- Stick to the Plan: Follow the structured approach to avoid unnecessary delays.
3- Proper Documentation: Maintain extensive documentation for future reference.
4- Allocate Time for Testing: Ensure sufficient time for final testing and bug fixing.
5- Set Realistic Milestones: Break down the project into achievable phases.

## Agile Frameworks


1- Scrum:

It is Most Common.

Best For: Software development, IT projects, and fast-paced teams.

2- Kanban:

It is Visual Workflow Management

Best For: Continuous delivery, operations, and support teams.

3- Crystal Agile:

It is People-Centric Agile Approach.

Best For: Small teams with a focus on communication & collaboration.

4- Lean Agile:

It is Eliminating Waste and Maximizing Value.

Best For: Startups and teams focusing on efficiency & minimal waste.

## Scrum Framework in Agile

Scrum is an Agile framework used to develop, deliver, and sustain complex products through iterative and incremental work. It provides a structured yet flexible approach to project management by emphasizing teamwork, accountability, and continuous improvement.

1- Scrum Roles

1. Product Owner (PO)

Represents the customer/stakeholders.
Defines and prioritizes the Product Backlog (a list of features, changes, and fixes).
Ensures the development team delivers value to the business.
Makes decisions about the product scope and direction.
Works closely with stakeholders and the development team.

2. Scrum Master

Acts as a facilitator and coach for the Scrum Team.
Ensures that Scrum principles and best practices are followed.
Removes obstacles that might slow down the team.
Helps the Product Owner refine backlog items.
Shields the team from external interruptions.

3. Development Team

Cross-functional team (developers, testers, designers, etc.).
Self-organizing and accountable for delivering a working product increment at the end of each Sprint.
Collaborates with the Product Owner to clarify requirements.
Estimates tasks and plans work during Sprint Planning.
Delivers potentially shippable product increments each Sprint.

2- Scrum Events:

1. Sprint

A fixed-length iteration (usually 1-4 weeks, commonly 2 weeks).
Starts immediately after the previous Sprint ends.
Goal: Deliver a potentially shippable product increment.
The scope can be adjusted, but no changes should disrupt the Sprint Goal.

2. Sprint Planning

Duration: ~4-8 hours for a 4-week Sprint (shorter for smaller Sprints).
Attendees: Product Owner, Scrum Master, Development Team.
Purpose: Decide what work will be completed in the upcoming Sprint.

Two parts:
WHAT will be delivered? (Product Owner presents priorities)
HOW will it be done? (Development Team breaks down work)

3. Daily Scrum

Duration: 15 minutes, every day.
Attendees: Development Team (Scrum Master and Product Owner can attend but shouldn’t disrupt).
Purpose: Sync the team’s work and plan the day.

4. Sprint Review

Duration: ~1-4 hours (depending on Sprint length).
Attendees: Scrum Team, stakeholders.

Purpose:
Showcase the completed work.
Gather feedback from stakeholders.
Discuss possible changes for future Sprints.

5. Sprint Retrospective

Duration: ~1-3 hours.
Attendees: Scrum Team.

Purpose:
Reflect on the past Sprint.
Identify what went well, what didn’t, and what can be improved.
Actionable improvements for the next Sprint.

3- Scrum Key Deliverables:

1. Product Backlog

A prioritized list of everything needed in the product.
Maintained by the Product Owner.
Items are refined continuously.

2. Sprint Backlog

A set of tasks selected for the Sprint from the Product Backlog.
Owned by the Development Team.
Includes a Sprint Goal.

3. Increment

A working version of the product delivered at the end of each Sprint.
Must meet the Definition of Done (DoD).

**Benefits of Scrum** 

Faster delivery of high-quality products.
Increased collaboration and transparency.
Continuous improvement through feedback loops.
More flexibility in handling changing requirements.

# Web Development Stacks

A web application consists of multiple components that work together to deliver functionality, maintain security, and ensure scalability. These components can be divided into frontend (client-side), backend (server-side), and infrastructure services.

**1- Frontend (Client-Side)**

The frontend is what users interact with. It runs in the browser and communicates with the backend.

Key Components:

**1. User Interface (UI)**

HTML (Structure)
CSS (Styling)
JavaScript (Behavior & Interactivity)
Frontend frameworks (e.g., React, Angular, Vue.js)

**2. Client-Side Logic**

Handles UI interactions, form validations, and user input.
Fetches data from the backend via APIs (AJAX, Fetch, Axios).

**3. Static Assets**

Images, fonts, CSS files, JavaScript files, etc.

**4. Progressive Web App (PWA) Features** 

Service Workers (Offline functionality)
Web Push Notifications
App Manifest for mobile-friendly experiences

**2- Backend (Server-Side)**

The backend handles business logic, data processing, authentication, and communication with databases.

**Key Components:**

**1. Web Server**

Handles HTTP requests and serves responses.
Examples: Nginx, Apache, IIS.

**2. Application Server**

Processes business logic.
Frameworks: .NET, Node.js, Spring Boot, Django, Laravel.

**3. Database Server**

Stores and manages data.
SQL Databases: MySQL, PostgreSQL, SQL Server.
NoSQL Databases: MongoDB, Firebase, Cassandra.

**4. APIs (REST, GraphQL, gRPC)**

Allows the frontend to communicate with the backend.
Examples: Express.js, ASP.NET Web API, FastAPI.

**5. Authentication & Authorization**

Manages user access.
OAuth, JWT, OpenID, SAML.

**6. Caching Layer**

Improves performance by storing frequent requests.
Examples: Redis, Memcached.

**7. Messaging & Event-Driven Architecture**

Handles background tasks & real-time communication.
Message brokers: RabbitMQ, Kafka.
WebSockets for real-time updates.

**8. File Storage**

Manages user-uploaded content.
Local: File System.
Cloud: Amazon S3, Google Cloud Storage.

***3- Services***

These services ensure security, scalability, and performance.

**Key Services:**

**1. Load Balancer**

Distributes traffic across multiple servers.
Examples: AWS Elastic Load Balancer, HAProxy.

**2. CDN (Content Delivery Network)**

Speeds up content delivery by caching assets closer to users.
Examples: Cloudflare, Akamai.

**3. Logging & Monitoring**

Tracks application health & errors.
Tools: Prometheus, ELK Stack (Elasticsearch, Logstash, Kibana), New Relic.

**4. CI/CD (Continuous Integration & Deployment)**

Automates code testing & deployment.
Tools: GitHub Actions, Jenkins, GitLab CI/CD.

5. Security Services

Firewalls, DDoS protection, Intrusion Detection Systems (IDS).
Examples: WAF (Web Application Firewall), Cloudflare Security.

6. Containerization & Orchestration

Deploy apps in isolated environments.
Tools: Docker, Kubernetes.

7. Cloud Services

Hosting & computing platforms.
Examples: AWS, Azure, Google Cloud.

8. Third-Party Integrations

Payment gateways: Stripe, PayPal.
Email services: SendGrid, Mailgun.
Analytics: Google Analytics, Mixpanel.

4. Web Application Architecture Types

1. Monolithic Architecture

Entire application is a single unit.
Simpler but harder to scale.

2. Microservices Architecture

Application is broken into independent services.
More scalable but complex.

3. Serverless Architecture

Uses cloud functions (AWS Lambda, Azure Functions).
No need to manage servers.

4. Single Page Application (SPA)

Frontend dynamically updates without full page reload.
Examples: React, Vue, Angular.

Web Development Stacks

1- MERN Stack (MongoDB, Express.js, React, Node.js)

Where to Use: Dashboards, interactive applications, e-commerce platforms.

When to Use: When frontend interactivity and performance are priorities.

Key Features:
React's component-based UI improves frontend performance.
Node.js enables non-blocking, event-driven backend execution.
Great for single-page applications (SPAs).

2- Django Stack (Python, Django, PostgreSQL)

Where to Use: Data-intensive applications, analytics dashboards, machine learning applications.

When to Use: When security and scalability are important.

Key Features:
Built-in authentication and security features.
Python-based backend simplifies integration with data analytics.
ORM simplifies database interactions.

3- Spring Boot Stack (Java, Spring Boot, PostgreSQL)

Where to Use: Enterprise applications, financial systems, government platforms.

When to Use: When building secure, scalable, high-performance enterprise applications.

Key Features:
Built-in security and authentication.
Ideal for microservices architecture.
Strong integration with enterprise databases.

4- .NET Stack (ASP.NET Core, C#)

Where to Use: Corporate portals, SaaS applications, enterprise software.

When to Use: When working within the Microsoft ecosystem.

Key Features:
High performance and scalability.
Strong security features.
Excellent cloud and API support.

5- Laravel Stack

Where to Use: Business applications, SaaS, CRM, CMS (like WordPress alternatives), e-commerce.

When to Use: When you need rapid development, clean architecture, built-in security, and easy API integration.

Features:

1- MVC Architecture	

Laravel follows the Model-View-Controller (MVC) pattern, making code structured and maintainable.

2- Blade Templating	

Built-in templating engine for frontend rendering.

3- Routing System	

Simple and efficient routing with middleware support.

4- Security	

Built-in authentication, role-based access control (RBAC), CSRF protection.

5- API Development	

Laravel provides built-in support for RESTful APIs, JSON responses, and GraphQL integration.

6- Task Scheduling	

Laravel Scheduler helps automate jobs like email notifications, report generation.

7- Caching	

Supports Redis, Memcached, and file-based caching for performance.

8- Scalability	

Works well with cloud-based solutions and microservices (Laravel Vapor for AWS).

Tools of development that are used in .NET stack

1- Integrated Development Environments (IDEs)

Visual Studio : Full-featured IDE for .NET development.
Visual Studio Code (VS Code) : Lightweight, cross-platform code editor.
JetBrains Rider : Alternative IDE for .NET with great performance.

2- Programming Languages

C# : Main language for .NET applications.
VB.NET : Used in legacy applications.
F# : Functional programming language.

3- Frameworks

.NET (formerly .NET Core) : Modern, cross-platform framework.
.NET Framework : Windows-only, used for older applications.
Mono : Cross-platform runtime, mainly for Unity (game development).

4- Web Development

ASP.NET Core : Web framework for building APIs and applications.
Blazor : For building interactive web UIs with C#.
Razor Pages : Simplified web application model in ASP.NET Core.

5- DevOps Tools

Azure DevOps : CI/CD, version control, and project management.
GitHub Actions : Automation for builds, testing, and deployment.
Docker : Containerization for .NET applications.
Kubernetes : Orchestration for containerized apps.
Azure Functions : Serverless computing with .NET.

