# React + Vite + Axios + Json-server

# React App Boilerplate with Vite, Axios, and Json-Server

This boilerplate provides you with a ready-to-use setup for a React application using Vite, Axios, and Json-Server. It allows you to start developing your application immediately without worrying about setting up your development environment.

## Features

- **Vite:** A modern frontend build tool that offers faster and leaner development experience.
- **React:** A JavaScript library for building user interfaces.
- **Axios:** A promise-based HTTP client for making HTTP requests from Node.js or XMLHttpRequests from the browser.
- **Json-Server:** A simple tool to setup a REST API in seconds.

## Getting Started

1. **Clone the Repository**
    
    ```
    git clone <https://github.com/your-repo/react-app-vite-axios-json-server.git>
    ```
    
2. **Install Dependencies**
    
    ```powershell
    npm install
    ```
    
3. **Start the Development Server**
    
    ```powershell
    npm run dev
    ```
    

## Folder Structure

- **src:** This folder contains all the React code for your application.
- **public:** This folder contains the static files that you want to serve.
- **db:** This folder contains a `db.json` file which is used by Json-Server to create a mock REST API.

## Using Axios for HTTP Requests

You can use Axios to make HTTP requests to your Json-Server API. Here's an example of how to make a GET request:

```jsx
axios.get('/api/notes')
  .then(response => {
    console.log(response.data);
  });
```

## Running the Json-Server

The Json-Server runs on a separate port. You can start it with the following command:

```powershell
npm run server
```

This will create a mock REST API based on the `db.json` file in your `db` folder.

Please feel free to clone, modify, and use this boilerplate as you see fit. Happy coding!