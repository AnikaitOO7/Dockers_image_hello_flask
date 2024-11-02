# Dockerized Hello World Flask App

This repository contains a simple "Hello World" web application built using **Flask** and **Docker**. It's a quick-start guide for setting up a minimal Flask app, Dockerizing it, and running it as a containerized service.

## 📂 Project Structure

```plaintext
.
├── app.py               # Main Flask application
├── Dockerfile           # Docker configuration for containerizing the app
├── requirements.txt     # Python dependencies for the app
└── README.md            # Project documentation
```

## 🛠 Prerequisites

Ensure you have the following installed:

- **Docker**: To containerize and run the application.
- **Git**: To clone the repository.

## 🚀 Getting Started

### 1. Clone the Repository

Clone this repository to your local machine:

```bash
git clone https://github.com/yourusername/hello-flask.git
cd hello-flask
```

### 2. Build the Docker Image

Build the Docker image using the following command:

```bash
docker build -t hello-flask .
```

This command creates a Docker image tagged as `hello-flask`.

### 3. Run the Docker Container

Run a container from the image you just built:

```bash
docker run -p 5000:5000 hello-flask
```

The Flask app will now be accessible at `http://localhost:5000`.

### 4. Verify the App

Visit `http://localhost:5000` in your browser, or use `curl` to verify:

```bash
curl http://localhost:5000
```

You should see:

```
Hello, World!
```

## 📄
