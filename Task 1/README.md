# XOps Static Web App

## Steps to Run

1. Build the Docker image:

    ```bash
    docker build -t xops-web .
    ```

2. Run the Docker container:

    ```bash
    docker run -p 8080:80 xops-web
    ```

3. Open your browser and go to [http://localhost:8080](http://localhost:8080) to view the web app.

## Files

- `index.html`: The static web page.
- `Dockerfile`: Docker instructions to build the image.
