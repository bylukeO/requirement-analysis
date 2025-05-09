# Requirement-analysis
# Requirement Analysis in Software Development.
### Requirement Analysis in Software Development.
    Requirement Analysis is a critical phase in the software development lifecycle (SDLC) where the project team gathers, analyzes, 
    and defines the requirements of the software product to be developed. This process ensures that all stakeholders have a clear 
    and mutual understanding of what the system should do and how it should perform.

# What is Requirement Analysis?
    Requirement Analysis is the process of defining user expectations and needs for a new or modified product. 
    It involves collecting and interpreting information from stakeholders to determine the specific requirements 
    that the software must fulfill. These requirements serve as the bridge between what stakeholders need and what developers will build.

    
## Importance of Requirement analysis in the SDLC.
### Requirement Analysis is crucial for several reasons which include:

    * Foundation for Success: Well-defined requirements provide clear direction for the development team, reducing ambiguity and misinterpretation.
    * Cost Efficiency: Addressing requirement issues early in the development cycle is significantly less expensive than fixing problems after deployment.
    * Scope Management: Clear requirements help control scope creep by establishing boundaries for what will and won't be included in the project.
    * Quality Assurance: Requirements serve as the basis for testing criteria, allowing teams to verify that the software meets stakeholder expectations.
    * Risk Reduction: Thorough analysis helps identify potential risks and challenges early, allowing for mitigation strategies to be developed.

# Why is Requirement Analysis Important?
    * Clarity and Understanding: It helps in understanding what the stakeholders expect from the software, reducing ambiguity.
    * Scope Definition: Clearly defines the scope of the project, which helps in preventing scope creep.
    * Basis for Design and Development: Provides a solid foundation for designing and developing the system.
    * Cost and Time Estimation: Facilitates accurate estimation of project cost, resources, and time.
    * Quality Assurance: Ensures that the final product meets the specified requirements, leading to higher customer satisfaction.

# Key Activities in Requirement Analysis.
    1.  Requirement Gathering 🗂️: This process involves collecting information from stakeholders through interviews, surveys, workshops, observation, and document analysis.
    It can be done through various methods which include;
    Interviews: Conducting interviews with stakeholders to gather detailed information about their needs and expectations.
    Surveys/Questionnaires: Distributing surveys to collect requirements from a larger audience.
    Workshops: Organizing workshops with stakeholders to discuss and gather requirements.
    Observation: Observing end-users in their working environment to understand their needs.
    Document Analysis: Reviewing existing documentation and systems to understand current functionalities and requirements.

    2.  Requirement Elicitation ✍️: Requirement elicitation involves drawing out detailed information from stakeholders, going beyond initial gathering to deeply understand needs, constraints, and expectations.
    It can be done through various methods like;
    Brainstorming: Conducting brainstorming sessions to generate ideas and gather requirements.
    Focus Groups: Holding focus group discussions with selected stakeholders to gather detailed requirements.
    Prototyping: Creating prototypes to help stakeholders visualize the system and refine their requirements.

    3.  Requirement Documentation 📚: Requirement documentation involves recording the gathered and elicited requirements in a clear, structured format that can be understood by all project stakeholders.
    It can be acheived through different ways, which include;
    Requirement Specification Document: Creating a detailed document that lists all functional and non-functional requirements.
    User Stories: Writing user stories to describe functionalities from the user’s perspective.
    Use Cases: Creating use case diagrams to show interactions between users and the system.

    4.  Requirement Analysis and Modeling 📊: Requirement analysis and modeling involves examining gathered requirements to resolve conflicts, identify gaps, and create representations that help stakeholders visualize the system.
    It can be done through various methods, which include;
    Requirement Prioritization: Prioritizing requirements based on their importance and impact on the project.
    Feasibility Analysis: Assessing the feasibility of requirements in terms of technical, financial, and time constraints.
    Modeling: Creating models (e.g., data flow diagrams, entity-relationship diagrams) to visualize and analyze requirements.

    5. Requirement Validation ✅: Requirement validation ensures that the documented requirements accurately represent stakeholder needs and that they are complete, consistent, and feasible to implement.
    It can be done through various methods whihc include;
    Review and Approval: Reviewing the documented requirements with stakeholders to ensure accuracy and completeness.
    Acceptance Criteria: Defining clear acceptance criteria for each requirement to ensure they meet the expected standards.
    Traceability: Establishing traceability matrices to ensure all requirements are addressed during development and testing.

# Types of Requirements.
### Functional Requirements.
### These describe what the system should do — the specific behaviors and functions.
    Examples:
    Hotel Listing Management

        Managers should be able to add, update, and delete hotel listings.

        Example: A manager updates the price of a room in the portal, and it reflects across the system.

    Hotel Search & Discovery

        Users should be able to search for hotels based on filters (location, date, price).

        Example: A user searches for hotels in Lagos between June 1-3 with a max budget of $100/night.

    Booking Functionality

        Customers should be able to select a hotel, choose a room, and book it.

        Example: A user books a deluxe room and receives confirmation via email/SMS.

    Payment Integration

        The system should process payments through integrated third-party services.

        Example: Booking is not confirmed until payment is successfully processed via Paystack or Stripe.

    Booking History Access

        Both customers and hotel managers should be able to view current and past bookings.

        Example: A hotel manager views all upcoming check-ins for the weekend.

    Notification Service

        Users should receive booking confirmations and reminders.

        Example: A customer receives an SMS with booking details after payment is completed.
### Non-functional Requirements.
### These define how the system performs — quality attributes, not specific features.
      Examples:

    Scalability

        The system must handle increased loads (e.g., traffic spikes during holiday seasons).

        Example: Auto-scaling the booking service to handle 10x user traffic during Black Friday promotions.

    Performance

        Hotel search results must be returned in under 2 seconds.

        Example: Elasticsearch is used to speed up complex queries.

    Availability

        The system should have at least 99.9% uptime.

        Example: Using load balancers and replica servers to avoid single points of failure.

    Reliability

        Booking data must not be lost even if a server crashes.

        Example: Kafka ensures messages are not lost and are eventually consumed for persistence.

    Data Consistency

        Once a booking is made, all services must reflect it in near real-time.

        Example: Redis and Cassandra sync data asynchronously but reliably.

    Security

        Payment information and user data must be encrypted and stored securely.

        Example: All API endpoints are protected with authentication and SSL.

    Maintainability

        The system should support independent updates to services.

        Example: Microservices architecture allows the booking module to be updated without affecting search.

    Fault Tolerance

        The system must recover gracefully from partial failures.

        Example: If the payment service fails, the system retries or alerts the user without crashing.

# Use Case Diagrams.
      What are Use Case Diagrams?
        Use case diagrams show how different users (actors) interact with the system to achieve specific goals (use cases).

    Creating Use Case Diagrams:
        Identify actors (e.g., guest, registered user, admin).
        Define use cases (e.g., search properties, book property, manage listings).
        Draw interactions between actors and use cases.

    Benefits of Use Case Diagrams:
        Provide a clear visual representation of system functionalities.
        Help in identifying and organizing system requirements.
        Facilitate communication among stakeholders and development team.
