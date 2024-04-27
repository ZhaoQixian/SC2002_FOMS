# SC2002_FOMS - Fastfood Ordering and Management System

## Introduction

FOMS is a Java-based console application designed to streamline the operational efficiency of fast food restaurants. This application supports functionalities for various user roles including Customers, Staff, Managers, and Administrators, facilitating order handling, payment processing, and order tracking. It is a course project done by NTU students for SC2002 Object Oriented Design & Programming.

## Key Features

- **Order Management**: Intuitive system for placing and tracking orders.
- **Payment Integration**: Multiple payment methods supported for user convenience.
- **User Roles**: Distinct capabilities and interfaces for different user roles.
- **Security**: Secure credential storage with SHA-3 hashing for passwords.
- **Automated Order Collection**: Countdown for collection and automated order status updates.

## Getting Started

### Prerequisites

Ensure you have Java Runtime Environment (JRE) installed on your system.

### Installation

Clone the repository using the following command:
```sh
git clone https://github.com/ZhaoQixian/SC2002_FOMS
```

Navigate to the project directory:
```sh
cd FOMS
```

Compile the Java files:
```sh
javac *.java
```

Run the application:
```sh
java Main
```

## Usage

The system provides various functionalities based on user roles:

### Customers

- Add items to cart
- Complete payments using preferred payment methods
- Track and collect orders

### Staff  

- Process and update order statuses
- Complete and update order statuses

### Managers

- Process and update order statuses
- Complete and update order statuses
- Manage menu items and inventory
- Oversee staff within the branch

### Administrators

- Oversee staff across different roles
- Manage and expand branch operations
- Assign staff to managerial roles and manage quotas
- Manage and expand payment methods

## Authors & Acknowledgments
| Team Member | Email |
| ------------- | ------------- |
|Allen Lu Zhao Quan|ALLE0002@e.ntu.edu.sg|
|Guan Xiaoxi|xguan007@e.ntu.edu.sg|
|Kriti Raja|kriti006@e.ntu.edu.sg|
|Yu Fengyuan|fyu002@e.ntu.edu.sg|
|[Zhao Qixian](https://github.com/ZhaoQixian)|qzhao010@e.ntu.edu.sg|


## License

This project is licensed under the MIT License - see the [Copyright](https://github.com/ZhaoQixian/SC2002_FOMS/tree/main/Copyright) folder for details.
