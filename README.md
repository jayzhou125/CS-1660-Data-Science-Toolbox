# CS-1660 Data-Science-Toolbox Final Project
This Data Science ToolBox is a Web Application that use docker to deploy each micro-services. 
Application supported:
	1. Rstudio
	2. Spyder
	3. IBM SAS cloud 
	4. Git bash
	5. Jupyter Notebook
	6. Orange
	7. Visual Studio Code
	8. Apache Hadoop
	9. Apache Spark
	10. Tableau Online
	11. SonarQube & SonarScanner
	12. Tensorflow
	13. Markdown

## Before starting the tool box
Make sure you have docker installed.
Click this link and follow the guide: [Docker get-started](https://www.docker.com/get-started)

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

