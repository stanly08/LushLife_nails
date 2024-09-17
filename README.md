This a web app that deals with a nail beauty parlor

Key Features:
Home/base: Main landing page.
Offers: Display current offers.
Signup/Login: User authentication with Flask-WTF.
Dashboard: Personalized dashboard for logged-in users.


Below are the technologies used;

Frontend Technologies:
HTML5: For structuring your web pages like offers.html, signup.html, login.html, etc.

CSS3 (Inline Styling): Since you prefer inline styles, you can directly embed CSS within the HTML elements to style my pages.

Bootstrap 5: To quickly style your web app using pre-built responsive components (like forms, buttons, grids, etc.).

Backend Technologies:
Python: To handle the server-side logic.

Flask: A lightweight Python web framework for routing and handling requests, which is suitable for small to medium web apps.

Jinja2: Flask's templating engine, which you'll use to render your HTML files (like base.html, dashboard.html) and pass data between the server and the client.

Database:
SQLite (or MySQL for more scalability): For storing user data like login information, offers, etc.

Other Technologies:
Flask-WTF: For form handling, such as the signup and login forms.

Flask-Bcrypt: To securely hash and store user passwords.

Flask-SQLAlchemy: For managing the database within Flask.

Flask-Login: For managing user sessions and authentication.

Static Files:
Flask Static Folder: Even though you're using inline styling, you should have a static folder for your images, JavaScript, and any other static files.

```
lush_life_nails/
│
├── app/
│   ├── __init__.py         # Initializes the Flask app
│   ├── routes.py           # Contains route logic for the app
│   ├── models.py           # (optional) Define models if using a database
│   ├── templates/          # All HTML templates
│   │   ├── base.html       # Base layout template
│   │   ├── offers.html     # Offers page
│   │   ├── signup.html     # Signup page
│   │   ├── login.html      # Login page
│   │   ├── dashboard.html  # Dashboard page
│   └── static/             # Static assets (Images)
│       └── images/
│           └── logo.png    # Placeholder image (social media icons, etc.)
│
├── run.py                  # Entry point to run the Flask app
├── requirements.txt        # Dependencies for the project (Flask, etc.)
└── README.md               # Optional README file to describe the project

```
