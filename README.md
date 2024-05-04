<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<h1>React App Documentation</h1>

<h2>Overview</h2>

<p>This document provides detailed documentation for a React application designed for uploading and managing resumes. The application interacts with a backend server to handle file uploads, data retrieval, and deletion. It includes information about dependencies, components, functionality, server interaction, setup instructions, and additional notes.</p>

<h2>Dependencies</h2>

<p>The React application relies on the following dependencies:</p>

<ul>
    <li><strong>React</strong>: A JavaScript library for building user interfaces.</li>
    <li><strong>axios</strong>: A promise-based HTTP client for the browser and Node.js.</li>
    <li><strong>@chakra-ui/react</strong>: A modular and accessible component library for React applications.</li>
</ul>

<h2>Components and Functions</h2>

<p>The main components and functions of the React application are:</p>

<ul>
    <li><strong>Main Component</strong>: The primary component responsible for rendering the application interface and handling user interactions.</li>
    <li><strong>useState Hook</strong>: Manages component state for input fields, file selection, data, loading states, error messages, and pagination.</li>
    <li><strong>useEffect Hook</strong>: Fetches data from the backend server when the component mounts or when the current page changes.</li>
</ul>

<h2>Functionality</h2>

<p>The React application provides the following functionality:</p>

<ul>
    <li><strong>File Upload</strong>: Allows users to upload their resumes along with their name and password.</li>
    <li><strong>Data Display</strong>: Displays a list of uploaded resumes with options to download or delete each resume.</li>
    <li><strong>Pagination</strong>: Implements pagination for navigating through multiple pages of data.</li>
    <li><strong>Error Handling</strong>: Displays error messages for duplicate resume uploads and other server errors.</li>
</ul>

<h2>Server Interaction</h2>

<p>The React application interacts with the backend server through the following endpoints:</p>

<ul>
    <li><strong>Upload Endpoint</strong>: Posts resume data to the backend server for storage.</li>
    <li><strong>Data Retrieval Endpoint</strong>: Retrieves paginated data from the backend server.</li>
    <li><strong>Data Deletion Endpoint</strong>: Deletes resume data from the backend server.</li>
</ul>

<h2>Setup</h2>

<p>To set up and run the React application, follow these steps:</p>

<ol>
    <li>Ensure that Node.js and npm are installed on your system.</li>
    <li>Install the required dependencies using npm:</li>
</ol>

<pre>
<code>npm install axios @chakra-ui/react</code>
</pre>

<ol start="3">
    <li>Copy the provided React component code into your project.</li>
    <li>Update the API URLs in the code to point to your backend server.</li>
    <li>Run the React application using the command:</li>
</ol>

<pre>
<code>npm start</code>
</pre>

<h2>Notes</h2>

<p>Additional notes regarding the React application:</p>

<ul>
    <li>Ensure that the backend server is running and accessible from the React application.</li>
    <li>Customize the styling and functionality of the components as needed for your application.</li>
</ul>

</body>
</html>
