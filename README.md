# CS255
CS255 Portfolio — Cameron Salazar
Date: August 24, 2025
Course: CS255 System Analysis and Design
Repo URL: <paste your GitHub link>

Artifact Overview
- Project One: Business Requirements Document (DriverPass)
- Project Two: System Design Document (DriverPass)

Reflection

Briefly summarize the DriverPass project. Who was the client? What type of system did they want you to design?
DriverPass is a client focused on improving pass rates for driving tests. They asked for a web-based system that supports online practice exams, on-the-road lesson scheduling, progress tracking, and admin oversight. The system serves students, instructors, and administrators and unifies learning and scheduling in one platform.

What did you do particularly well?
I modeled the problem from both process and object perspectives. The process view clarified user workflows and decision points; the object view defined durable entities and behaviors (Student, Instructor, PracticeTest, RoadLesson, Feedback, Payment, Schedule). I also articulated nonfunctional needs early (performance, security, adaptability) and kept requirements clear, testable, and role-based.

If you could choose one part of your work to revise, what would you pick? How would you improve it?
I would expand the traceability and measurement. I would add a full requirements-to-design-to-test matrix, tighter performance budgets per use case, and more specific acceptance criteria for scheduling edge cases like double-booking and cancellation rules.

How did you interpret the user’s needs and implement them into your system design? Why is this important?
I translated interview goals into use cases, user stories, and acceptance criteria, then mapped them to UI flows, components, data entities, and integrations. Considering user needs ensured the design handled real tasks—taking practice tests quickly, booking lessons without conflicts, viewing progress—and enforced quality attributes like security and responsiveness that shape user trust.

How do you approach designing software? What techniques or strategies will you use in the future?
Start with context and stakeholders, then capture scenarios as use cases and activity diagrams, define entities and relationships, and sketch sequence flows for key interactions. I will continue to prototype early, set explicit nonfunctional targets, enforce security-by-design, and maintain traceability from requirements to tests so the design remains verifiable and adaptable.
