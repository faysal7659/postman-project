# Project Title
 
 API testing using Postman and newman

 


## Installation

Install my-project with npm

1.JDK 8 Install (Link: https://www.oracle.com/java/technologies/javase/javase8-archive-downloads.html)


2.Node JS Install (Link: https://nodejs.org/en/)


3.Environment Variable Setup


4.Postman (Link: https://www.postman.com/)

5.npm install -g newman-reporter-htmlextra
    
## Deployment

To deploy this project run

1.Download the github repositories
    
    Command git clone https://github.com/faysal7659/postman-project.git

2.Open postman App

3.Go to collection and import collection from git Download

4.GO to Environment and import enviroment from git Download

5.Click main folder open menu bar then clikc collection Runner.

6.newman run “Collection Link” -e EnvironmentName.json -r cli,htmlextra


![apitest](https://user-images.githubusercontent.com/93936293/201234815-60fe8738-8efd-47b1-9ef8-96a01cd8bb6f.PNG)

