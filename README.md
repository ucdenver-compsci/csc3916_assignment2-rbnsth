# Movie API

This project is a movie API built using Express.js. It provides endpoints for retrieving, creating, updating, and deleting movies. It also includes JWT and Basic authentication for certain routes.

## Student Information

- **Name:** Robin Shrestha
- **Due Date:** Feb 24, 2024

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Node.js
- npm

### Installation

1. Clone the repository:
```bash
1. git clone https://github.com/your-username/movie-api.git
2. Install dependencies: `npm install`
```

## Usage

1. Start the server: `npm run start`
2. Access the API endpoints through http://localhost:3000 (or configured port is):

   - GET /movies: Retrieve a list of movies.
   - POST /movies: Create a new movie.
   - PUT /movies: Update a movie (requires JWT authentication).
   - DELETE /movies: Delete a movie (requires Basic authentication).

## API Documentation

### GET /movies

Retrieve a list of movies.

### POST /movies

Create a new movie.

### PUT /movies

Update a movie. Requires JWT authentication.

### DELETE /movies

Delete a movie. Requires Basic authentication.

## Authentication

- PUT /movies: Requires JWT authentication.
- DELETE /movies: Requires Basic authentication.

## Postman Enviroment: 
- Collection: CSCI3916_HW2

- Enviroment: Robin_HW2

## Postman Link
[<img src="https://run.pstmn.io/button.svg" alt="Run In Postman" style="width: 128px; height: 32px;">](https://app.getpostman.com/run-collection/32232262-5ef5173c-2663-4510-bf95-616902c386ae?action=collection%2Ffork&source=rip_markdown&collection-url=entityId%3D32232262-5ef5173c-2663-4510-bf95-616902c386ae%26entityType%3Dcollection%26workspaceId%3Dca3c3d1e-eea4-46ea-b8aa-d5044f56b4cf#?env%5BRobin_HW2%5D=W3sia2V5IjoidG9rZW4iLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJhbnkiLCJzZXNzaW9uVmFsdWUiOiJKV1QuLi4iLCJzZXNzaW9uSW5kZXgiOjB9LHsia2V5IjoiQmFzaWMiLCJ2YWx1ZSI6IlkzVmZkWE5sY2pwamRWOXlkV3hsZWc9PSIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJkZWZhdWx0Iiwic2Vzc2lvblZhbHVlIjoiWTNWZmRYTmxjanBqZFY5eWRXeGxlZz09Iiwic2Vzc2lvbkluZGV4IjoxfSx7ImtleSI6IkpXVCIsInZhbHVlIjoiSldUIGV5SmhiR2NpT2lKSVV6STFOaUlzSW5SNWNDSTZJa3BYVkNKOS5leUpwWkNJNkltVXlPR0psTXpNMllqWTNNbVZoWTJVNFptTTRNV1l6WldKbE5EYzJabVF3TkRreU9XTTJPR0VpTENKMWMyVnlibUZ0WlNJNkltUnZZM1J2Y25kb2J5SXNJbWxoZENJNk1UY3dPRFl6T1RNNE5IMC4tSk9XSTRLa1BMRlVSUDkzN0lfOGY5aHVrTXRLM25zSWpUdkRVTFdURmRFIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImRlZmF1bHQiLCJzZXNzaW9uVmFsdWUiOiJKV1QuLi4iLCJzZXNzaW9uSW5kZXgiOjJ9XQ==)