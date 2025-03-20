# Recipe Management Application 🍳

A full-stack web application for managing and sharing recipes. Users can create, save, edit, and browse recipes with secure authentication.

![Application Screenshot](screenshot.png) <!-- Add your screenshot here -->

## Features ✨
- User authentication (Register/Login/Logout)
- Create, edit, and delete recipes
- Save/unsave favorite recipes
- Responsive UI with image uploads
- Search and filter recipes
- Protected routes and error handling
- Recipe ownership management

## Technologies Used 🛠️
**Frontend:**
- React 18
- Redux Toolkit (State Management)
- React Router 6
- Formik & Yup (Form Validation)
- React Bootstrap (UI Components)
- Axios (HTTP Client)

**Backend:**
- ASP.NET Core 6
- Entity Framework Core
- SQL Server (Database)
- Cookie-based Authentication
- BCrypt (Password Hashing)
- Swagger (API Documentation)

## Prerequisites 📋
- [.NET 6 SDK](https://dotnet.microsoft.com/download)
- [Node.js](https://nodejs.org/) (v16+ recommended)
- [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)
- [Git](https://git-scm.com/)





appsettings.json:


"ConnectionStrings": {
  "DefaultConnection": "Server=YOUR_SERVER_NAME;Database=RecipeDB;Trusted_Connection=True;TrustServerCertificate=True;"
}



Database Name:    RecipeDB

Frontend Setup

cd ../Client
npm install







Start Backend

cd Backend_RecipeManagement




API will be available at:
https://localhost:5001/swagger/index.html


Dependencies used :
Frameworks:
 .AspNetCore.App
 Microsoft.NETCore.App
Packages:
 BCrypt.Net-Next (4.0.3)
 Microsoft.AspNetCore.Session (2.3.0)
 Microsoft.EntityFrameworkCore (9.0.3)
 Microsoft.EntityFrameworkCore.SqlServer
(9.0.3)
 Microsoft.EntityFrameworkCore.Tools (9.0.3)
 Microsoft.Extensions.Caching.Memory (9.0.3)
 Swashbuckle.AspNetCore (6.6.2)


