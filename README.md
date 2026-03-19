# Online Notepad

A web-based notepad application built with **ASP.NET Core MVC 8**.
Users can register, log in, create and manage documents using a rich text editor, with all data persisted in a SQL database.

## Features

* User registration and authentication (login/logout)
* Secure, user-specific document storage
* Full CRUD operations:

  * Create documents
  * Read/view documents
  * Update/edit documents
  * Delete documents
* Rich text editing via WYSIWYG editor
* Persistent storage using SQL

## Tech Stack

* **Framework:** ASP.NET Core MVC 8
* **Database:** SQL (e.g., SQL Server)
* **Authentication:** ASP.NET Core Identity
* **Editor:** Froala WYSIWYG Editor

## Third-Party Components

This project integrates the **Froala WYSIWYG Editor** as a third-party rich text editor.
It is used under its free/unpaid usage terms.

## Getting Started

### Prerequisites

* .NET 8 SDK
* SQL Server (or compatible SQL database)
* Visual Studio 2022 or another compatible IDE

### Installation

1. Clone the repository:

   ```
   git clone https://github.com/tim-maastricht/online-notepad.git
   ```

2. Open the solution in your IDE.

3. Configure the database connection string in `appsettings.json`.

4. Apply migrations (if applicable):

   ```
   dotnet ef database update
   ```

5. Run the application:

   ```
   dotnet run
   ```

## Usage

1. Register a new account or log in.
2. Create a new document.
3. Edit content using the integrated WYSIWYG editor.
4. Save, update, or delete documents as needed.

## Project Overview

* **Authentication:** Handles user registration and login
* **Document Management:** Stores and retrieves user-created documents in SQL
* **Editor Integration:** Provides rich text editing via Froala
* **CRUD Logic:** Enables full lifecycle management of documents

## License

This project is licensed under the **MIT License**.
