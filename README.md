# Docker Multi-Container Setup

## Project Description
This project demonstrates a multi-container application
using Flask, PostgreSQL, Nginx and Docker Compose.

## Technologies Used
- Python Flask
- PostgreSQL
- Nginx
- Docker
- Docker Compose

## Services
1. Flask: Runs the web application.
2. PostgreSQL: Stores database information.
3. Nginx: Works as a reverse proxy.

## Project Features
- Flask REST API
- PostgreSQL database connection
- Health check endpoint
- Nginx reverse proxy
- Environment variable configuration

## API Routes
- `/` - Home page
- `/health` - Database health check

## Setup
1. Clone the repository.
2. Create a `.env` file from `.env.example`.
3. Add your database password.
4. Run `docker compose up --build`.
5. Open http://localhost:8080.

## Author
Student Project