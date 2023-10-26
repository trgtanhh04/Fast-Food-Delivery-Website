# Fast Food Delivery Website
Intelligent User-Friendly Fast Food Ordering Website,
This is a project for a website selling soft drinks and bubble tea using HTML and the Django framework. This project serves as a sample demonstration of how to create a website for selling beverage products online with Django.

## Features
- Display a list of soft drinks and bubble tea products for users to choose from.
- Allow users to add products to their shopping cart.
- Show the total quantity and value of items in the cart.
- Collect order information and delivery address.
- Confirm orders and proceed to payment.

## Installation and Running the Project

1. Clone the project from the GitHub repository: [(https://github.com/Tienanh204/Fast-Food-Delivery-Website)](https://github.com/Tienanh204/Fast-Food-Delivery-Website)

2. Set up a virtual environment and install the required libraries:
cd your-repo
python -m venv venv
source venv/bin/activate (Linux/Mac) or venv\Scripts\activate (Windows)
pip install -r requirements.txt

3. Migrate the database and run the project:
python manage.py migrate
python manage.py runserver

4. Access the application in your web browser at [http://localhost:8000/](http://localhost:8000/).
   

## Illustrations
![Website Interface](https://github.com/Tienanh204/Fast-Food-Delivery-Website/blob/main/webbanhang/Demo1.png) ![Product Image](https://github.com/Tienanh204/Fast-Food-Delivery-Website/blob/main/webbanhang/Demo2.png)

## Project Structure

- `app/`: Directory containing the Django application of the project.
- `templates/`: Directory containing HTML templates.
- `static/`: Directory containing static files like CSS and images.
- `manage.py`: Django project management file.
- `requirements.txt`: List of required libraries.

## Contributions
If you wish to contribute to the project or report issues, please create an issue or submit a pull request.
