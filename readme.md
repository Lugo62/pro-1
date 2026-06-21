User Management Web Application
Project Overview
The objective of this task is to build a complete "User Management Web Application" using Python (Flask), HTML, CSS, and SQLite. This project demonstrates how the frontend, backend, and database work together as one integrated system, mirroring real-world industry web applications.
Technologies Used
Backend: Python with the Flask framework to handle server-side logic and requests.
Frontend: HTML for creating the structure (forms and tables) and CSS for styling the user interface.
Database: SQLite for permanent storage of user records.
Tools: VS Code for writing code and a web browser for testing the application.
Project Flow
The application follows a simple end-to-end flow to manage user data:
Frontend Interaction: A user enters their name and email into an HTML form on the web page.
Form Submission: When the user clicks "Add User," the data is sent to the Flask backend through a POST request.
Database Storage: The backend receives this information and executes a SQL command to insert the data into the users table in database.db.
Data Retrieval: After saving the new user, the application fetches all current records from the SQLite database.
Dynamic Display: The retrieved data is sent back to the frontend, where it is displayed in a styled table for the user to view.
Project Structure
The project is organized into a standard directory layout used in professional Flask development:
app.py: Main backend code.
database.db: The SQLite database file.
templates/index.html: The HTML user interface.
static/style.css: The stylesheet for visual design.
