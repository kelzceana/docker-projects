#  Amazon prime video Dockerized App

This project is a Node.js application packaged with Docker using a minimal Alpine base image (`node:20-alpine`). It exposes port `3000` and starts the app with `npm start`.

---

##  Docker Setup

###  Project Structure

Your Dockerfile should be located at the root of your project, alongside your `package.json` and application source code.

##  Build the Docker Image
To build the Docker image from the repository:

```bash
docker build -t my-node-app .
```

Run the container and map port 3000:

```bash
docker run -p 3000:3000 my-node-app
```
