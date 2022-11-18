# CMPG-323-Overview-32494122
This is a repository for CMPG 323 Projects.

###### Git Ignore
The .gitignore is used to ignore certain files that should not be available for access. Its objective is to ignore those specific files when the project is loaded onto github. 
###### Repositories
Each project is expected to have its own repository. There are 5 projects in total. Project one has been added under the repository "CMPG-323-Overview". The other remaining repositories for the projects may simply be linked to this main repository. 
###### Diagram
The diagram below basically illustrates how CMPG-323-Overview is the main repository which will consist of all 5 projects. Each project will then have its own specific repository created, of which the repository will then be linked to that specific project. Basically, you can access all the different projects through the overview, or you can access each individual project through its own repository.

--

![Screenshot 2022-08-17 185537](https://user-images.githubusercontent.com/110536628/185200246-157d4203-5a1e-419c-81cf-f0cd610c9236.png)


###### Storage Of Credentials
Credentials will be managed by using the gitignore setup. The objective is that those files are to be ignored as they contain sensitive information such as log in details, which should be kept private. 
###### Branching Strategy
In each project, different branches namely, main, develop, feature, hotfix and release will be created. The idea with this is that the work done on a project can be seperated or isolated into a specific branch, for example the main branch can include all the work from other branches, and the hotfix branch will include fixes or edits that have been completed.

# Project 2
This repository consists of project 2.

### Project 2 Description
Project 2 is based on cloud computing. An API project was created on Visual Studio 2019 using .Net framework tools, and swagger end points.
<br />The project basically links a database to a website where a client would want to perform REST(Create, Update, Delete, Retrieve) operations. 
This project also consists of a database, of which a connection string is used for connection. 

# Project 3 

### This project is a WebApp built on Microsoft Visual Studios.

### Description

Project 3 is a WebApp built on Microsoft Visual Studios. The WebApp makes use of a cloud database to store data that is entered by a user. A user can manipulate the data on the website using the different functionalities that are provided. Some of these functionalities are the standard CRUD operations. CRUD is basically an acronym which basically describes the four basic operations a program should be able to perform. In this WebApp, A repository pattern is used as implementation for the different functionalities.

### Repository Pattern 
A repository is basically a design pattern which is integrated as an additional layer between the WebApp and the database. The diagram below provides an overview of what this pattern is. 

![1_bsnRfIYmDDLxHyYPkXzUzA](https://user-images.githubusercontent.com/110536628/193019033-27bf8461-ba27-4acb-bf9b-cc0fe3554cf1.png)

{link to website} https://blog.devgenius.io/building-a-powerful-and-generic-repository-in-net-667edea193f6

The link provided above also provides information about what a repository pattern and how they are implemented in todays technology world. 


##### CRUD Operations
###### * CREATE
###### * READ
###### * UPDATE
###### * DELETE 
{See link to read more about CRUD operations} https://www.freecodecamp.org/news/crud-operations-explained/

# Project4
This project is based on UIPath implementation whereby functionalities are created on UiPath orchestrator. These functionalities basically implement CRUD operations on a web application. 

#### Brief
The project contains different workflows and an excel document. Uipath reads data of the excel document and prints the data on the web application. 
The first workflow is "TestZones"
The second workflow is "TestCategories"
The third workflow is "TestDevices" 

### How does it work?
The functions in UIPATH operate to read data from the excel document, and the data gets stored in a datatable on UIPATh. The data is the transferred to the web application through a series of different functions. Once the data is on the web app, UIPath runs more functions to test whether the data has been successfully created and read on the web appplication. 

##### Requirements:
###### * UIPath Automation
###### * GIT
###### * Github
###### * Browser(preferably Chrome)
