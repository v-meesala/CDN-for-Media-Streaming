
# CDN for Media Streaming Project

## Overview
This project sets up a Content Delivery Network (CDN) that uses Docker, Nginx, Redis, PostgreSQL, MongoDB, Django, and Flask to stream media content efficiently.

## Installation

### Prerequisites
- Docker
- Docker Compose
- Python 3 and pip
- Nginx, Redis, PostgreSQL, MongoDB (installed using Docker)

### Setup Instructions
1. Clone the repository:
   ```
   git clone https://github.com/v-meesala/CDN-for-Media-Streamin
   ```
2. Navigate to the project directory and build the Docker images:
   ```
   cd CDN-for-Media-Streaming
   docker-compose up --build
   ```

## Configuration
Refer to `docker-compose.yml` and `nginx.conf` for service configurations.

## Running the Application
Ensure all services are up and running:
```
docker-compose up
```

## Testing
Load the application in your web browser or use a tool like Postman to send requests to your CDN network.

## Security
The project uses OAuth2 and SSL/TLS for secure data exchange and authentication.

## Contribution
Feel free to fork the repository and submit pull requests.
