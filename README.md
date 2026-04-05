Docker Project 1 – Flask Todo App

Simple Flask Todo application containerized using Docker.

Build Image:
docker build -t 1stapp .

Run Container:
docker run -d -p 5000:5000 -v $(pwd):/app 1stapp

Access Application:
http://localhost:5000

