# Here the live link of the deployed project (ie) created by our Team

[ url: https://dillikumarnl.github.io/Grocery_Stores/](https://dillikumarnl.github.io/Grocery_Stores/)

The mentioned above url navigates to the website which we are created

# Project_Title-Application for Grocery Delivery 
SOFTWARE 
REQUIREMENTS SPECIFICATION
 
For 
 
Grocery Delivery Application
 
Prepared by:- 
CHANDRASEKARAN S,
DILLIKUMAR N,
HARIHARAN R,
TAMIL SELVAN T 

Academic Year: 2023-2024

## 1. Introduction 
## 1.1 Purpose  
This SRS document outlines the requirements for our project Grocery Delivery Application, aiming to simplify and enhance the grocery shopping experience. It encompasses both functional and non-functional prerequisites defined by our client. Our primary objective is to provide an accessible platform that enables users to effortlessly browse, create lists, and order groceries from their homes or workplaces, promoting convenience and time-saving. Additionally, our system empowers vendors to manage inventory and fulfill orders, fostering industry-wide efficiency efficiently. Visualized through ER and UML diagrams, this document elucidates hardware and software interface requirements, guiding our development process. Join us on this journey to redefine grocery delivery, promoting accessibility and satisfaction for all. Your participation is vital in this transformative project.

 
## 1.2 Scope of Development Project 
Develop a website with a paramount focus on security, integrating robust user authentication, authorization, and data encryption for a grocery delivery application. Ensure an intuitive user experience with responsive design, efficient data handling, and user-friendly interfaces. Implement secure session management, rigorous input validation, and comprehensive error-handling mechanisms. 
Employ HTTPS for secure data transmission and conduct regular security assessments to address vulnerabilities proactively. Construct a scalable architecture to accommodate future growth while adhering to applicable compliance standards. Deliver extensive documentation and user training to facilitate smooth website management and operation within the context of the grocery delivery application.
The project can be readily deployed in diverse scenarios, providing the flexibility to incorporate new features as needed. This adaptability ensures module reusability and scalability. Java was chosen as the development language due to its numerous advantages, including exceptional performance, a rich array of available tools, cross-platform compatibility, access to extensive libraries, cost-effectiveness (open-source), and a streamlined development process.

## 1.3 Description

This is a web application that aims to simplify and enhance the grocery shopping experience. It allows users to effortlessly browse, create lists, and order groceries from their homes or workplaces, promoting convenience and time-saving. Additionally, it empowers vendors to manage inventory and fulfill orders, fostering industry-wide efficiency. It also provides real-time order tracking, secure payment processing, and customer support and feedback features.

This project was developed using React.js and Bootstrap as the front-end technologies, and Spring Boot and MongoDB as the back-end technologies. React.js is a popular JavaScript library for building user interfaces, and Bootstrap is a framework for creating responsive and mobile-friendly web pages. Spring Boot is a framework for creating stand-alone, production-grade Spring-based applications, and MongoDB is a cross-platform document-oriented database. These technologies provide a fast, scalable, and secure web application that can handle complex data and logic.

## 1.4 Features

- User Registration & Authentication: Enable secure account creation and login for users.
- Product Catalog: Provide a comprehensive catalog for browsing and selecting grocery items.
- Order Management: Allow users to place and manage orders, including order validation.
- Real-Time Order Tracking: Implement tracking for customers and drivers with live updates.
- Vendor Tools: Offer vendors tools for managing products, pricing, and order processing.
- Payment Processing: Integrate secure payment gateways for diverse payment methods.
- Customer Support & Feedback: Facilitate user inquiries, issue resolution, and feedback submission for continuous improvement.


## 1.5 Usage

To use this application, you need to register as a user and log in with your credentials. You can choose to register as a customer, a delivery driver, a vendor, or an administrator. Depending on your role, you will have access to different features and interfaces.

- As a customer, you can browse the product catalog, create lists, place orders, track orders, make payments, and provide feedback.
- As a delivery driver, you can view the available orders, accept orders, update the order status, and receive payments.
- As a vendor, you can manage your products, prices, and inventory, process orders, and view reports.
- As an administrator, you can oversee the entire system, manage users, and handle issues.


## 1.6 Product Perspective
A web-based platform that connects customers, vendors, and delivery agents for online grocery shopping.
Convenient and efficient way to order groceries from a variety of stores and have them delivered to the doorstep.
System that enables vendors to manage inventory and orders, and delivery agents to complete deliveries.
Service that offers personalized recommendations, discounts, rewards, and quality standards.

## 2. Fuctionalites
## 2.1 Product Function 
User Registration & Authentication: Enable secure account creation and login for users.
Product Catalog, Provide a comprehensive catalog for browsing and selecting grocery items.\
Order Management: Allow users to place and manage orders, including order validation.
Real-Time Order Tracking: Implement tracking for customers and drivers with live updates.
Vendor Tools: Offer vendors tools for managing products, pricing, and order processing.
Payment Processing: Integrate secure payment gateways for diverse payment methods.
Customer Support & Feedback: Facilitate user inquiries, issue resolution, and feedback submission for continuous improvement.
 	 
## 2.2 User Classes and Characteristics 
 For grocery delivery applications, there are different entities that have different characteristics, roles, and responsibilities to consider for a good environment setup.

Customers:
Characteristics:
•	Individuals or households.
•	Place grocery orders.
•	Preferences for specific products or vendors.
•	Demand order tracking and notifications.
Roles:
•	Browse, select, and order groceries.
•	Monitor order status and receive updates.
•	Provide feedback and ratings.

Delivery Drivers:
Characteristics:
•	Contracted drivers or couriers.
•	Responsible for order deliveries.
•	Need real-time navigation and order information.
Roles:
•	Accept and fulfill delivery orders.
•	Utilize GPS for route optimization.
•	Confirm deliveries with digital records.

Vendors:
Characteristics:
•	Grocery stores or suppliers.
•	Offer product listings and inventory.
•	Manage order processing and fulfillment.
Roles:
•	List and update products and pricing.
•	Process incoming customer orders.
•	Maintain inventory status.

Administrators:
Characteristics:
•	System administrators.
•	Manage the application, users, and vendors.
•	Oversee system performance and security.
Roles:
•	Manage user accounts and roles.
•	Monitor and resolve system issues.
•	Administer promotional campaigns.

## 2.3 Assumptions and Dependencies 
The assumptions are:- 
	The coding should be error-free 
	The system should be user-friendly so that it is easy to use for the users 
	The information of all users, books, and libraries must be stored in a database that is accessible by the website 
	The system should have more storage capacity and provide fast access to the database 
	The system should provide a search facility and support quick transactions 
	The Library System is running 24 hours a day 
	Users may access  from any computer that has Internet browsing capabilities and an Internet connection 
	Users must have their correct usernames and passwords to enter into their online accounts and do actions 
 
The dependencies are:- 
	The specific hardware and software due to which the product will be run 
 On the basis of listing requirements and specifications, the project will be developed and run 
	The end users (admin) should have a proper understanding of the product 
	The system should have the general report stored 
	The information of all the users must be stored in a database that is accessible by the Library System 
	Any update regarding the book from the library is to be recorded to the database and the data entered should be correct. 
 
## 2.4 Requirement 
System & Software Configuration:- 
Operating System: Windows NT, Windows 98, Windows XP, and above versions., 
Language & IDE:Html, JavaScript(react.js-library), CSS(bootstrap) (front end), java (Spring boot)(back-end)
Database: MongoDB. 
 
## 2.5 Data Requirement 
 The inputs consist of the query to the database and the output consists of the solutions for the query. The output also includes the user receiving the details of their accounts. In this project, the inputs will be the queries as fired by the users like creating an account, selecting books, and putting into an account. Now the output will be visible when the user requests the server to get details of their account in the form of time, date, and which books are currently in the account.  
 
## 3. External Interface Requirement 
## 3.1 GUI 
Our GUI design focuses on efficient navigation and information hierarchy, making it easy for users to browse products, manage their shopping carts, and track orders. We employ visually engaging elements, including high-quality images, icons, and a cohesive color scheme, to enhance the overall aesthetic and brand identity of the application. The checkout process is streamlined with secure payment options, and users can expect real-time order tracking and personalized experiences through user profiles. Accessibility and error handling are key considerations, ensuring that the application is usable by individuals with disabilities and that users receive clear guidance in case of issues. Overall, our GUI design aims to deliver a seamless and enjoyable grocery shopping experience while accommodating future growth and scalability.

## 4. Non-functional Requirements 
## 4.1 Performance Requirement 
Response Time: The application responds quickly to user actions, with pages loading within a specified time frame.
Scalability: The application handles an increasing number of users and orders without significant performance degradation.

## 4.2 Reliability
Availability: Aim for high availability, minimizing downtime for maintenance or unexpected issues.
Error Handling: Provide informative error messages and gracefully handle errors to prevent service interruptions.

## 4.3 Security
Data Encryption: Use encryption to protect sensitive data such as user information and payment details.
Authentication and Authorization: Implement strong authentication and authorization mechanisms to ensure that only authorized users can access specific features.
Secure APIs: Ensure that APIs used for payment processing and other sensitive operations are secure and protected from attacks. 

## 4.4 Data Management
Data Backup and Recovery: Regularly back up user data and provide a robust data recovery mechanism in case of data loss.
Data Privacy: Comply with data privacy regulations and protect user data from unauthorized access. 
## 4.5 Scalability and Load Handling
Load Testing: Perform load testing to ensure the application can handle a high volume of concurrent users and orders.
Horizontal Scaling: Be able to scale horizontally by adding more servers or resources during peak usage.

## 4.6 Usability
 User Interface Design: Create an intuitive and user-friendly interface that is easy to navigate.
	Accessibility: Ensure the application is accessible to users with disabilities, complying with accessibility standards.
	Cross-Browser Compatibility: Ensure the application works seamlessly on major web browsers.
	Mobile Responsiveness: Optimize the user experience for mobile devices through responsive design.
	Logging: Implement robust logging to capture system events, errors, and user activities for troubleshooting and auditing.
	Monitoring: Set up monitoring tools to track system health, performance, and security.
	Regulatory Compliance: Adhere to relevant legal and regulatory requirements, including food safety standards and e-commerce regulations.


## 4.7 Glossary 
The following is the list of conventions and acronyms used in this document and the project as well: 
Administrator: A login ID representing a user with user administration privileges to the software  
User: A general login ID assigned to most users 
Client: Intended users for the software  
SQL: Structured Query Language used to retrieve information from a   database 
NoSQL: non-relational database to store and retrieve data.
SQL Server: A server used to store data in an organized format 
Layer: Represents a section of the project 
User Interface Layer: The section of the assignment referring to what the user interacts with directly 
Application Logic Layer: The section of the assignment refers to the Web Server. 
Data Storage Layer: The section of the assignment referring to where all data is recorded  Use Case: A broad-level diagram of the 	project showing a basic overview 
Class diagram: It is a type of static structure diagram that describes the structure of a system by showing the system’s cases, their attributes, and the relationships between the classes 
Interface: Something used to communicate across different mediums 
Unique Key: Used to differentiate entries in a database 

