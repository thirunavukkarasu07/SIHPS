# Smart India Hackathon Workshop
# Date:02/10/2025
## Register Number:212224220117
## Name:Thirunavukkarasu meenakshisundaram
## Problem Title
E-Waste Facility Locator
## Problem Description
Website that tells you the location of the nearest e-waste collection and recycling facility. Offers educational pop-ups on the harmful components of your e-waste and their effects on the environment and human health if not disposed correctly. There could be an option to input the model of your old device and earn credit points relative to the amount of precious metals recovered from the device if disposed correctly.
## Problem Creater's Organization
Ministry of Environment

## Idea
Idea:
Create a web platform that helps users locate the nearest e-waste collection and recycling facilities. The platform will provide educational content on the environmental and health impacts of improper e-waste disposal and offer incentives for proper disposal through a credit points system based on the precious metals recovered from old devices.


## Proposed Solution / Architecture Diagram
1.User Interface (UI): A web application accessible via desktop and mobile devices.
2.Backend: Server to handle requests, process user input, and interact with databases and third-party APIs.
3.Database: Storage for facility locations, user information, device data, and credit points.
4.External APIs: Integration with location services (Google Maps API), educational content sources, and recycling programs.
5.Admin Panel: Interface for managing facility data, educational content, and user rewards.

![fbuil-08-1030196-g007](https://github.com/R01ty/SIHPS/assets/142526219/65cbb46f-0b0a-477e-a98f-06378019a9c4)

## Use Cases
Locate E-Waste Facility:

Description: Users input their location to find the nearest e-waste collection facility.
Actors: User, Admin.
Flow:
User inputs location.
System queries the database and external APIs to find nearby facilities.
System displays the nearest facilities on a map with details.
Educational Pop-ups:

Description: Users receive educational pop-ups about e-waste components and their environmental impact.
Actors: User, System.
Flow:
User navigates the site.
System triggers educational pop-ups based on user interactions.
Pop-ups display content and links to more information.
Credit Points for E-Waste Disposal:

Description: Users input the model of their old device to estimate and earn credit points for proper disposal.
Actors: User, System.
Flow:
User inputs device model.
System calculates potential credit points based on recoverable precious metals.
User disposes of the device at a verified facility.
System verifies disposal and credits points to the user's account.
![Waste-Management-System-Use-Case-Diagram](https://github.com/R01ty/SIHPS/assets/142526219/ce6ceb09-a3b9-4226-8a92-80b501143672)

## Technology Stack
Frontend:

HTML/CSS/JavaScript
Frameworks/Libraries: React or Angular
Google Maps API for facility location
Backend:

Node.js with Express.js
RESTful API development
Database:

MongoDB for facility and user data
Firebase for real-time updates (optional)
Educational Content:

Integration with third-party APIs or Content Management System (CMS) like WordPress
Credit Points System:

Custom logic implemented in the backend
Integration with reward program APIs

## Dependencies
APIs:

Google Maps API for location services
Educational content APIs (e.g., Wikipedia, environmental organizations)
Recycling program APIs for credit points validation
Libraries and Frameworks:

React/Angular for frontend development
Node.js and Express.js for backend development
Mongoose for MongoDB integration
Hosting and Deployment:

Cloud services like AWS, Google Cloud, or Azure
Containerization with Docker (optional)
Authentication:

OAuth for user authentication (e.g., Google, Facebook)
Payment/Reward Systems:

Integration with payment gateways or reward platforms for credit points redemption

