**Talking Lands**

Welcome to the Talking Lands project repository. This project was developed using Python as the backend language, leveraging the FastAPI framework, and MongoDB as the spatial database.

Tech Stack:
Backend Language: Python
Framework: FastAPI
Database: MongoDB (with GeoJSON for spatial data handling)
Getting Started
Follow the instructions below to clone the repository, set up the environment, and run the project.

1. Clone the Repository
First, clone the repository to your local machine using the following command:
git clone https://github.com/Santhosh-M-personal/Talking-Lands.git
Navigate to the project directory:
   
        cd Talking-Lands


3. Create and Activate a Virtual Environment
   It's recommended to use a virtual environment to manage dependencies. Run the following commands to create and activate the virtual environment:
   For Windows:
   
        python -m venv venv
        venv\Scripts\activate

   For macOS/Linux:
   
        python3 -m venv venv
        source venv/bin/activate

5. Install the Required Dependencies
   Once the virtual environment is activated, install the necessary dependencies using pip:
   
        pip install -r requirements.txt


7. Run the Application
   With the environment set up and dependencies installed, you can run the application:
   
        python main.py

   This command will start the FastAPI application, which will be hosted locally.


9. Access the API Documentation
   FastAPI automatically generates interactive API documentation using Swagger. You can access it by navigating to:
        
        http://127.0.0.1:8000/docs
        
   By appending /docs to the base URL, you will be redirected to the Swagger UI, where you can explore and interact with the API endpoints.
