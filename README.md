# Cardiff University Open Day

This project is a simple web app for browsing programs available during the Cardiff University Open Day. It allows users to search and sort the programs by time or title and view detailed information about each topic and program, including location, description, and times.

## Features
- Displays detailed information about each program
- Has a search function for finding programs
- Includes sort functionality based on time or alphabetical order
## Setup

To run the project locally, follow these steps:

### 1. Prepare the Files
- Ensure that the `OpenDay.json` file is in the same folder as the `Open.html` file.


### 2. Run a Local Server
You can use a simple Python HTTP server to run this project locally. Open a terminal or command prompt in the project folder and run the following:

`python -m http.server`

### 3. View the Web App

Once the server is running, you can view the web app by navigating to the following URL in your browser:
`http://localhost:8000`

If you need to use a different port (in case port `8000` is already in use), you can specify a custom port like this and access the webapp at the specified port:

`python -m http.server portNumber`





