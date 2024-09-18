# Hotel Management Application

## Project Overview

This project focuses on developing a hotel management system (Quản Lý Khách Sạn) that facilitates online and in-person booking, room rental management, payment processing, and administrative functionalities. The system is designed using Python Flask for the backend, utilizing Object-Oriented Programming (OOP) principles, and MySQL for the database.

## Features

1. **Booking Management**
   - Customers can book rooms online or in-person.
   - The system supports room search based on multiple criteria.
   - Booking is allowed up to 28 days in advance.

2. **Room Rental Management**
   - Staff can create rental slips for customers upon arrival.
   - For existing reservations, staff can retrieve booking information using the customer's name.
   - Supports two types of customers: domestic and foreign, with a maximum of 3 guests per room.

3. **Payment Processing**
   - Staff can process payments for room rentals.
   - Room rates are based on a maximum of 2 guests, with an additional 25% charge for a third guest.
   - For foreign guests, rates are multiplied by 1.5.

4. **Admin Management**
   - Administrators can modify room types, pricing, and guest regulations.
   - Management of room lists (add/remove/edit/search rooms).

5. **API Integration**
   - The system includes APIs for seamless data interaction and integration with external services.
  
## Project Requirements

- **Use Case Diagram and Specifications**: Develop use case diagrams for the four most critical business processes.
![image](https://github.com/user-attachments/assets/8bf1d56e-3903-4035-b72a-dba2b3cb5513)

- **Class Diagram**: Design class diagrams that will be translated into a relational database schema, adhering to OOP principles.
![image](https://github.com/user-attachments/assets/53d52254-9095-4ce1-8277-1561a76f9c58)

## Technology Stack

- **Backend**: Python Flask
- **Database**: MySQL
- **Version Control**: GitHub for collaborative development and version management.

## Installation Instructions

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd hotel-management-system
   ```

3. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Set up your MySQL database and configure the connection settings in the application.

5. Run the application:
   ```bash
   python app.py
   ```

## Usage

- Access the application through your web browser at `http://localhost:<port-id>`.
- Follow the on-screen instructions for booking, managing rentals, and processing payments.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

This is a team's project, and big shout out for [huynhduydong]((https://github.com/huynhduydong)) for being a MVP of our project, originally archived in his GitHub: https://github.com/huynhduydong/hotell (as we had some unresolved conflicts during merging our code, so we had to push it seperatedly)

---

Feel free to modify any sections as needed to better fit your project!
