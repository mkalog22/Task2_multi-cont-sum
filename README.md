This application is a multi-container environment set up using Docker Compose, consisting of a Python Flask web server and a MongoDB database. 

The MongoDB container stores a collection of numerical data. 
The Python Flask application connects to this MongoDB instance, retrieves the numerical data, computes the sum of the values, and displays the result as a JSON response. 

Access the Result on Localhost:
Open your web browser and navigate to http://localhost:5000 to see the sum displayed as JSON output.
