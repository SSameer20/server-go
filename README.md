# Simple Go Web Server

This repository contains a simple web server written in Go. The server responds to three different routes: `/`, `/hello`, and `/headers`.

## Routes

### `/`

- **Description**: Serves the `index.html` file.
- **Response**: The contents of the `index.html` file.
- **Example**:
  ```bash
  curl http://localhost:8090/
  ```
  

  ```bash
  /hello
  ```
Description: Responds with a simple "hello" message.
Response: hello

/headers
Description: Responds with the request headers.
Response: A list of all request headers.
Example:
bash
Copy code
curl -H "Custom-Header: value" http://localhost:8090/headers
Getting Started
Prerequisites
Go (1.16 or higher)
Running the Server
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/simple-go-web-server.git
cd simple-go-web-server
Create an index.html file in the root directory of the project with some HTML content:

```bash
<!DOCTYPE html>
<html>
<head>
    <title>My Go Web Server</title>
</head>
<body>
    <h1>Welcome to my Go Web Server!</h1>
</body>
</html>
```
Run the server:

bash
Copy code
go run main.go
Open a web browser and navigate to http://localhost:8090 to see the content served from index.html.

License
This project is licensed under the MIT License.

