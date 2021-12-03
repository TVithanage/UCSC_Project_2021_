# UCSC_Project_2021_
Related URL:https://github.com/TVithanage/UCSC_Project_2021_.git

It is provided project in two different repositories as RMS_BackendProject_2021 and RMS_FrontendProject_2021. Frontend project contains all the pages which are interact with the users. Then backend project contains all the backend processes related .ts files and other related files.

### RMA_FrontendProject_2021
Related URL:
RMS_FrontendProject_2021:https://github.com/TVithanage/RMA_FrontendProject_2021.git
### RMS_BackendProject_2021
Related URL:
RMS_BackendProject_2021:https://github.com/TVithanage/RMS_BackendProject_2021.git


## Table of contents
* [General info]
* [Technologies]
* [Setup]
* [Features]

## General info
* Recruitment Management System (RMS) is a simple application which is used to manage day to day recruitment processes. 
* This project contains a general login at the initial run. User credentials for logging is:
Username: admin
Password: admin
* Then it directs to the admin dashboard portal and it contains all the modules contain.
* User: Provides the all user details
* Previleges: This allows to user previlege management
* Role: This allows to add roles to the system
* Job Vacancy: This allows to add job vacancies and through this registered users are able to apply it if they are approved to apply for the specific job. Through the Job Category,Department links; it is possible to add related departments and Job categories.
* Candidate Profile: Thia allows to add new candidates with their personal details.
* Reports: This is provided reports which are related to the candidate progress.
* It is provided userfriendly interfaces and error handling messages to guide users easily.
	
## Technologies
Project is created with:
* Windows 10 OS and it is compatible with all windows 7 and higher versions
* Perfectly run on Visual Studio Code
* MySQL Server - 8.0
* ExpressJs 4.17
* TypeORM
* Boostrap latest version 3/5
* Node.js 12.0
* Chart.js library
* jQuerry library
* NPM 
* Google chrome and Fire fox for launch the project.
	
## Setup
First use the RMS_BackendProject_2021 as the backend project. Then start the local sql server. And then use the below commands to run project initially.

Then add the DB file provieded as recruitment_management SQL Text file to the local SQL server. After that run below codes to run the project.

```
$ cd ../RecruitmentManagement/Backend
$ ng serve
```
Then it provides the local url that project is runnig:
http://localhost:3000 as default. 

To run this RMA_FrontendProject_2021, install it locally using npm:

```
$ cd ../RecruitmentManagement/Frontend
$ npm install
$ npm start
```
## Features
* Allows to post job advertisements
* Allows to apply through web
* Allows to schedule interviews
* Allows to identify candidate performances
* Modern userfriendly UIs
