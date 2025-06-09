## Setting Environment for running application:

### Required Software :

- VS Code (Editor)
- Node (For React)
- JDK
- IntelliJ IDEA (Editor)
- Docker (Running Backend)
- Postman (API testing)

### Environment Setup:

1. fork the repository
2. GIT Clone:

    ```bash
    git clone --recurse-submodules https://github.com/Manoj-14/rapid-tanker.git
    ```

### Backend Setup (Using Docker):

1. Go to directory TankerBackend:

    ```bash
      cd TankerBackend
    ```

1. create docker.env file TankerBackend folder and add these key and values
    
    ```
      GIT_USERNAME=
      GIT_PASSWORD=
      DATABASE_URL=
      DATABASE_USERNAME=
      DATABASE_PASSWORD=
      apiKey=
    ```
    
2. Run the docker compose file

    ```bash
    docker compose up
    ```

### Frontend Setup:

1. Go to directory TankerFrontend:

    ```bash
    cd TankerFrontend
    ```

1.  Install node modules

    ```bash
    npm install .
    ```

1.  Running Frontend:
     ```bash
      npm run start
    ```
