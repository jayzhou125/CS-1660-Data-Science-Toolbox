# CS-1660 Data-Science-Toolbox Final Project
This Data Science ToolBox is a Web Application that uses docker to deploy each micro-services. 

Applications supported: 
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
Make sure you have docker installed. If you don't know how to install Docker,
click [Docker get-started](https://www.docker.com/get-started) and follow the guide. 


## Usage
1. Clone this repo to your local directory. 
2. `cd` in your local directory and look for a file named `docker-compose.yml`.
3. If you have docker installed, run `docker-compose up -d` in your terminal or command prompt to start the application. 
	 Docker will then look up images needed for the application. Since the images are already pushed to the docker hub, just wait till it finishes downloading the images. 
4. Once the set up is done, open your browser and go to [localhost:5000](http://127.0.0.1:5000/) to see the application. If your device does not support localhost, head to your `default-machine-ip:5000`. 
5. Click on the name of the application and it take you to a new tab where the application will be running on. For specific usage for each applicatin, head to the section named **App usage specifics** below.

## To stop
Close the tabs when you are done with them and run `docker-compose down` to close the services.

## App usage specifics
**1. Rstudio:**
> When opening Rstudio, it is going to ask you for a username and password. Just type `rstudio` for both the username and password to log in. 

**2. Spyder:**
> When opening Spyder, it will take you to a virtual machine and might take a while to load. Once it finishes loading, just look for the Syper application icon and click on it to use the application.

**3. IBM SAS:**
> On click, it will take you to the online portal where you can log in using your own username and password. 

**4. Git:**
> On click, it will take you to the a online terminal where Git is pre-installed. Git bash command should all work. Notice that the back distribution is Alpine, which is a Linux variation, so make sure you are using linux command to navigate around the terminal. 

**5. Jupyter Notebook:**
> On click, it will take you to a new notebook page, just like a normal Jupyter Notebook. 

**6. Orange:**
> On click, it will take you to a virtual environment where Orange is pre-installed. When prompted for password, just type in `orange` to get in. Then you can click on the application icon to open the application. 

**7. VS Code:**
> On click, it will take you to a online VS Code session, with a test.py preloaded. What the py file does is just printing out "Hello World" to the terminal. To quickly demo, open a terminal at the top and try run `python test.py`, and you should see Hello World in the terminal. 

**8. Apache Hadoop:**
> On click, it will take you to a virtual environment that relects the remote docker command prompt. Type `hadoop` in the command prompt to check the hadoop specifics. You can use the command prompt to access the hdfs file system. 

**9. Apache Spark:**

**10. Tableau:**
> On click, it will take you to the log in page of Tableau Online. You can log in using you own Tableau account.

**11. SonarQube & SonarScanner**

**12. Tensorflow:**
> On click, it will take you to a jupyter notebook page where tensorflow is pre-installed. And a folder named "tensorflow-tutorials" contains several example programs that utilize tensorflow. 

> Alternately, you can open a terminal by clicking `new` on the top-right corner, and then click `Termianl`, wchich will kick off a new tab where you can test tensorflow's installation. Try `pip show tensorflow` to see the version installed. Or try typing `python -c "import tensorflow as tf; print(tf.reduce_sum(tf.random.normal([1000, 1000])))"` in the terminal and it should run a very simple tenserflow program. 

**13. Markdown:**
> On click, it will take you to a markdown editor where you can edit a markdown text on the left side and see the actual view of it on the right. 


## Notes:

