# Inventory Management System

## Project Overview

The **Inventory Management System** is a desktop application developed using C# and Windows Forms (.NET 8). It is designed to help businesses manage their inventory operations efficiently by providing tools for tracking products, managing suppliers, recording stock movements, and generating reports.

The system provides a user-friendly graphical interface that simplifies inventory management and helps reduce manual work and errors.

## Technologies Used

- **Programming Language:** C#
- **Framework:** .NET 8
- **Application Type:** Windows Forms Desktop Application
- **Database:** SQLite
- **Database Library:** Microsoft.Data.Sqlite
- **IDE:** Visual Studio 2022

## Main Features

### 1. Dashboard
- Displays an overview of inventory information.
- Shows key performance indicators (KPIs).
- Provides visual summaries of inventory data.

### 2. Products Management
- Add new products.
- Edit existing product information.
- Delete products.
- Search and filter products.
- Track product quantities and prices.

### 3. Suppliers Management
- Add and manage suppliers.
- Update supplier information.
- View supplier details.

### 4. Stock Movements
- Record stock-in operations.
- Record stock-out operations.
- Track inventory movement history.
- Monitor changes in product quantities.

### 5. Reports
- Generate inventory reports.
- View inventory statistics.
- Display charts and summaries.

### 6. Settings
- Manage application settings.
- Configure available system options.

### 7. Authentication and User Management
- User login system.
- First administrator account setup.
- Change password functionality.
- Manage application users.

## Project Structure

```text
InventoryManager/
│
├── InventoryManager.sln
│
└── InventoryManager/
    ├── InventoryManager.csproj
    ├── Program.cs
    ├── Forms/
    ├── Panels/
    ├── Controls/
    ├── Database/
    └── Other application files
```

*Note: The actual folder structure may vary depending on the project organization.*

## Requirements

To run the application, you need:

- Windows 10 or Windows 11.
- Visual Studio 2022.
- .NET 8 SDK.
- .NET 8 Windows Desktop Runtime.
- NuGet package restoration support.

## Installation and Setup

1. Download or extract the project ZIP file.
2. Open `InventoryManager.sln` using Visual Studio 2022.
3. Allow Visual Studio to restore the required NuGet packages.
4. Select the appropriate build configuration.
5. Build the solution using:

   `Build → Rebuild Solution`

6. Run the application by pressing `F5` or clicking Start.

## Database

The application uses SQLite for local database storage.

The database is designed to store application data such as products, suppliers, stock movements, and user information.

The database file is managed locally by the application.

## Academic Information

**Course:** CS312 – Modern Development Tools

**Project Title:** Inventory Management System

**Project Type:** Desktop Application

**Development Framework:** C# Windows Forms (.NET 8)

**Academic Institution:** Misr University for Science and Technology (MUST)

**Group Number:** [Enter Group Number]

**Team Members:**
- [Student Name] – [Student ID]
- [Student Name] – [Student ID]
- [Student Name] – [Student ID]

## License

This project was developed for academic purposes as part of the CS312 – Modern Development Tools course.

---

**Inventory Management System – Efficient Inventory Tracking and Management.**
