# How to Build the First containerized java web application

## Prerequisite

- JDK 17 or above 
- Spring Tool Suite for Eclipse
- Docker Desktop


## Getting Started


## Step 1. Clone the repository

```
git clone https://github.com/dockersamples/genie-website-java
```

## Step 2. Building docker image

```
docker build -t docker_desktop_page .
```

## Step 3. Running the docker container
```
docker run -p 8080:8080 docker_desktop_page
```

<img width="1451" alt="Screenshot 2022-08-10 at 11 41 18 PM" src="https://user-images.githubusercontent.com/111007084/183986105-d4655cb8-1954-4625-b568-9d76f063b5e5.png">
