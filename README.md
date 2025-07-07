# My JavaScript Project

This project is a simple JavaScript application that logs a message to the console. It is designed to demonstrate the use of Jenkins for continuous integration and deployment.

## Files in the Project

- **echo.js**: Contains the JavaScript code that logs a message to the console.
- **Jenkinsfile**: Defines the Jenkins pipeline for building and running the project.
- **README.md**: This documentation file.

## How to Run the Project

1. Ensure you have Node.js installed on your machine.
2. Clone the repository to your local machine.
3. Navigate to the project directory.
4. Run the following command to execute the JavaScript file:

   ```
   node echo.js
   ```

This will output the message to the console. 

## Jenkins Pipeline

The Jenkins pipeline defined in the `Jenkinsfile` will automate the process of checking out the code, installing Node.js, and executing the JavaScript file. Make sure your Jenkins environment is set up to run Node.js jobs.