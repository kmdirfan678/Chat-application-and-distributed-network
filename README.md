PROJECT TITLE : SIMPLE DISTRIBUTED CHAT APPLICATION

TEAM MEMBERS  : GOWSIK P , 
                PRAVIN K , 
                MOHAMED IRFAN SHEIK K. 


DESCRIPTION  : 


Step 1: Requirement Analysis

•	Objective: Finalize functional, non-functional, and performance requirements.

•	Tasks:

o	Understand user expectations, such as instant messaging, video/audio calling.

o	Validate requirements like message ordering, guaranteed delivery, and scalability.

 

Step 2: Architecture Design

•	Objective: Design a robust architecture based on the three-tier model: Presentation, Business, and Persistence layers.

•	Tasks:

o	Define interactions between layers.

o	Decide client-server communication using WebSocket and WebRTC for real-time communication.

o	Use a cache layer for quick access to chat history.

 

Step 3: Technology Selection

•	Objective: Choose technologies and tools based on performance and scalability needs.

•	Tasks:

o	Backend: Java 8, Apache Tomcat, MySQL, Redis.

o	Frontend: Angular (TypeScript-based).

o	Real-time protocols: WebSocket, WebRTC.

o	Cloud hosting: AWS for scalability.

 

Step 4: Database Design

•	Objective: Define schemas for user management, message tracking, and friend lists.

•	Tasks:

o	Create relational tables in MySQL for users, conversations, and friendships.

o	Implement Redis for caching frequently accessed data.

 

Step 5: Server-Side Development

•	Objective: Develop the backend for account management, messaging, and real-time communication.

•	Tasks:

o	Implement REST API for user authentication and authorization.

o	Configure WebSocket for text messaging.

o	Use WebRTC for peer-to-peer video/audio communication.

o	Develop services for message storage and retrieval using MySQL and Redis.

 

Step 6: Client-Side Development

•	Objective: Build a user-friendly interface using Angular.

•	Tasks:

o	Implement UI for login, chat panels (conversations, friends, chat messages).

o	Create components for group and one-on-one communication.

o	Connect with WebSocket for real-time messaging.

 

Step 7: Integration of Protocols

•	Objective: Seamlessly integrate WebSocket and WebRTC into the system.

•	Tasks:

o	Establish WebSocket connections for instant messaging.

o	Configure WebRTC for video and audio calls.

o	Test fallback mechanisms (e.g., HTTP Long-Polling) for low-bandwidth scenarios.

 

Step 8: Testing and Debugging

•	Objective: Ensure the application works seamlessly and meets performance benchmarks.

•	Tasks:

o	Conduct unit tests for components and services.

o	Perform integration tests for end-to-end data flow.

o	Measure performance under various loads (e.g., 10,000 users online).

 

Step 9: Deployment and Cloud Configuration

•	Objective: Deploy the application to a scalable and cost-efficient cloud environment.

•	Tasks:

o	Host the backend on AWS (e.g., EC2, S3, RDS for MySQL).

o	Use a content delivery network (CDN) for frontend hosting.

o	Configure autoscaling for handling high traffic.

 

Step 10: Documentation

•	Objective: Prepare comprehensive documentation for system understanding and future development.

•	Tasks:

o	Detail API endpoints, database schema, and application flow.

o	Provide instructions for deployment and scaling.

 

Step 11: Feedback and Refinement

•	Objective: Improve the application based on user feedback and initial deployment results.

•	Tasks:

o	Collect feedback from beta users.

o	Address bugs, performance issues, and usability concerns.

 

Step 12: Launch and Maintenance

•	Objective: Launch the application and ensure its ongoing reliability.

•	Tasks:

o	Roll out the application to all users.

o	Monitor application performance using logging and analytics tools.

o	Implement regular updates for security, features, and scalability.


