# Airbnb clone project overview

The backend for the Airbnb Clone project is designed to provide a robust and scalable foundation for managing user interactions, property listings, bookings, and payments. This backend will support various functionalities required to mimic the core features of Airbnb, ensuring a smooth experience for users and hosts.

## *Team Roles*

- Backend Developer: Responsible for implementing API endpoints, database schemas, and business logic.
- Database Administrator: Manages database design, indexing, and optimizations.
- DevOps Engineer: Handles deployment, monitoring, and scaling of the backend services.
- QA Engineer: Ensures the backend functionalities are thoroughly tested and meet quality standards.


## Technology Stack

- Django: A high-level Python web framework used for building the RESTful API.
- Django REST Framework: Provides tools for creating and managing RESTful APIs.
- PostgreSQL: A powerful relational database used for data storage.
- GraphQL: Allows for flexible and efficient querying of data.
- Celery: For handling asynchronous tasks such as sending notifications or processing payments.
- Redis: Used for caching and session management.
- Docker: Containerization tool for consistent development and deployment environments.
- CI/CD Pipelines: Automated pipelines for testing and deploying code changes.


## Database Design

1. Users: 
    - id
    - name
    - picture
    - bio
    - bookings
    - properties
2. Properties:
    - id
    - title
    - description
    - property type
    - location
    - price
    - bookings
3. Bookings: 
    - id
    - user_id
    - property_id
    - booking period
    - price paid
    - payment method used
4. Reviews:
    - id
    - user_id
    - property_id
    - booking_period
    - review text
    
5. Payments: 
    - id
    - user_id
    - property_id
    - booking_period
    - payment method
    - amount

## Feature Breakdown

1. User Authentication: Register new users, authenticate, and manage user profiles.
2. Property Management: Create, update, retrieve, and delete property listings.
3. Booking System: Make, update, and manage bookings, including check-in and check-out details.
4. Payment Processing: Handle payment transactions related to bookings.
5. Review System: Post and manage reviews for properties.

## API Security

- Authentication: verifies the identity of a user or system accessing an API, ensuring only authorized entities can interact with it. This process is crucial for API security, protecting sensitive data and maintaining the integrity of the service. 

- Authorization: the process of verifying that a user or application has the right permissions to access specific resources or perform certain actions after they have been authenticated. 

- Rate limiting: a security measure that restricts the number of requests a user or client can make to an API within a specific time frame. This technique helps prevent abuse, overloading, and potential security threats like DDoS attacks. By controlling the rate at which API requests are made, developers can ensure fair access to resources, maintain system stability, and optimize resource utilization. 


## CI/CD Pipeline

 A CI/CD pipeline is an automated series of steps that streamline the software development lifecycle, from code creation to deployment.
 CI/CD pipelines are crucial because they automate the software development lifecycle, enabling faster and more frequent releases, improved software quality, and increased collaboration between teams.
 These include : GitHub Actions, Docker
