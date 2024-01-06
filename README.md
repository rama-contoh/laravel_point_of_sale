## ✨ Laravel Point of Sale

Point of Sale Management and Invoice build with Laravel 10 and MySql.

![Dashboard](https://user-images.githubusercontent.com/71541409/234483153-38816efd-c261-4585-bb93-28639508f5e3.jpg)

## 😎 Features
- POS
- Orders
  - Pending Orders
  - Complete Orders
  - Pending Due
- Stock Management
- Products
  - Products
  - Categories
- Employees
- Customers
- Suppliers
- Salary
  - Advance Salary
  - Pay Salary
  - History Pay Salary
- Attendance
- Role and Permission
- Users Management
- Backup Database

## 🚀 How to Use

1.  **Clone Repository or Download**

    ```bash
    $ git clone https://github.com/rama-contoh/
    ```
1. **Setup**
    ```bash
    # Go into the repository
    $ cd laravel-point-of-sale

    # Install dependencies
    $ composer install

    # Open with your text editor
    $ code .
    ```
1. **.ENV**

    Rename or copy the `.env.example` file to `.env`
    ```bash
    # Generate app key
    $ php artisan key:generate
    ```

1. **Setup Database**

    Setup your database credentials in your `.env` file.

1. **Seed Database**
    ```bash
    $ php artisan:migrate:fresh --seed

    # Note: If showing an error, please try to rerun this command.
    ```
1. **Create Storage Link**

    ```bash
    $ php artisan storage:link
    ```
1. **Run Server**

    ```bash
    $ php artisan serve
    ```
1. **Login**

    Try login with username: `admin` and password: `password`

1. **Create Storage Link**

    ```bash
    $ php artisan storage:link
    ```
1. **Run Server**

    ```bash
    $ php artisan serve
    ```
1. **Login**

    Try login with username: `admin` and password: `password`

    or username: `user` and password: `password`

