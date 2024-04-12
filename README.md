Certainly! Here's the updated guide with the additional step to create a `.env` file and add the database connection parameters:

## Hospital Management System

This project is a Hospital Management System built using Node.js, Express, MySQL, and EJS. Follow these steps to set it up:

### Installation

1. **Clone or Download**: First, clone or download the project from the repository.

2. **Open Command Prompt**: Navigate to the project folder in the command prompt.

3. **Install Dependencies**: Run the following command to install the project dependencies:
   ```
   npm install
   ```
   or if you already have the dependencies installed and want to update them, you can use:
   ```
   npm update
   ```

4. **Create `.env` File**: Create a file named `.env` in the project folder, and add the following parameters with their respective values:
   ```
   SQL_HOST="XXXX.."
   SQL_USER="XXX.."
   SQL_PASS="XXXXXX.."
   ```

   Replace `"XXXX.."`, `"XXX.."`, and `"XXXXXX.."` with your actual MySQL database host, username, and password respectively.

5. **Import Database**: Import the provided database file into your MySQL server.

6. **Run the Application**: Start the application by running:
   ```
   nodemon app
   ```
   or
   ```
   node app
   ```

### Screenshots

Here are some screenshots of the application:

#### Home
![Home](screenshot/home.PNG)

#### Sign Up
![Sign Up](screenshot/signup.PNG)

#### Dashboard
![Dashboard](screenshot/dash.PNG)

#### Medicine Store
![Medicine Store](screenshot/med.PNG)

#### Report Generation
![Report Generation](screenshot/report.PNG)

#### Add Employee Leave
![Add Employee Leave](screenshot/leave.PNG)

---

Feel free to adjust the instructions and screenshots as needed. Let me know if you need further assistance!