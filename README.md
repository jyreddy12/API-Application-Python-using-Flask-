# API-Application-Python-using-Flask-
API Application Using Flask
===========================

This is a Python-based API application built using Flask. It provides a simple interface to add, view, and delete items in a database. The database is an in-memory list for demonstration purposes.

Features
--------
- Add items to the database via a POST request.
- View all items in the database via a GET request.
- Delete items from the database via a POST request.

Available Endpoints
-------------------
1. **Add an Item**
   - URL: `/add`
   - Method: POST
   - Request Body: JSON object representing the item to add.
   - Response: A success message with the updated database.

2. **View Items**
   - URL: `/view`
   - Method: GET
   - Response: A list of all items in the database.

3. **Delete an Item**
   - URL: `/delete`
   - Method: POST
   - Request Body: JSON object representing the item to delete.
   - Response: A success or failure message based on whether the item was found.

System Requirements
-------------------
- Python 3.7 or above
- Flask library

Setup and Run
-------------
1. Install Python from the official Python website: https://www.python.org/
2. Install Flask by running the command:
   ```bash
   pip install flask
