# TicketWave - Cinema E-Booking System

TicketWave is a modern web-based application designed to streamline the movie ticket booking experience for both administrators and users. With a focus on usability, security, and real-time updates, TicketWave allows users to browse a wide range of movies, book tickets seamlessly, and manage their profiles efficiently.

This project was developed as part of the Software Engineering course (CSCI 6050) during my master's program at the University of Georgia. The objective was to implement software engineering principles in a real-world application by designing, developing, and deploying a robust and user-friendly cinema e-booking system. The development process followed a hybrid model, integrating both waterfall and agile methodologies, ensuring high-quality outcomes through iterative improvements and user feedback.

## Key Features

### 1. **Movie Information Management**
- Administrators can easily manage movie details such as titles, categories, cast, director, synopsis, trailers (images and videos), reviews, and showtimes.
- The system supports adding, updating, and deleting movie information, ensuring an up-to-date catalog for users.

### 2. **Ticket and Promotion Management**
- Administrators have full control over ticket pricing, booking fees, and special promotions.
- Email notifications for promotions are automatically sent to subscribed users, driving user engagement.

### 3. **User Registration and Profile Management**
- Secure registration process with email verification and unique account IDs.
- Registered users can manage personal profiles, update payment details, and subscribe to promotional emails.

### 4. **Booking Facility**
- A streamlined, intuitive interface for selecting movies, dates/times, and seat categories.
- Seat selection is made simple with a graphical hall view for optimal user experience.
- Only registered users can book tickets, ensuring secure transactions.

### 5. **Secure Checkout**
- Secure, encrypted payment system that supports promo codes for discounts.
- Users receive email confirmations for every successful booking.

### 6. **Order History and Ticket Refund**
- Users can view their complete booking history and request refunds for tickets, provided cancellations are made at least 60 minutes before the showtime.

### 7. **Administrative Tools**
- Administrators have access to predefined reports, system parameters, and multi-user access controls.
- The platform includes role-based authentication and authorization mechanisms for secure system management.

## Development Process
TicketWave was developed using a **multi-layered architecture** to ensure modularity, scalability, and maintainability. A hybrid incremental development model was followed, combining agile sprints with the structure of the waterfall model. User feedback loops and continuous testing ensured a polished, production-ready system.

### Architecture Style
- **Front-End**: Angular
- **Back-End**: Java Spring Boot
- **Database**: MySQL

## Technology Stack
- **Front-End**: Angular
- **Back-End**: Java SpringBoot
- **Database**: MySQL
- **Languages**: TypeScript, Java, SQL
- **Tools & Frameworks**: Visual Studio Code, Spring Tool Suite (STS), Node.js, Angular CLI

## Installation Guide

### Prerequisites
- **Java JDK**: Download the latest version of the [Java JDK](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html).
- **Spring Boot IDE**: Install [Spring Tool Suite (STS)](https://spring.io/tools) or [Eclipse](https://www.eclipse.org/).
- **Visual Studio Code**: Download and install [VS Code](https://code.visualstudio.com/).
- **Node.js**: Install Node.js from [Node.js Official Website](https://nodejs.org/).
- **MySQL**: Download and install [MySQL](https://dev.mysql.com/downloads/installer/).

### Step 1: Clone the Repository
```bash
git clone https://github.com/your-username/TicketWave.git

### Step 2: Backend Setup
1. Open the backend project in Spring Tool Suite (STS) or Eclipse.
2. Configure the database connection in the `application.properties` file:
    ```properties
    spring.datasource.url=jdbc:mysql://localhost:3306/ticketwave
    spring.datasource.username=root
    spring.datasource.password=yourpassword
    ```
3. Run the Spring Boot application.

## Step 3: Frontend Setup
1. Navigate to the frontend directory:
    ```bash
    cd frontend
    ```
2. Install dependencies:
    ```bash
    npm install
    ```
3. Update the API base URL in the `environment.ts` file:
    ```typescript
    export const environment = {
      production: false,
      apiUrl: 'http://localhost:8080/api'
    };
    ```
4. Run the Angular application:
    ```bash
    ng serve
    ```

## Step 4: Access the Application
- Open your browser and navigate to `http://localhost:4200` to access the TicketWave interface.
- You can change the port number if needed by modifying the configuration.

## Future Enhancements
- **Mobile App Integration**: Develop native mobile apps for iOS and Android for increased accessibility.
- **Social Media Integration**: Allow users to log in using their social media accounts.
- **Advanced Analytics**: Provide more in-depth analytics for administrators regarding user behavior and movie popularity.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For any questions or contributions, feel free to reach out:

- **Email**: kushalmareedu@gmail.com
- **LinkedIn**: [Kushal-Maridu](https://linkedin.com/in/Kushal-Maridu)

