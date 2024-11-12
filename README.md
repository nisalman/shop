
# Salman's eCommerce

Salman's eCommerce is a versatile and modern eCommerce web application designed for efficient online shopping experiences. 
This platform offers users a range of features including product browsing, order tracking, flash sales, vendor management, 
and an admin dashboard to manage the entire ecosystem. Built with a user-friendly interface, it is ideal for both vendors and customers.

## Features

### User Interface
- **Homepage**: Displays a wide range of products across different categories.
- **Product Categories**: Users can browse products by category, including options like "Kid's Fashion" and flash sales.
- **Flash Sale Countdown**: A visually appealing countdown timer for ongoing flash sales, creating a sense of urgency for limited-time offers.
- **Search & Navigation**: Easy navigation with a search bar for quick access to products.
- **Responsive Design**: Compatible with multiple devices, including desktops, tablets, and smartphones.

### Admin Dashboard
- **Order Management**: Overview of today's orders, pending orders, and completed orders.
- **Earnings & Reviews**: Track earnings, view reviews, and monitor overall platform performance.
- **Product Management**: Add, edit, or remove products, manage categories, and handle vendor information.
- **Blog Management**: Includes a blog section for content marketing, with options to add and manage blog posts.
- **Analytics**: Real-time data on transactions, vendor stats, and total subscribers.
- **User Management**: Manage registered users, control access, and oversee customer interactions.

### Vendor Management
- **Multi-Vendor System**: Allow vendors to sign up, list products, and manage their offerings.
- **Sales Tracking**: Vendors can monitor their sales and manage their product listings effectively.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/nisalman/shop.git
   ```
2. Navigate to the project directory:
   ```bash
   cd shop
   ```
3. Install dependencies:
   ```bash
   composer install
   ```
4. Set up environment variables in `.env` file.
5. Run database migrations:
   ```bash
   php artisan migrate
   ```
6. Start the application:
   ```bash
   php artisan serve
   ```

## Technologies Used
- **Backend**: Laravel
- **Frontend**: HTML, CSS, JavaScript
- **Database**: MySQL
- **Version Control**: Git, GitHub

## License
This project is licensed under the MIT License.
