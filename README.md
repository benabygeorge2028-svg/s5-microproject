
# Personal Portfolio Website Using Docker

## 1. Project Overview

This project is a responsive personal portfolio website developed
using HTML, CSS, and JavaScript. It presents personal information,
technical skills, projects, and contact details.

The website is containerized using Docker and served through Nginx.
It is deployed on a cloud hosting platform to make it accessible
through a public URL.

## 2. Objectives

- To design a responsive personal portfolio website.
- To learn basic web development using HTML, CSS, and JavaScript.
- To understand Docker images and containers.
- To serve a website using Nginx.
- To deploy a Docker-based application to the cloud.
- To publish and manage source code using GitHub.

## 3. Technologies Used

- HTML5
- CSS3
- JavaScript
- Docker
- Nginx
- Git and GitHub
- Render Cloud Hosting

## 4. Project Structure

ben-portfolio/
├── index.html
├── style.css
├── script.js
├── Dockerfile
├── nginx.conf
├── .dockerignore
└── README.md

## 5. Features

- Personal introduction
- About Me section
- Technical skills
- Project showcase
- Contact links
- Responsive mobile navigation
- Docker containerization
- Cloud deployment

## 6. Implementation

The website interface is created using HTML and styled with CSS.
JavaScript handles mobile navigation and the copyright year.

Nginx serves the static website files inside a Docker container.
The Dockerfile defines the base image, file copying instructions,
port, and startup command.

The source code is stored on GitHub and deployed through Render.

## 7. Local Execution

Build the image:

docker build -t ben-portfolio .

Run the container:

docker run -d --name ben-portfolio-container -p 8080:10000 ben-portfolio

Open:

http://localhost:8080

## 8. Cloud Deployment

1. Push the source code to GitHub.
2. Connect GitHub to Render.
3. Create a Docker-based Web Service.
4. Select the Free instance plan.
5. Deploy the application.
6. Test the generated public URL.

## 9. Expected Outcome

A working portfolio website accessible through a web browser
locally and through a public cloud URL.

## 10. Conclusion

This project demonstrates the development, containerization,
and cloud deployment of a static website. It provides practical
experience with frontend technologies, Docker, Nginx, GitHub,
and cloud hosting.
