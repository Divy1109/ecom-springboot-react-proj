Here's the updated README with the correct ports:

---

# E-Commerce Web Application

This is a E-commerce web application built with React for the frontend and Spring Boot for the backend. The application allows users to manage a product inventory with functionalities to add, delete, and search for products.

## Features

- **Product Management:** Add, delete, and search for products.
- **React Frontend:** A dynamic user interface built with React.
- **Spring Boot Backend:** RESTful APIs for handling product operations.
- **In-Memory Database:** Uses Hibernate with an H2 in-memory database for persistence during development.

## Technologies Used

- **Frontend:** React, JavaScript, HTML, CSS
- **Backend:** Spring Boot, Hibernate, RESTful Web Services
- **Database:** H2 (In-Memory)

## Getting Started

### Prerequisites

- Java 21 (or later)
- Node.js (for running the React frontend)
- Maven (for managing Spring Boot dependencies)

### Running the Application

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Divy1109/ecom-springboot-react-proj.git
   cd ecom-springboot-react-proj
   ```

2. **Run the backend:**

   ```bash
   cd ecom-proj
   mvn spring-boot:run
   ```

3. **Run the frontend:**

   ```bash
   cd ../ecom-frontend-5-main
   npm install
   npm start
   ```

4. **Access the application:**

   - Frontend: Open your browser and navigate to `http://localhost:5173`.
   - Backend: The backend will be running on `http://localhost:8080`.

## Future Enhancements

- **Cloud Deployment:** Plan to deploy the application to AWS (EC2 for the backend, S3 for static hosting).
- **Database Integration:** Transition from H2 to AWS RDS for persistent storage.

## Contributing

Feel free to fork this repository and submit pull requests. Contributions are welcome!

## License

This project is licensed under the MIT License.

---

This version reflects the correct port numbers for your application.
