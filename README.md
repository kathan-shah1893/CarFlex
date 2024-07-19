# CarFlex 🚗

CarFlex is a web application built with Django for managing car rentals.

## Features

- 🚗 **Car Management**: CRUD operations for cars, including details like make, model, year, and availability.
- 📅 **Booking System**: Users can book cars based on availability and date range.
- 📝 **Admin Dashboard**: Separate dashboard for admins to manage cars, bookings, and users.
- 🔒 **Authentication and Authorization**: User authentication and roles (admin, customer).
- 📊 **Reporting**: Basic reporting features such as booking history and revenue generation.

## Technologies Used

- **Backend**: Django, Django REST Framework
- **Frontend**: HTML/CSS, Bootstrap (optional)
- **Database**: SQLite (for development), PostgreSQL (for production)
- **Deployment**: Heroku, AWS (optional)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/kathan-shah1893/CarFlex.git
   cd CarFlex
   ```

2. Create a virtual environment and activate it:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Apply migrations:

   ```bash
   python manage.py migrate
   ```

5. Create a superuser (admin):

   ```bash
   python manage.py createsuperuser
   ```

6. Run the development server:

   ```bash
   python manage.py runserver
   ```

7. Access the admin dashboard at `http://localhost:8000/admin/` to add cars and manage bookings.

## Usage

1. Navigate to `http://localhost:8000/` to view the CarFlex application.
2. Sign up as a customer or use the superuser account created to manage cars and bookings.
3. Explore the features of booking cars, viewing availability, and managing bookings.

## Contributing

Contributions are welcome! If you'd like to add features, improve existing ones, or fix issues, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by the need for a robust car rental management system.
- Built using Django, a powerful web framework in Python.


Happy coding with CarFlex! 🚀
