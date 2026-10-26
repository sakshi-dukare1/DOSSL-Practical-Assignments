# Assignment 4: Dockerization

## Aim
To containerize the Student Task Manager web application using Docker.

## Tools and Technologies
- Docker Desktop
- Docker CLI
- Node.js
- Dockerfile
- Student Task Manager web application

## Practical Demonstration

### Screenshot 1: Project Files and Dockerfile
![Project Files and Dockerfile](Screenshot1.png)

---

### Screenshot 2: Docker Image Build
![Docker Image Build](Screenshot2.png)

---

### Screenshot 3: Docker Images
![Docker Images](Screenshot3.png)

---

### Screenshot 4: Running Docker Container
![Running Docker Container](Screenshot4.png)

---

### Screenshot 5: Application Running in Browser
![Application Running in Browser](Screenshot5.png)

## Commands Used

### Build the Docker image
```bash
docker build -t student-task-manager:v1 .
```

### List Docker images
```bash
docker images
```

### Run the container
```bash
docker run -d -p 5000:5000 --name student-task-container student-task-manager:v1
```

### List running containers
```bash
docker ps
```

## Conclusion
Docker was used to package the Student Task Manager application into an image and prepare it to run in a container.