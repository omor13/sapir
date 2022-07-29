# Cloud DevOps - Final Lab

## Introduction

If you're building and deploying cloud native applications and microservices, then understanding container development and orchestration is a must have skill.

In this Lab you'll learn how to use both `Docker` and `Docker Compose` to build and run containers.

In this Lab scenario you'll work with 3 containers:

* `React` (front-end)
* `Express` (Back-end)
* `Mongodb` (Database)
![image](https://user-images.githubusercontent.com/30344406/181800731-23acc432-e764-49cf-be0c-49d6d025f82e.png)

This Lab will teach you how to use use Docker Compose, a tool for defining and running multi-container Docker applications, to configure and launch the Full Stack (front-end , Back-end , db) environment.
![image](https://user-images.githubusercontent.com/30344406/181816851-d7dee2d7-8fca-4249-99cf-39450a1cacb7.png)
### Upon completion of this Lab, you will be able to:

* Use a **Dockerfile** to create a web application
* Use a **Docker Compose** file to create a multi-container setup
* Use the **docker compose** command to launch a multi-container setup
* Test and validate the container setup using the **cur**l command




## Step 1️⃣: `Login to AWS Management Console`

Firstly , login to aws console using the following credentials:

| Account ID | 777203705741 |
| ---------- | ------------ |
| Username   | analiza      |
| Password   | Analiza2022$ |

## Step 2️⃣: `Create an EC2 Instance`

Use EC2 to create a new instance with the following properties:

| Instance Name | sapir_<your-firstname>_<your_last_name> |
| ---------- | ------------ |
| AMI   |  ami-02292f97f5e004ea6 (AnalizaOS - Customized Ubuntu) |
| Type   | t2.micro |
| Region   | N.Virginia |
| Storage   | 15 GB |



```sh
apt update
```
