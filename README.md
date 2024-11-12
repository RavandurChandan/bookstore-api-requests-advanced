Bookstore API Authentication and Book Management
This Python script demonstrates how to authenticate with a bookstore API, retrieve a list of books, and add a new book to the collection. The script makes use of the requests library to interact with the API.

Features:
Authentication: Sends a POST request with a username and password to generate an authentication token.
Retrieve Books: Sends a GET request to fetch the list of books available in the bookstore.
Add Book: Sends a POST request to add a new book to the user's collection.
Requirements:
Python 3.x
requests library
To install the required dependencies, run the following command:
pip install requests
How it works:
Authentication:
The script authenticates a user with the provided username and password by sending a POST request to the authentication endpoint. If successful, it retrieves an authentication token.

Get Book List:
Once authenticated, the script uses the token to send a GET request to the bookstore API to retrieve a list of books.

Add Book:
Finally, the script sends a POST request with a sample book to add it to the user's collection.

Usage:
To use the script:

Ensure that you have Python and the necessary libraries installed.
Modify the username and password in the cred dictionary if needed.
Run the script:
jupyter notebook requests_examples_demoqa.ipynb
