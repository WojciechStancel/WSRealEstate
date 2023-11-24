# WS Real Estate (old-repository)

**Currently, app is hosted on AWS, repository with all informations are here: https://github.com/WojciechStancel/Real-Estate**
---
Welcome to the WS Real Estate Agency web application. This application is built using Django for the backend and Bootstrap for the frontend. It serves as a platform for managing real estate listings, allowing users to browse and add property listings, as well as providing authentication and registration features. The application utilizes a PostgreSQL database, and it was hosted on Digital Ocean with Nginx as the web server. 

## Features

- **Property Listings:** Browse and search for available real estate listings.
- **User Authentication:** Register and log in securely to access additional features.
- **Listing Management:** Registered users can add and manage their property listings.
- **Admin Panel:** Administrators can manage users, listings, and website content.
- **Database:** The application uses PostgreSQL for data storage, ensuring data integrity and security.
- **Hosting:** The application was hosted on Digital Ocean.

## Technology Stack

- Backend: Django
- Frontend: Bootstrap
- Database: PostgreSQL
- Web Server: Nginx
- Hosting: Digital Ocean

## Installation

To set up this application locally, follow these steps:

1. Clone this repository: `git clone https://github.com/WojciechStancel/WSRealEstate.git`
2. Navigate to the project directory: `cd WSRealEstate`
3. Install Python dependencies: `pip install -r requirements.txt`
4. Create a PostgreSQL database and configure the database settings in `settings.py`.
5. Makemigrations: `python manage.py makemigrations`
6. Run database migrations: `python manage.py migrate`
7. Start the Django development server: `python manage.py runserver`

For a production deployment, you will need to configure Nginx and gunicorn to serve the application.

## Acknowledgments

I would like to acknowledge Brad Traversy (https://github.com/bradtraversy) for the tools and resources that made this project during Python Django Dev to Deployment Course. It was a big pleasure to learn new stuff. 

Link to course: https://www.udemy.com/course/python-django-dev-to-deployment/

---

> My Website 💻 [CodeCr8ive.pl](https://www.codecr8ive.pl) &nbsp;&middot;&nbsp;
> My account on
[Github <img width="20px" src="https://github.com/WojciechStancel/Notes-React-App/assets/121879383/fc63de6c-91ae-4eb7-ac97-a5a365bdf073)">](https://github.com/WojciechStancel) &nbsp;&middot;&nbsp;
> Find me on
 [Linkedin <img width="20px" src="https://github.com/WojciechStancel/Notes-React-App/assets/121879383/94d42b30-025f-4997-9ff5-9491c49d9026">](https://www.linkedin.com/in/wojciech-stancel/) 
