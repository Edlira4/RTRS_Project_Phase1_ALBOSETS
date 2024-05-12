# RTRS_Project_Phase1_ALBOSETS
Group Division (Phase I) 
# Team Information
## Team Name: [ALBOSETS]

## Team Leader:
- **Name:** [Edlira Daku]
- **GitHub Username:** [Edlira4]

## Team Members:
No other members, group made of 1 person.

# Project Details

## Project Title: [Albanian Railway Ticket Reservation System]

## Problem Statement:
[The lack of an efficient railway ticket reservation system in Albania hinders the convenience and accessibility of railway transportation for passengers]

## Solution Proposed:
[We propose to develop a comprehensive railway ticket reservation system that will streamline the booking process and enhance the overall efficiency of railway services in Albania..]

## Project Scope:
- **Aim:** [SThe aim of our project is to provide a user-friendly and efficient railway ticket reservation system for passengers in Albania.
- **Main Objectives:**
1. [Implement a secure and user-friendly interface for ticket booking.]
2. [Integrate real-time train schedule information]
3. [Offer secure payment options for ticket purchases]
4. [Provide customer support features for passenger assistance]
   

## Application Description:
[The Albanian Railway Ticket Reservation System will be a web-based application that allows passengers to book tickets, check train schedules, select seats, and make secure payments online. The system will also provide real-time updates on train statuses and offer customer support for inquiries and assistance..]

# Roles and Tasks Distribution

## Team Leader:

[Project management, coordination, and overseeing the development process]

## Main Roles and Tasks:
1. [Edlira Daku] - [Responsible for overall project management and full-stack development tasks.]


# Deadline
Submission Deadline: 04.03.2023, 23:59 hours.

# Additional Notes
[Please note that additional information and updates may be added to the provided project details as the development process progresses. Kindly stay tuned for further updates and enhancements to the project scope and implementation details]

**Phase II: User Requirements and Application Specifications**

**1. Chosen Development Model:**
- **Agile**
  - **Justification:** Agile methodology has been selected for its iterative approach, allowing for continuous refinement of the system based on user feedback. Given the dynamic nature of the project and potential changes in requirements, Agile offers adaptability and promotes collaboration, essential for successful development.

**2. User Requirements:**

**a. Stakeholders:**
- **End-users (Passengers):** Students, commuters, and travelers who rely on the railway system for transportation.
- **Clients (Railway Authorities):** Representatives from Albanian railway authorities overseeing the development and implementation of the ticket reservation system.
- **Developers (Team Leader - Edlira Daku):** Responsible for system design, development, and maintenance.

**b. User Stories:**
1. **User Type:** Passenger (Student)
   - **Requirement:** As a student, I want to easily search for train options based on my university location and preferred travel times to plan cost-effective trips.
   - **Benefit:** Facilitates budget-conscious travel planning for students by providing tailored search options based on their educational institution's location.

2. **User Type:** Passenger (General)
   - **Requirement:** As a commuter, I need real-time updates on train schedules and seat availability to efficiently plan my daily travels.
   - **Benefit:** Enhances commuter experience by offering timely information, reducing wait times, and optimizing travel routes.

**3. Functional Requirements:**

**a. Brief Description:**
- **User Registration and Authentication:** Allow passengers to register and log in securely to access booking features.
- **Train Search and Schedule Viewing:** Provide a user-friendly interface for searching trains, viewing schedules, and checking seat availability.
- **Booking and Payment:** Enable passengers to select seats, proceed with secure online payment, and receive booking confirmations.
- **Real-time Updates:** Display live updates on train statuses, delays, and cancellations to keep passengers informed.
- **Customer Support Features:** Offer FAQs, contact forms, and live chat support for passenger assistance and inquiries.

**b. Acceptance Criteria:**
1. **User Registration and Authentication:**
   - ✓ Students can register using their university email addresses for authentication.
   - ✓ Two-factor authentication ensures secure login for registered users.

2. **Train Search and Schedule Viewing:**
   - ✓ Advanced search options allow filtering by university locations for student convenience.
   - ✓ Real-time schedule updates ensure accuracy and reliability.

3. **Booking and Payment:**
   - ✓ Secure payment gateways accept various payment methods, including student discounts where applicable.
   - ✓ Booking confirmation emails are sent promptly upon successful payment.

4. **Real-time Updates:**
   - ✓ Automated notifications alert passengers of any schedule changes or disruptions.
   - ✓ Live updates on seat availability help passengers make informed decisions.

5. **Customer Support Features:**
   - ✓ Comprehensive FAQs address common inquiries regarding bookings, refunds, and policies.
   - ✓ Responsive customer support via email, live chat, or phone ensures timely assistance for passengers.

**4. Non-Functional Requirements:**

**a. Brief Description:**
- **Performance:** Ensure fast response times and scalability to accommodate peak usage periods, such as holidays or exam seasons.
- **Usability:** Design an intuitive user interface accessible across devices, considering varying levels of technical proficiency among users.
- **Security:** Implement robust data encryption, secure authentication protocols, and regular security audits to safeguard passenger information.

**b. Acceptance Criteria:**
1. **Performance:**
   - The system should maintain response times under 3 seconds, even during peak usage.
   - Scalability tests demonstrate the system's ability to handle a 20% increase in concurrent users without degradation.

2. **Usability:**
   - User interface designs undergo usability testing with student focus groups to ensure accessibility and ease of navigation.
   - Mobile-responsive layouts accommodate users accessing the system from smartphones or tablets.

3. **Security:**
   - All user passwords are hashed using bcrypt with salt for added security.
   - Regular security audits and penetration testing are conducted to identify and address potential vulnerabilities proactively.

**5. Application Specifications:**

**a. Architecture:**
- The system architecture follows a microservices approach, utilizing containerization for scalability and flexibility.
- Components include frontend clients, microservices for user management, booking, payment processing, and a centralized database.

**b. Database Model:**
- A relational database model is adopted, featuring tables for users, trains, bookings, payments, and customer support interactions.
- Foreign key constraints maintain data integrity, while indexing improves query performance.

**c. Technologies Used:**
- **Frontend:** HTML5, CSS3, JavaScript (React.js)
- **Backend:** Node.js, Express.js
- **Database:** PostgreSQL
- **Other Tools:** Docker for containerization, Kubernetes for orchestration, JSON Web Tokens (JWT) for authentication.

**d. User Interface Design:**
- User interface designs incorporate Material Design principles for a modern and intuitive user experience.
- Wireframes and prototypes are iteratively developed based on user feedback and usability testing results.

**e. Security Measures:**
- Data encryption using HTTPS ensures secure communication between clients and servers.
- Multi-factor authentication (MFA) options, including biometric authentication, are available for enhanced user security.
- Regular security audits and compliance with industry standards (e.g., OWASP) ensure data protection and privacy compliance.

  # Deadline
Submission Deadline: 18.03.2023, 23:59 hours.

# Additional Notes
[Please note that additional information and updates may be added to the provided project details as the development process progresses. Kindly stay tuned for further updates and enhancements to the project scope and implementation details]

# Phase III: Software Design and Modeling

# Group Name: ALBOSETS

Software Architecture
System Architecture:
The Albanian Railway Ticket Reservation System follows a microservices architecture, allowing for modularity, scalability, and flexibility. It comprises several interconnected components, including frontend clients, microservices for user management, booking, payment processing, and a centralized database. Each microservice is containerized using Docker for efficient deployment and management. Kubernetes orchestrates these containers, ensuring fault tolerance and high availability.

Component Diagram:
[Diagram illustrating the different components of the system and their interactions.]

Detailed Design
Class Diagram:
[Class diagram showcasing the relationships and attributes of various classes within the application, such as User, Train, Booking, Payment, etc.]

Sequence Diagrams:
[Sequence diagrams illustrating the step-by-step interactions between different components to accomplish tasks like user registration, train booking, payment processing, etc.]

Database Design:
The relational database model utilizes PostgreSQL to organize the application's data efficiently. Tables include User, Train, Booking, Payment, and Customer Support Interactions, with appropriate foreign key constraints to maintain data integrity. Indexing is implemented to improve query performance, ensuring optimal database operations.

Modeling
Use Case Diagram:
[Use case diagram depicting the different interactions and functionalities available to end-users, clients, and developers within the system.]

Activity Diagrams:
[Activity diagrams outlining the flow of activities for various tasks, such as searching for trains, booking tickets, making payments, etc.]

State Diagrams:
[State diagrams illustrating the different states that objects within the system can transition between, such as the states of a booking process or user authentication.]

Additional Notes
- All diagrams are properly labeled and formatted for clarity and easy understanding.
- Detailed explanations and annotations accompany each diagram to provide further insight into the system's design and functionality.
- The submission deadline for Phase III is April 1st, 2024, 23:59 hours.
## 1. Introduction to Testing:

Software testing is the process of evaluating software to identify defects or bugs. It involves executing software components or systems to compare actual results with expected results and ensure that they meet specified requirements. Testing is crucial in software development for ensuring reliability and correctness, as it helps to detect and fix defects early in the development lifecycle, reducing the cost and effort of fixing them later.

## 2. Purpose of Testing:

Testing aims to identify defects early in the development process and verify that software components perform as intended. It helps in validating that the software meets the specified requirements, ensuring its reliability, functionality, and performance. By testing software comprehensively, developers can deliver high-quality products that meet user expectations and contribute to customer satisfaction.

## 3. Focus on Testing a Single Component:

For this assignment, we will focus on testing the `BookingService` module of the Albanian Railway Ticket Reservation System. This component is critical as it handles the core functionality of booking tickets, managing seat availability, and processing payments. Testing this module is important to ensure that it functions correctly, handles various scenarios effectively, and contributes to the overall reliability of the system.

## 4. Preparing Test Cases:

To prepare comprehensive test cases for the `BookingService` module, we need to cover various scenarios, including:
- Normal inputs: Valid booking requests under standard conditions.
- Edge cases: Unusual scenarios such as booking when seats are almost full.
- Invalid inputs: Testing the system's response to invalid inputs, such as incomplete booking details or negative fares.

## 5. Choosing Testing Frameworks:

For testing the `BookingService` module in the Node.js environment, we recommend using Jest, a popular testing framework for JavaScript. Jest offers a simple yet powerful testing experience, including support for assertions, mocking, and code coverage analysis. To set up the testing environment with Jest, you can install it using npm:

```
npm install --save-dev jest
```

Then, you can configure Jest by adding a `jest.config.js` file to your project directory with the necessary configuration options.

## 6. Writing Test Code:

To write test code for the `BookingService` module, we'll create test methods to exercise different functionalities. We'll use Jest's test function to define individual test cases, providing examples of assertions to validate expected outcomes. Here's an example of how to write test code for booking a ticket successfully:

```javascript
test('should book a ticket successfully', () => {
  // Mocking data
  const bookingDetails = {
    userId: 'user123',
    trainId: 'train456',
    seatNumber: 'A12',
    departureTime: '2024-05-15T08:00:00',
    fare: 25.0
  };

  // Perform booking
  const bookingResult = bookingService.bookTicket(bookingDetails);

  // Assert booking success
  expect(bookingResult.success).toBe(true);
  expect(bookingResult.message).toBe('Ticket booked successfully.');
});
```

## 7. Running Tests:

To execute tests written with Jest, you can run the following command in your terminal:

```
npx jest
```

This command will execute all test files in your project and provide outputs indicating which tests passed, which failed, and any errors encountered during execution. You can interpret the results to ensure that the `BookingService` module behaves as expected under different scenarios.

## 8. Test Coverage:

Achieving high test coverage is essential to ensure thorough testing of the software. Test coverage measures the percentage of code that is executed by the test suite. By aiming for high test coverage, developers can identify areas of the codebase that may require additional testing and ensure that all critical functionalities are adequately tested.

---

By following these steps, you can effectively test the `BookingService` module of the Albanian Railway Ticket Reservation System and ensure its reliability and correctness.
06/05/2024
