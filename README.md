# salary_predictions_api
 
## To Run This Application

Clone this repository to local computer

Create a new virtual environment

Windows: python -m venv ./venv
Mac: python3 -m venv ./venv
Activate the new virtual environment

Windows: .\venv\Scripts\activate
Mac: source ./venv/bin/activate
Install the dependencies pip install -r requirements.txt

Run the application with flask run a. To run a specific app: flask --app app run
b. To change the port: flask run --port 8080
c. To listen on all public IP addresses: flask run --host 0.0.0.0 d. To run in debug mode: flask run --debug

Example: flask --app app run --port 8080 --debug 
