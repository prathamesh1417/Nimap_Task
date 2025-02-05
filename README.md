
🚀 ASP.NET Web Application  – Category & Product Management

📌 Overview

This ASP.NET Project provides CRUD operations for managing Categories and Products using Entity Framework (Code-First Approach). 
It supports server-side pagination for optimized data retrieval and efficient database queries.

✨ Features

✅ Code-First Approach – Models and DbContext are directly configured in the controllers.
✅ Category Management – CRUD operations for category entities.
✅ Product Management – CRUD operations for products with category association.
✅ Paginated Product List – Displays:

ProductId

ProductName

CategoryId

CategoryName
✅ Server-Side Pagination – Fetches only required records per page.

🏗️ Technologies Used

ASP.NET 

Entity Framework (Code-First)

SQL Server

📂 Project Structure

/AspNet
│-- Controllers/
│   ├── CategoriesController.cs
│   ├── ProductsController.cs
│-- Models/
│   ├── Category.cs
│   ├── Product.cs
│-- Data/
│   ├── ApplicationDbContext.cs
│-- Program.cs
│-- appsettings.json

🔧 Setup & Installation

1️⃣ Clone the Repository

git clone link
cd aspnet-product-category-api

2️⃣ Configure Database

Update appsettings.json with your SQL Server connection string.


3️⃣ Run Migrations

dotnet ef migrations add InitialCreate  
dotnet ef database update

4️⃣ Run the Application

dotnet run

💡 Future Enhancements

🔹 Add authentication & authorization.
🔹 Implement sorting & filtering.
🔹 Introduce caching for performance optimization.


---

🛠️ License

This project is open-source under the MIT License.
