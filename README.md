# Short URL Project

Welcome to the Short URL Project repository! This project is built using Node.js, Express.js, and MongoDB, allowing users to shorten their URLs. This readme file provides an overview of the project and explains how to set it up and use it.


## Blog Post

Before talking about the project, I would like to share with you the link to a blog that I wrote explaining this project of mine.

 1. **Project Overview**: The blog post provides a comprehensive overview of the short URL project, discussing its purpose and benefits.

2. **Technical Implementation**: It delves into the technical aspects of the project, explaining how Node.js, Express.js, and MongoDB are used to build the URL shortening functionality.

3. **API Documentation**: The blog post includes detailed documentation of the project's API endpoints, explaining how to interact with the API for URL shortening and retrieving analytics.

You can find the blog post [here](https://nikk.hashnode.dev/building-a-short-url-project) 🌏.


## Features
- Shorten long URLs into compact, easy-to-share short URLs.
- Redirect users to the original URL when they visit the short URL.
- Track the number of clicks on each short URL.
- Provides a simple and user-friendly API for shortening URLs.

## Prerequisites
To run this project locally, you'll need the following software installed on your machine:
- Node.js (v14 or higher)
- npm (Node Package Manager)
- MongoDB (Make sure the MongoDB service is running)

## Installation
1. Clone this repository to your local machine.
git clone <repository_url>


2. Change into the project's directory.

3. Install the dependencies.


## Usage
1. Start the server by running the following command:
npm start

2. The server should now be running on the specified port (default: 3000).

3. Open your web browser and visit `http://localhost:3000` (or the appropriate base URL if you configured it differently).

4. You can now begin shortening URLs by entering them in the provided input field and clicking the "Shorten" button.

5. The shortened URL will be displayed below the input field. You can copy and share this URL with others.

6. When users visit the shortened URL, they will be redirected to the original long URL.

7. To view the analytics (number of clicks) for a shortened URL, append a `+` symbol to the end of the URL. For example, `http://localhost:3000/abc+`.

## API Endpoints
The project also provides API endpoints for programmatic access to URL shortening functionality.

- `POST /api/shorten`: Shorten a URL. Send a JSON payload in the request body with the `url` property containing the long URL to be shortened.

- `GET /:code`: Redirect to the original long URL associated with the specified short code.

- `GET /api/:code/stats`: Get the analytics (number of clicks) for a shortened URL.

For detailed information about these endpoints, refer to the API documentation or use tools like Postman to explore the endpoints.


Feel free to check it out to gain a deeper understanding of the project!
