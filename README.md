# Dockerized Node.js App

A simple Dockerized Node.js application built with Express.js.

## Features

- Node.js backend server
- Express.js framework
- Docker containerization
- Runs on port 3000

## Technologies Used

- Node.js
- Express.js
- Docker / Podman
- Linux (Fedora)

## How to Run Locally

Install dependencies:

```bash
npm install
```

Start server:

```bash
node app.js
```

Open browser:

```text
http://localhost:3000
```

## Run with Docker

Build image:

```bash
docker build -t dockerized-nodejs-app .
```

Run container:

```bash
docker run -p 3000:3000 dockerized-nodejs-app
```

## Author

Rabiya Pathan
