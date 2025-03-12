# CoffeeBlend - Laravel Project

CoffeeBlend is a web-based Coffee Shop Management System built using Laravel. It allows users to manage menus, process orders, handle reservations, and integrate payment options efficiently.

## Models Included

- **User**: Handles authentication and user roles.
- **MenuItem**: Stores coffee shop menu items.
- **Order**: Manages customer orders and payments.
- **Reservation**: Handles table reservations.
- **Review**: Stores customer reviews and ratings.
- **Payment**: Processes payments via PayPal.
- **Admin**: Manages system settings and staff accounts.

## Installation Steps

1. **Start Apache and MySQL**  
   Ensure both services are running (e.g., via XAMPP or WAMP).

2. **Create a Database**  
   Create a MySQL database named **coffeeblend**.

3. **Import SQL File**  
   Import the provided SQL file into the database.

4. **Install Dependencies**
    ```bash
    composer install

5. **Run Laravel Server**  
   Open a terminal in the project folder(vs code) and run:
   ```bash
   cd coffeeblend
   php artisan serve
   npm run dev


Feel free to explore each folder to see the full details and code for each module.
