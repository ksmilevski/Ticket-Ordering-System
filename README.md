# Movie Ticket Ordering System

This repository contains a .NET-based web application designed to manage ticket orders for theatre and movie shows, alongside an administrative application for managing orders and related data. Developed using the Onion Architecture, this project is structured to ensure a clear separation of concerns, promoting maintainability and scalability.

## Features

### User Application
User Registration and Authentication: Users can register, log in, and manage their profiles, utilizing a custom implementation of the IdentityUser class.

Movies Management: Users can browse all available movies, which are presented in a Grid Layout format.

Ticket Ordering: Users can view available tickets and perform CRUD operations, including adding, editing, and deleting tickets.

Show Listings: A comprehensive view of all available movies is provided, allowing users to explore and select their preferred movies.
### Admin Application

Order Management: The admin panel provides a detailed view of all ticket orders, with functionalities to export order data to PDF.

Movie Import: Admins can import movie data into the system to keep the database updated.

Export Orders and Products: Admins can export all orders or individual order details and related products to PDF for reporting and record-keeping purposes.

## Technologies

Backend: .NET, ASP.NET Core

Frontend: HTML, CSS

Architecture: Onion Architecture

Database: Entity Framework Core, SQL Server

