# Karan's Photography Portfolio

## Overview
A multi-page photography portfolio built with HTML and CSS, containerized with Docker, and served using Nginx. This project is designed as the foundation for a larger personal platform that will expand to showcase additional creative and technical work.

## Features
- Multi-page layout: Home, Gallery, and About
- Styled photography portfolio interface
- Dockerized for consistent local development
- Served with Nginx

## Tech Stack
- HTML5
- CSS3
- Docker
- Nginx

## How to Run
1. Clone the repository
2. Build the Docker image:
   docker build -t my-portfolio .
3. Run the container:
   docker run -p 8080:80 my-portfolio
4. Open in browser:
   http://localhost:8080

## Project Structure
- `site/` contains the HTML, CSS, images, and JS files
- `nginx/` contains the Nginx configuration
- `Dockerfile` defines the container setup

## Future Improvements
- Improve mobile responsiveness
- Add more photography collections
- Add CI/CD pipeline
- Deploy to AWS
