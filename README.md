# Movie Ticket Booking Management System

## Overview

The Movie Ticket Booking Management System is a software application built using C# and SQL Server, designed to manage movie ticket bookings. This Windows application features an admin interface for managing tasks and user management, along with a user registration form and login form.

## Key Features

### Technologies:
- **Language:** C#
- **Framework:** .NET Framework 4.7.2
- **Database:** SQL Server

### Features:
- **Admin Form:** Interface for administrative tasks and user management.
- **Registration Form:** Register new users into the system.
- **Login Form:** Access the system with existing credentials.

## Project Structure

- **Admin Form:** Provides administrative functionalities for managing the system.
- **RegistrationForm:** Allows new users to register in the system.
- **Form1:** Handles user login with existing credentials.

## Getting Started

### Prerequisites

- .NET Framework 4.7.2 SDK
- SQL Server

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/Movie-Ticket-Booking-Management-System.git
    ```

2. **Open the solution in Visual Studio:**

    Navigate to the project directory and open `MovieTicketBookingManagementSystem.sln` with Visual Studio.

3. **Restore NuGet packages:**

    In Visual Studio, go to `Tools > NuGet Package Manager > Manage NuGet Packages for Solution` and restore the necessary packages.

### Configuration

Update the connection strings and other configurations in `RegistrationForm.cs` and `Form1.cs`:

```csharp
string conn = @"Your Connection String";
