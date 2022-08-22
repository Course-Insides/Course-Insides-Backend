# Course-Insides Backend
## Introduction
This is backend for Course-Inside project written in reactive spring boot.
## Setup Locally
### Clone repository
```
git clone git@github.com:Course-Insides/Course-Insides-Backend.git
```
### Setup MongoDB
```
docker pull mongodb
docker run --name mongodb -d -p 27017:27017 mongo
```
### Build Application
```
./gradlew clean build
```
### Run Application
```
./gradlew bootRun
```
This project is created with ❤ by [Harsh3305](https://github.com/Harsh3305)