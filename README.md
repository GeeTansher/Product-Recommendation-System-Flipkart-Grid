# Flipkart Grid Personalized product recommendation system

Table of Contents
    Introduction
    Prerequisites
    Installation
    Running the Application
    Accessing ML Files
    Troubleshooting


1. Introduction
    The Flipkart Grid Personalized Product Recommendation System is a powerful application that combines advanced algorithms and user-friendly interfaces to provide personalized product recommendations for users.


2. Prerequisites
    Before you begin, ensure you have the following installed on your system:

    Node.js (for frontend setup)
    Python (for backend and Flask setup)


3. Installation
    Clone the Repository: Start by cloning this repository to your local machine.

    Frontend Setup:

    Navigate to the "website folder" using your terminal.
    Run cd frontend to enter the frontend folder.
    Run npm install to install frontend dependencies.
    Backend Setup:

    Navigate to the "website folder" using your terminal.
    Run cd backend to enter the backend folder.
    Create a virtual environment by running py -m venv env.
    Activate the virtual environment with .\env\Scripts\activate.
    # Requirement.txt is in backend folder
    Install backend dependencies by running python -m pip install -r requirements.txt.


4. Running the Application
    Start the Frontend:

    In the "website folder," navigate to the frontend folder using your terminal.
    Run npm start to host the frontend of the website.
    Access the website at http://localhost:3000/.
    Start the Backend:

    In the "website folder," navigate to the backend folder using your terminal.
    Run npm run start to start the backend server.
    Start the Flask Backend:

    Navigate to the "website folder" using your terminal.
    Move to the backend folder with cd backend.
    Run the Flask server with flask run.
    Access the Application:

    Open your web browser and go to http://localhost:3000/ to see the application in action.


5. Accessing ML Files
    For accessing machine learning files, models, and datasets, follow these steps:

    Navigate to the "ML" folder in the main project directory.
    Modify datasets and files as needed for your project's requirements.


6. Troubleshooting
    Due to data irregularities with the frontend schema, it was not feasible for us to put all of the data into the backend to display it on the website, so we have only taken a select few products. At this time, the website is still in the prototyping stage. It can be updated at any time with more information, including images for images and other details over time.
    
    If you encounter any issues during setup or running the application, refer to the following steps:

    Make sure you have the required software (Node.js, Python) installed and properly configured.
    Double-check that you're running backend, frontend, and Flask app in separate terminals.
    Ensure all necessary dependencies are installed by following the installation steps carefully.