# Flask Basic Web Application

This is a simple Flask web application that demonstrates how to build a web app using Python and Flask. The app includes basic routes and integrates with a database using SQLite for storing user information.

# Features

- A simple homepage that displays a welcome message.
- A user registration form that allows users to sign up.
- Data is stored in an SQLite database.
- Basic styling with custom CSS.

# Technologies Used

- **Flask**: Web framework for building the app.
- **SQLite**: Database used to store user information.
- **HTML/CSS**: For structuring and styling the web pages.

## Project Structure

flask_app/

├── app.py              # Main application file 

├── example.db          # SQLite database file 

├── requirements.txt    # Python dependencies 

├── templates/ 

└── home.html           # Main homepage HTML file 

└── static/ 

├── css/ 

└── styles.css         # CSS file for styling


### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/gunjan1223/Flask-App.git

   cd flask-basic-app
   
   pip install -r requirements.txt

2. Run the Flask application:
    ```bash
     python app.py

3. Open your web browser and go to:
   ```bash
   http://127.0.0.1:5000

### Database Setup
The app uses SQLite as the database.

On the first run, the app will create a example.db SQLite database file automatically.

If you want to reset the database, simply delete the example.db file and restart the app.

### Endpoints

Home: GET /

  Displays the homepage and the user registration form.
  
Register User: POST /register

  Handles form submission for user registration. User data is stored in the SQLite database.
  
### Dependencies

The required dependencies are listed in the requirements.txt file:
1. Flask
2. SQLite (comes pre-installed with Python)
3. Other necessary packages (if any)

You can install them by running:
   ```bash
  pip install -r requirements.txt
