# CS-1660 Data-Science-Toolbox Final Project
This Data Science ToolBox is a Web Application that use docker to deploy each micro-services. 

Application supported: 
- Rstudio 
- Spyder
- IBM SAS cloud 
- Git bash
- Jupyter Notebook
- Orange
- Visual Studio Code
- Apache Hadoop
- Apache Spark
- Tableau Online
- SonarQube & SonarScanner
- Tensorflow
- Markdown

## Before starting the tool box
Make sure you have docker installed.

If you don't know how to install Docker,
click [Docker get-started](https://www.docker.com/get-started) and follow the guide. 


## Usage
1. Clone this repo to your local directory. 
2. `cd` in your local directory and look for a file named `docker-compose.yml`
3. If you have docker installed, run `docker-compose up -d` to have the application running. 
	 Docker will then look up images needed for the application, since the images are already push to the docker hub, just wait till it finishes downloading the 	
	 images. 
4. Once the set up is done. Open your browser and go to [localhost:5000](http://127.0.0.1:5000/) to see the application. If your device does not support localhost, head to your `default-machine-ip:5000`. 
5. Click on the name of the application and it take you to a new tab which the application will be run on. For specific usage for each applicatin, head to section named **App usage specifics** below.

## To stop
Close the tabs when you are done with them and run `docker-compose down` to close the services.

