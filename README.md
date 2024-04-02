# E-Commerce Django Project with Bootstrap

This is an e-commerce web application built using Django and Bootstrap. It allows users to browse through products, add them to their cart, and make purchases. The project also includes an admin interface for managing products, orders, and users.

## Features

- User authentication and authorization system.
- Product browsing with category filtering.
- Cart management for adding and removing products.
- Checkout process with order summary and payment integration.
- Admin interface for managing products, orders, and users.
- Responsive design using Bootstrap for a seamless experience across devices.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/ecommerce-django.git
```

2. Navigate to the project directory:

```bash
cd ecommerce-django
```

3. Create a virtual environment:

```bash
python -m venv venv
```

4. Activate the virtual environment:

- On Windows:

```bash
venv\Scripts\activate
```

- On macOS and Linux:

```bash
source venv/bin/activate
```

5. Install dependencies:

```bash
pip install -r requirements.txt
```

6. Apply database migrations:

```bash
python manage.py migrate
```

7. Create a superuser account to access the admin interface:

```bash
python manage.py createsuperuser
```

8. Run the development server:

```bash
python manage.py runserver
```

9. Access the application at [http://localhost:8000](http://localhost:8000)

## Configuration

- You can customize the settings in `settings.py` file to suit your requirements.
- Ensure you set up proper environment variables for sensitive information like database credentials and secret key.

## Usage

- Browse through products by navigating to the home page.
- Add products to your cart and proceed to checkout.
- Admins can manage products, orders, and users by logging into the admin interface.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue if you encounter any bugs or have suggestions for improvements.

## License

This project is licensed under the MIT License.
