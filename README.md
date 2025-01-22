#Electronic Store Management System

##General description of the system

This is an application to manage the financial life of an electronic store. It allows a store owner to maintain their business in an automated manner by generating live financial reviews of the business, providing a detailed overview of the employees, and allowing easy modifications of the available stock. It has three levels of users: Administrator, Manager, and Cashier, each of which has different permissions and features.

The Administrator user is at the top of the hierarchy of users. This role has the permission to create other users and manage their levels of access. The administrator can manage overall income and expenses on the finances tab, and manipulate the store's stock by adding, removing, or editing items. Additionally, the administrator can manage employee data and view detailed statistics about income, expenses, and the performance of the employees.

The Manager is responsible for managing stock levels, restocking items, and receiving notifications when stocks are low. Managers can also analyze the performance of cashiers and track sales statistics for a particular period.

The Cashier handles day-to-day sales and customer transactions. They can create bills, update stock levels automatically after a sale, and generate printed receipts. Cashiers have limited access to other areas of the system and are restricted to interacting with stock for their assigned sector.

For all users, the system includes a profile section where they can modify their personal information, such as name, username, password, and more. There is also a messaging feature that allows users to exchange messages with each other. Users can access statistics and reports based on the time frame they select.

##Information regarding the implementation

The system is implemented in Java using JavaFX as the frontend framework. The information is stored in text and binary files, following the design patterns of inheritance and factory classes. The main components of the system include:

Model-View-Controller Architecture (MVC): Ensures separation of concerns and modular development.

Object-Oriented Design: Utilizes encapsulation, inheritance, polymorphism, abstract classes, interfaces, and generics.

File Handling: Combines text and binary file handling for secure data storage and easy manipulation.

Validation and Exception Handling: Implements string validation, regular expressions, and structured error handling with custom exceptions.

Factory Classes: Responsible for creating users and managing system-wide operations such as stock updates and transaction tracking.

Proxy Classes: Used to mock database operations during testing to comply with the Single Responsibility Principle and facilitate smooth testing.

