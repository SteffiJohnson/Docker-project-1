Docker Project 1 – Flask Todo App

Simple Flask Todo application containerized using Docker.

Build Image:
docker build -t todo-app .

Run Container:
docker run -d -p 5000:5000 -v $(pwd):/app todo-app

Access Application:
http://localhost:5000
