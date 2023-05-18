# Hotel Management System

This is a Hotel Management System built using Django, HTML, CSS, Bootstrap, JavaScript, and SQLite3 database. The system allows users to book rooms, sign up and log in as both users and staff members. Staff members have additional privileges such as adding locations and rooms, while users can book rooms and filter available rooms based on their preferences.

## Features

- User registration and login: Users can create an account and log in to the system.
- Staff registration and login: Staff members can create an account and log in to the system.
- Room booking: Users can search for available rooms and book them.
- Room filtering: Users and staff members can filter rooms based on preferences such as room type, location, or price.
- Staff privileges: Staff members can add new locations and rooms to the system.
- Three types of rooms: The system offers three types of rooms - premium, luxury, and deluxe.
- Responsive UI: The user interface is designed using Bootstrap, ensuring compatibility across different devices.

## Technologies Used

- Django: A high-level Python web framework that simplifies the development process.
- HTML: Markup language used for creating the structure and content of web pages.
- CSS: Stylesheet language used for describing the presentation of a document written in HTML.
- Bootstrap: A front-end framework that provides pre-designed templates and components for building responsive websites.
- JavaScript: A programming language that enables interactive features and dynamic content on web pages.
- SQLite3: A lightweight and file-based database engine used for storing application data.

## Installation

To run the Hotel Management System locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/hotel-management-system.git
   ```

2. Navigate to the project directory:

   ```bash
   cd hotel-management-system
   ```

3. Create and activate a virtual environment (optional but recommended):

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

4. Install the project dependencies:

   ```bash
   pip install -r requirements.txt
   ```

5. Apply the database migrations:

   ```bash
   python manage.py migrate
   ```

6. Start the development server:

   ```bash
   python manage.py runserver
   ```

7. Open a web browser and visit `http://localhost:8000` to access the Hotel Management System.

## Usage

1. Sign up as a user or staff member using the provided registration form.
2. Log in using your credentials.
3. If you are a staff member, you will have access to additional features such as adding locations and rooms.
4. If you are a user, you can search for available rooms, filter them based on your preferences, and book a room.
5. Enjoy using the Hotel Management System!

## Contributing

Contributions are welcome! If you'd like to contribute to the Hotel Management System, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and test them thoroughly.
4. Commit your changes and push them to your fork.
5. Submit a pull request detailing your changes.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

The Hotel Management System is developed by Prapti Bankar. Special thanks to the Django community and all the open-source contributors whose libraries and frameworks were used in this project.

## Contact

If you have any questions or suggestions regarding the Hotel Management System, please feel free to contact praptibankar@gmail.com. We appreciate your feedback and support.
