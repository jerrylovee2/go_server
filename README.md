# Simple Go Web Server Example

## Features:
- **Static File Serving:** The server serves static files from the `./static` directory.
- **Form Handling:** It handles POST requests to `/form`, parsing form data (`name` and `address`).
- **Hello Handler:** Responds with "Hello!" to GET requests to `/hello`.

## Usage:

bash
Copy code
git clone <repository-url>
cd <repository-name>
Run the Server:

bash
Copy code
go run main.go
The server will start on port 8081.

Access the Server:

Open a web browser and go to http://localhost:8081 to access static files.
POST to http://localhost:8081/form with form data to see the parsed results.
GET http://localhost:8081/hello to see "Hello!" response.
Requirements:
Go (1.11 or newer recommended) installed on your machine.
Notes:
Make sure to have a ./static directory with static files for serving.
Customize handlers (formhandler and hellohandler) for your application's specific needs.

Author: Nitish Ahir
