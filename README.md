# Project Setup

## Creating the Project

1. Create a new folder for the project:
    ```bash
    mkdir example-project
    ```
2. Navigate into the project directory:
    ```bash
    cd example-project
    ```

## Setting Up the Frontend

1. Inside of `example-project`, create a new project called `frontend` and choose the React option:
    ```bash
    npx create-vite@latest frontend --template react
    ```
2. Navigate into the `frontend` directory:
    ```bash
    cd frontend
    ```
3. Install the dependencies:
    ```bash
    npm install
    ```
4. Run the development server:
    ```bash
    npm run dev
    ```
5. Open your browser and navigate to the address shown in the terminal.

## Setting Up the Backend

1. Inside of `example-project`, create a new folder called `backend`:
    ```bash
    mkdir backend
    ```
2. Navigate into the `backend` directory:
    ```bash
    cd backend
    ```
3. Create a virtual environment:
    ```bash
    python3 -m venv .venv
    ```
4. Activate the virtual environment:
    ```bash
    source .venv/bin/activate
    ```
5. Install the requirements:
    ```bash
    pip install -r requirements.txt
    ```
6. Run the server:
    ```bash
    python manage.py runserver
    ```