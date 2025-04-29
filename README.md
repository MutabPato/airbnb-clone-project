# airbnb-clone-project

## *Team Roles*
- Business analyst (BA): Understands customer’s business processes. Translates customer business needs into requirements

- Product owner (PO): Holds responsibility for a product vision and evolution. Makes sure the final product meets customer requirements

- Project manager (PM): Makes sure a product or its part is delivered on time and within budget. Manages and motivates the software development team

- UI/UX designer: Transforms a product vision into user-friendly designs. Creates user journeys for the best user experience and highest conversion rates


- Software architect: Designs a high-level software architecture. Selects appropriate tools and platforms to implement the product vision. Sets up code quality standards and performs code reviews


- Software developer: Engineers and stabilizes the product. Solves any technical problems emerging during the development lifecycle


- Quality assurance (QA) engineer: Makes sure an application performs according to requirements. Spots functional and non-functional defects


- Test automation engineer. Designs a test automation ecosystem. Writes and maintains test scripts for automated testing


- DevOps engineer: Facilitates cooperation between development and operations teams. Builds continuous integration and continuous delivery (CI/CD) pipelines for faster delivery

## Technology Stack
- Django: a high-level Python web framework that simplifies and speeds up the development of secure, maintainable web applications. It's designed to handle many common web development tasks, allowing developers to focus on the unique features of their applications rather than reinventing the wheel. 

- MySQL: an open-source relational database management system (RDBMS) that uses Structured Query Language (SQL) to manage and store data. It is a widely used database system for a variety of applications, including web development, e-commerce, and content management systems. 

- GraphQL: a query language and server-side runtime for APIs that provides clients with the specific data they request. It's an alternative to traditional REST APIs, allowing developers to fetch data from multiple sources with a single query. 

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
## API Security
## CI/CD Pipeline

 
