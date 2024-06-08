# E-Kart

## Overview

E-Kart is an online shopping platform designed to offer a seamless and efficient shopping experience. It features a robust product catalog, user authentication, and a shopping cart system. This project is an example of a full-stack web application built using Java, JSP, and MySQL.

## Features

- **User Authentication:** Secure login and registration for users and administrators.
- **Product Catalog:** Display products with details such as name, description, price, and image.
- **Search and Filter:** Search for products by name and filter by categories.
- **Shopping Cart:** Add, update, or remove items from the cart.
- **Admin Dashboard:** Admins can add, update, or remove products from the catalog.

## Technologies Used

- **Backend:** Java, JSP, JDBC, Servlets
- **Frontend:** HTML, CSS, Bootstrap, JavaScript
- **Database:** MySQL

## Installation

### Prerequisites

- Java Development Kit (JDK) 8 or higher
- Apache Tomcat 9.0 or higher
- MySQL Database

### Steps

1. **Clone the repository:**
    ```sh
    git clone https://github.com/RaneRakesh/ekart.git
    cd ekart
    ```

2. **Setup the Database:**
    - Create a database named `shopping-cart`.
    - Import the `shopping-cart.sql` file located in the `sql` folder to create the required tables.

3. **Configure Database Connection:**
    - Update the `DBConnection.java` file with your MySQL database credentials.

4. **Deploy to Tomcat:**
    - Copy the project folder to the `webapps` directory of your Tomcat installation.
    - Start the Tomcat server.

5. **Access the Application:**
    - Open your web browser and navigate to `http://localhost:8080/shopping-cart`.

## Usage

### User Operations

- **Browse Products:** Users can browse through the product catalog.
- **Add to Cart:** Users can add desired products to their shopping cart.
- **Checkout:** Users can proceed to checkout and view their cart details.

### Admin Operations

- **Manage Products:** Admins can add new products, update existing product details, and remove products from the catalog.

## Contact

For any inquiries or issues, please contact dummyuse00007@gmail.com or open an issue on GitHub.

---

Thank you for using E-Kart! We hope you have a great experience shopping with us.
