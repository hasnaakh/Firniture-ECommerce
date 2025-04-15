# 🪑 Firniture E-Commerce Website

An elegant and fully functional **E-Commerce Website for Furniture** built using **ASP.NET Core MVC (.NET 6)**. This platform allows users to browse, search, and purchase furniture products, while admins can manage products, categories, and customer orders through a dedicated dashboard.

## 🚀 Features

### 🛍️ Customer Side
- Browse furniture by category
- Detailed product pages
- Add to cart & checkout
- User authentication (Register/Login)
- Order history and details

### 🛠️ Admin Panel
- Manage furniture products (CRUD)
- Manage categories and subcategories
- View and manage customer orders
- Dashboard with statistics and order tracking

### 💡 Technical Stack
- **Backend:** ASP.NET Core MVC (.NET 6)
- **Frontend:** Razor Pages, Bootstrap 5
- **Database:** SQL Server + Entity Framework Core
- **Authentication:** ASP.NET Identity


## ⚙️ Getting Started

### Prerequisites
- [.NET 6 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/6.0)
- SQL Server (or SQL Express)
- Visual Studio 2022 or VS Code

### Setup Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/hasnaakh/Firniture-ECommerce.git
   cd Firniture-ECommerce
   ```

2. **Configure your database**
   - Update your connection string in `appsettings.json`.

3. **Apply migrations and seed data**
   ```bash
   dotnet ef database update
   ```

4. **Run the application**
   ```bash
   dotnet run
   ```

5. **Visit in browser**
   ```
   http://localhost:5000
   ```


