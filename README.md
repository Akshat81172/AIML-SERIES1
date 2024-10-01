Project Description
The Basic Q&A Bot for College Admission is a simple web-based chatbot designed to assist users with inquiries related to college admissions. The bot can answer questions regarding admission requirements, application processes, and deadlines, providing a user-friendly interface for prospective students seeking information.

Technologies Used
Python:

The backend of the chatbot is built using Python, a versatile and widely-used programming language that is well-suited for web development and natural language processing tasks.
Flask:

Flask is a lightweight web framework for Python that allows for easy development of web applications. It handles routing, requests, and responses, making it simple to create a RESTful API for the chatbot.
NLTK (Natural Language Toolkit):

NLTK is a leading platform for building Python programs to work with human language data. It provides tools for text processing and supports various natural language processing tasks. In this project, it is used to create a basic chatbot that can respond to user queries based on predefined patterns.
HTML/JavaScript:

The frontend is developed using standard HTML and JavaScript. HTML structures the content of the web page, while JavaScript is used to handle user interactions and send requests to the Flask backend. The JavaScript code fetches responses from the chatbot and updates the chatbox dynamically.
JSON:

JSON (JavaScript Object Notation) is used for data interchange between the client (frontend) and the server (backend). The chatbot receives user input in JSON format and sends responses back to the frontend in the same format.
Features
User Interaction:

The bot engages users in a conversational manner, allowing them to ask multiple questions in a single session.
Error Handling:

The chatbot includes basic error handling for unrecognized queries, providing users with helpful feedback when their questions cannot be addressed.
Scalability:

The current implementation can be easily extended with more Q&A pairs, additional features, or integration with a backend database for real-time data retrieval.
