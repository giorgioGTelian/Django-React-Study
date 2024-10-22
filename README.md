# Fullstack Application with Django and React

This project is a full-stack application built with Django and React. It provides a step-by-step guide on how to implement this solution.

## Project Structure

The project consists of two main folders:

1. `client`: This folder contains the React frontend of the application.
2. `server`: This folder contains the Python Django backend of the application.

```plaintext
project-root/
│
├── client/       # React frontend
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── ...
│
├── server/       # Django backend
│   ├── manage.py
│   ├── server/
│   ├── app/
│   ├── requirements.txt
│   └── ...
│
└── README.md
```

## Implementation Guide

To implement this solution, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the `client` folder and install the required dependencies using `npm install`.
3. Start the React development server using `npm start`.
4. Open another terminal window and navigate to the `server` folder.
5. Create a virtual environment and activate it.
6. Install the required Python packages using `pip install -r requirements.txt`.
7. Run the Django development server using `python manage.py runserver`.

### Setup and Installation

#### Backend (Django)

1. **Navigate to the server directory:**

   ```sh
   cd server
   ```

2. **Create a virtual environment:**

   ```sh
   python -m venv venv
   ```

3. **Activate the virtual environment:**

   - On Windows:

     ```sh
     venv\Scripts\activate
     ```

   - On macOS/Linux:

     ```sh

     source venv/bin/activate
     ```

4. **Install the required packages:**

   ```sh
   pip install -r requirements.txt
   ```

5. **Run database migrations:**

   ```sh
   python manage.py migrate
   ```

6. **Start the Django development server:**

   ```sh
   python manage.py runserver
   ```

#### Frontend (React)

1. **Navigate to the client directory:**

   ```sh
   cd client
   ```

2. **Install the required packages:**

   ```sh
   npm install
   ```

3. **Start the React development server:**

   ```sh
   npm start
   ```

### Running the Application

1. **Start the Django backend server:**

   ```sh
   cd server
   python manage.py runserver
   ```

2. **Start the React frontend server:**
python --version

   ```sh
   cd client
   npm start
   ```

3. **Access the application:**
   - The React frontend will be running on `http://localhost:3000`
   - The Django backend will be running on `http://localhost:8000`

### Additional Notes

- Ensure both servers are running simultaneously for the application to function correctly.
- You can customize the Django settings and React configurations as needed for your specific use case

## installing python and django

It looks like Python is not installed or not properly configured on your system. Here are the steps to install Python and set it up correctly:

### Step-by-Step Guide to Install Python on Windows

1. **Download Python:**

   - Go to the [official Python website](https://www.python.org/downloads/).
   - Download the latest version of Python for Windows.

2. **Install Python:**

   - Run the downloaded installer.
   - Make sure to check the box that says "Add Python to PATH" before clicking "Install Now".
   - Follow the installation prompts.

3. **Verify the Installation:**

   - Open a new PowerShell or Command Prompt window.
   - Run the following command to verify the installation:

     ```sh
     python --version
     ```

   - You should see the Python version number.

4. **Create a Virtual Environment:**
   - Navigate to your project directory:

     ```sh
     cd C:\Users\giorgio\PersonalProjects\Django-React-Study
     ```

   - Create a virtual environment:

     ```sh
     python -m venv env
     ```

5. **Activate the Virtual Environment:**
   - On Windows:

     ```sh
     .\env\Scripts\activate
     ```

6. **Install Django and Other Dependencies:**
   - Once the virtual environment is activated, install Django:

     ```sh
     pip install django
     ```

### Notes on installing python and django

- If you encounter any issues, make sure that the Python installation path is added to your system's PATH environment variable.
- You can manage your Python installations and virtual environments using tools like `pyenv` and `virtualenv`.

After completing these steps, you should be able to proceed with setting up your Django and React project as described in the README.
