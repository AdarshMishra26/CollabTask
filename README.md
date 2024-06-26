# CollabTask

CollabTask is a comprehensive project management web application designed to streamline task creation, assignment, and tracking for teams. With features like user authentication, email verification, task filtering, and sorting, CollabTask is the perfect tool for boosting productivity and collaboration within your team.

## Features

* User registration and login with email verification
* Password reset functionality
* Task creation with assignee selection
* Task filtering by status (To Do, Done) and sorting by due date
* Task search functionality
* User roles and permissions
* Task comments and attachments
* Team management (creation, deletion)
* Error handling and pagination

## Technologies Used

* Flask: A lightweight web framework for building the application.
* PyMongo: A MongoDB driver for Flask to interact with the database.
* Flask-Login: A Flask extension for handling user authentication.
* Flask-Bcrypt: A Flask extension for securely hashing and storing passwords.
* Flask-Mail: A Flask extension for sending emails.
* Flask-WTF: A Flask extension for form handling and validation.
* WTForms: A library for creating forms in Flask applications.
* Unittest: A built-in Python library for testing the application.

## Installation

1. Clone the repository:
```
git clone https://github.com/your-username/collabtask.git
```
1. Navigate to the project directory:
```
cd collabtask
```
1. Create a virtual environment:
```
python -m venv venv
```
1. Activate the virtual environment:
```bash
source venv/bin/activate  # For Linux/macOS
venv\Scripts\activate  # For Windows
```
1. Install the required packages:
```
pip install -r requirements.txt
```
1. Configure the environment variables in a `.env` file:
```makefile
SECRET_KEY=your_secret_key
MONGO_URI=mongodb://localhost:27017/project_management
MAIL_SERVER=smtp.example.com
MAIL_PORT=587
MAIL_USE_TLS=True
MAIL_USERNAME=your_email@example.com
MAIL_PASSWORD=your_email_password
```
1. Run the application:
```
python app.py
```

## Usage

1. Access the application in your web browser at `http://127.0.0.1:5000/`.
2. Register a new user account and verify your email.
3. Log in and start creating tasks, teams, and managing your projects.

## Testing

To run the tests for the application, navigate to the project directory and execute the following command:

```
python -m unittest tests.py
```

## Contributing

Contributions to CollabTask are welcome! If you find any issues or want to suggest new features, please open an issue or submit a pull request.

## License

CollabTask is licensed under the [MIT License](LICENSE).

## Acknowledgements

CollabTask was inspired by the need for an efficient and user-friendly project management tool that fosters collaboration and productivity within teams. Special thanks to all the open-source libraries and tools used in the development of this application.

Happy collaborating! 🚀# CollabTask
