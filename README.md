Building and Running Containers:

To build and run the containers defined in the docker-compose.yml, open a terminal and navigate to the project folder containing the docker-compose.yml file. Run the following command:

~docker-compose up
This command will build the Docker images (if not already built) and start all the services defined in the docker-compose.yml file. Your frontend, backend, and MongoDB containers will run together, and they'll be interconnected according to the specifications you defined.

Accessing the Application:

Once the containers are running, you can access your application through the exposed ports specified in the docker-compose.yml. In this example, the frontend is accessible at http://localhost:80, the backend at http://localhost:3000, and MongoDB at mongodb://localhost:27017.

Stopping the Containers:

To stop the containers and remove them, you can press Ctrl+C in the terminal where docker-compose up is running, or you can run:

~docker-compose down
