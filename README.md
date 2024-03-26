Ice Cream Parlour Website
This project is a web application built using Django and Python 3.10. It serves as a platform for customers to view available ice cream flavors, place orders, and manage their accounts.

Table of Contents
Features
Installation
Usage
Contributing
License
Features
User authentication: Allow users to register, log in, and manage their accounts.
Ice cream catalog: Display a list of available ice cream flavors with details such as name, description, and price.
Order management: Allow users to add ice cream flavors to their cart, place orders, and view their order history.
Admin panel: Provide administrators with the ability to manage ice cream flavors, orders, and user accounts.


Clone the repository:
bash
Copy code
git clone <repository-url>
Navigate to the project directory:
bash
Copy code
cd ice-cream-parlour
Create and activate a virtual environment:
bash
Copy code
python3 -m venv venv
source venv/bin/activate
Install dependencies:
Copy code
pip install -r requirements.txt
Run migrations:
Copy code
python manage.py migrate
Create a superuser (admin user) to access the admin panel:
Copy code
python manage.py createsuperuser
Start the development server:
Copy code
python manage.py runserver
Access the website at http://127.0.0.1:8000/.
Usage
Visit the website and create an account or log in if you already have one.
Browse the ice cream catalog to view available flavors and their details.
Add ice cream flavors to your cart and proceed to checkout to place an order.
As an admin, access the admin panel at http://127.0.0.1:8000/admin/ to manage ice cream flavors, orders, and user accounts.
Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature/<feature-name>).
Make your changes.
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature/<feature-name>).
Create a new pull request.
