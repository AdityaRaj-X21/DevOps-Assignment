# DevOps-Assignment
Demonstrate your basic ability to work with simple Docker features.
---

# Hello Node Dockerized

Welcome to the "Hello Node Dockerized" project! This project is a demonstration of basic Docker features, showcasing how to containerize a simple Node.js application using Docker and Docker Compose.

## About

This project consists of a simple Node.js/Express REST API that returns a "Hello, World!" response on port 3000. It serves as a minimalistic example to understand the process of containerizing a Node.js application and running it using Docker.

## Getting Started

To get started with this project, follow these steps:

1. **Clone the Repository**: Clone this repository to your local machine using the following command:
   ```
   git clone <repository_url>
   ```

2. **Install Dependencies**: Navigate to the project directory and install the required dependencies using npm:
   ```
   cd hello-node
   npm install
   ```

3. **Run the Application Locally**: Start the Node.js server locally using the following command:
   ```
   node main.js
   ```

4. **Access the API**: Open a web browser and navigate to http://localhost:3000 to access the API endpoint and see the "Hello, World!" response.

## Dockerization

This project includes a Dockerfile and a docker-compose.yml file to containerize the Node.js application using Docker. Here's how to run the application in a Docker container:

1. **Build Docker Image**: Build the Docker image using the Dockerfile:
   ```
   docker build -t hello-node .
   ```

2. **Run Docker Container**: Run the Docker container using the built image:
   ```
   docker run -p 3000:3000 hello-node
   ```

3. **Access the API**: Open a web browser and navigate to http://localhost:3000 to access the API endpoint and see the "Hello, World!" response served from the Docker container.

## Docker Compose

Alternatively, you can use Docker Compose to manage the Docker containers. Here's how to run the application using Docker Compose:

1. **Start Docker Compose**: Run the following command to start the services defined in the docker-compose.yml file:
   ```
   docker-compose up
   ```

2. **Access the API**: Open a web browser and navigate to http://localhost:3000 to access the API endpoint and see the "Hello, World!" response served from the Docker container managed by Docker Compose.

## Contribution

Contributions are welcome! If you find any issues or have suggestions for improvement, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to customize this README to fit the specifics of your project. You can include additional sections such as "Dependencies," "Usage Examples," or "Troubleshooting" if needed. Additionally, make sure to replace `<repository_url>` with the actual URL of your GitHub repository.

Once you've added this description to your README file, your project documentation will provide clear instructions on how to set up and run the application using Docker, making it accessible for other developers to understand and contribute to.
