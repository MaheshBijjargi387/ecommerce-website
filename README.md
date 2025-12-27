# E-Commerce Website 🛒

A fully functional e-commerce website built using HTML, CSS, JavaScript, Django, and Bootstrap. This project provides a seamless shopping experience with features like product listings, user authentication, a shopping cart, and order management.

## ✨ Features

### Customer Features
- **Product Catalog**: Browse products with categories and filters
- **Product Search**: Find products quickly with search functionality
- **Product Details**: View detailed product information, images, and specifications
- **Shopping Cart**: Add, update, and remove items from cart
- **User Authentication**: Secure registration and login system
- **User Profile**: Manage personal information and view order history
- **Checkout Process**: Streamlined checkout with address and payment details
- **Order Management**: Track order status and history
- **Wishlist**: Save favorite products for later

### Admin Features
- **Product Management**: Add, edit, and delete products
- **Order Management**: View and update order status
- **User Management**: Manage customer accounts
- **Inventory Control**: Track stock levels
- **Dashboard**: Overview of sales and analytics

## 🛠️ Tech Stack

- **Backend**: Django 4.x (Python)
- **Frontend**: HTML5, CSS3, JavaScript, Bootstrap 5
- **Database**: SQLite (Development) / PostgreSQL (Production)
- **Authentication**: Django Authentication System
- **Payment**: Payment gateway integration ready

## 🚀 Installation & Setup

### Prerequisites
- Python 3.8 or higher
- pip (Python package manager)
- Virtual environment (recommended)

### Installation Steps

1. **Clone the repository**
```bash
git clone https://github.com/MaheshBijjargi387/ecommerce-website.git
cd ecommerce-website
```

2. **Create virtual environment**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

4. **Configure database**
```bash
python manage.py makemigrations
python manage.py migrate
```

5. **Create superuser**
```bash
python manage.py createsuperuser
```

6. **Load sample data (optional)**
```bash
python manage.py loaddata fixtures/sample_data.json
```

7. **Run development server**
```bash
python manage.py runserver
```

8. **Access the application**
- Frontend: `http://127.0.0.1:8000/`
- Admin Panel: `http://127.0.0.1:8000/admin/`

## 📁 Project Structure

```
ecommerce-website/
├── products/          # Product models and views
├── cart/             # Shopping cart functionality
├── orders/           # Order processing
├── accounts/         # User authentication
├── static/           # CSS, JS, images
├── templates/        # HTML templates
├── media/            # Product images
├── ecommerce/        # Project settings
└── manage.py         # Django management
```

## 🎯 Key Functionalities

### Product Management
- Category-based organization
- Product variants (size, color)
- Stock management
- Product ratings and reviews

### Shopping Experience
- Add to cart with quantity selection
- Cart total calculation
- Apply discount codes
- Multiple payment options

### Order Processing
- Order confirmation emails
- Order tracking system
- Invoice generation
- Order history

## 🔐 Security Features

- Secure password hashing
- CSRF protection
- SQL injection prevention
- XSS protection
- Secure payment processing

## 📱 Responsive Design

- Mobile-first approach
- Tablet and desktop optimized
- Cross-browser compatibility
- Fast loading times

## 🚧 Future Enhancements

- [ ] Payment gateway integration (Stripe/PayPal)
- [ ] Email notifications
- [ ] Product recommendations
- [ ] Advanced search filters
- [ ] Customer reviews and ratings
- [ ] Multi-language support
- [ ] Social media integration
- [ ] Live chat support

## 🧪 Testing

```bash
python manage.py test
```

## 📊 Database Schema

Key models include:
- User (Customer accounts)
- Product (Product information)
- Category (Product categories)
- Cart (Shopping cart items)
- Order (Customer orders)
- OrderItem (Individual order items)

## 🤝 Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Mahesh Bijjargi**
- GitHub: [@MaheshBijjargi387](https://github.com/MaheshBijjargi387)
- Email: maheshbijjargi387@gmail.com

## 🙏 Acknowledgments

- Bootstrap for responsive design
- Django community for excellent documentation
- Open source contributors

---

⭐ If you find this project useful, please give it a star!

💼 **Looking for opportunities?** I'm open to full-stack development roles!