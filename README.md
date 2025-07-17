# Movie Ticket Ordering System 🎬

The **Movie Ticket Ordering System** is a .NET-based web application designed to manage movie and theatre ticket reservations with both user-facing and administrative capabilities. Built using **Onion Architecture**, the system ensures a clean separation of concerns, making it maintainable, testable, and scalable.

## 🎯 Purpose
- Enable users to browse movies and manage ticket reservations.
- Provide admins with robust tools for managing movies, orders, and data exports.
- Apply enterprise-grade architectural principles to a practical application domain.

## 👤 User Application Features

### 🔐 Authentication & Profile Management
- **User Registration & Login:** Secure authentication system with custom `IdentityUser` implementation.
- **Profile Management:** Users can view and update their personal information.

### 🎟️ Ticket and Movie Interaction
- **Movie Catalog:** Browse available movies in a responsive Grid Layout.
- **Ticket Management:** Perform full CRUD operations—create, update, or delete tickets.
- **Show Listings:** Explore a detailed list of currently showing and upcoming movies.

## 🛠️ Admin Application Features

### 🧾 Order Management
- **View & Manage Orders:** Admins can track all ticket orders placed by users.
- **Export to PDF:** Order summaries and product details can be exported for reporting or archival.

### 🎬 Movie Management
- **Movie Import:** Admins can bulk-import movie data to ensure the catalog stays up to date.

### 📄 Data Export
- **Reports:** Export individual orders or comprehensive product lists in PDF format for administrative use.

## 🏗️ Technologies Used

- **Backend:** .NET, ASP.NET Core  
- **Frontend:** HTML, CSS  
- **Architecture:** Onion Architecture (Domain-Driven Design, Dependency Injection)  
- **Database:** Entity Framework Core, SQL Server

---

This project demonstrates a practical application of layered architecture and domain-driven design, making it suitable for real-world deployments in cinema chains, theater booking platforms, or academic showcase systems.
