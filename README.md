# DEPI RAM Web Server



A lightweight web server designed to manage domain authentication with a simple login interface for DEPI RAM. This project serves as a foundation for handling HTTP requests, user authentication, and serving static content.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview
The DEPI RAM Web Server is a minimalistic web application that provides a login interface for domain users. It is built to handle HTTP requests, serve a static login page, and can be extended to include backend authentication logic. This project is ideal for learning web server development and user authentication workflows.

## Features
- Simple and clean login interface for domain users
- Handles HTTP GET requests to serve the login page
- Supports static file serving (HTML, CSS)
- Customizable design and configuration
- Lightweight and easy to deploy

## Technologies Used
- **HTML/CSS**: For the frontend login interface
- **Web Server**: [To be specified, e.g., Python with http.server, Node.js with Express, etc.]
- **Tools**: Git for version control

## Installation
Follow these steps to set up the project locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/shimaaf0uad/Web_Server.git
   cd Web_Server
   ```

2. **Install dependencies** (if applicable):
   - If using Node.js:
     ```bash
     npm install
     ```
   - If using Python:
     ```bash
     pip install -r requirements.txt
     ```
   - If no dependencies are required, skip this step.

3. **Set up the server**:
   - Ensure you have the necessary runtime installed (e.g., Node.js, Python).
   - If using a simple HTTP server, no additional setup is needed.

## Usage
1. **Run the web server**:
   - If using Python's built-in HTTP server:
     ```bash
     python -m http.server 8000
     ```
   - If using Node.js (example with a custom server):
     ```bash
     node server.js
     ```
   - If using another method, specify the command here.

2. **Access the login page**:
   - Open your browser and navigate to:
     ```
     http://localhost:8000
     ```
   - You should see the DEPI RAM login page as shown in the screenshot above.

## Project Structure
```
Web_Server/
│
├── index.html         # Main login page
├── styles.css         # Styles for the login page (if applicable)
├── server.js          # Web server script (if using Node.js)
├── README.md          # Project documentation
└── LICENSE            # License file
```

## Configuration
- **Port**: The default port is `8000`. You can change it by modifying the server script or command.
- **Static Files**: The server serves files from the project directory by default. Update the directory path in the server script if needed.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m "Add feature"`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
- **Author**: Shimaa Fouad
- **GitHub**: [shimaaf0uad](https://github.com/shimaaf0uad)
- **Email**: [shimaa.fouad@example.com] (optional, replace with your email if desired)
