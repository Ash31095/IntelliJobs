# IntelliJobs


### 1. Objective

To create an application that provides job applicants a canvas where they can track the statuses of all their job applications. It will give the user an analytical view of the status of their job applications by displaying the statistics. The applicant will have a search page where he can view all his applications regardless fo the status. The applicant can add a new job that he has applied to by filling out details such as Job position, Company name, Job location etc.
The main aim of building this application is to give them a platform where they can easily update and track their job applications during the job search process.


### 2. Domain Diagram

![Domain Diagram](DomainDiagram.png?raw=true "Page view")

### 3.Technology Used

- React
- HTML
- SCSS
- Nodejs
- Express
- JavaScript
- MongoDB Atlas

### 4. Prerequisites

- Node.js
- MongoDB
- npm
- VScode

### 5. Running application locally

- Clone the repository

```
$ git clone git@github.com:neu-mis-info6150-spring-2022/final-project-webdevs.git
```

- Navigate to `webapp` folder to run frontend

```
$ cd webapp
$ npm install
$ npm start
```

- Navigate to `server` folder to run backend

```
$ cd server
$ npm install
$ node server
```

- Add `.env` file inside server folder with below details

```
  PORT
  MONGO_URL
  JWT_ENCKEY
  JWT_EXPIRY
```


