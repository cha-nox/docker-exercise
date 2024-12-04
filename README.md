# Requirements
- Docker

# Setup instructions
1. Clone the repository.
    ```sh
    cd path/to/your/directory
    git clone https://github.com/your-username/your-repo.git
    ```
2. Build the Docker image.
    ```sh
    docker build -t docker-exercise:latest ./app
    ```
3. Run the Docker container.
    ```sh
    docker-compose up -d
    ```
4. Enjoy [your app](http://127.0.0.1:3000) !

# Additional informations
- You can run `docker ps` to see informations about the running containers. These informations includes the status of the last healthcheck under de "STATUS" section.