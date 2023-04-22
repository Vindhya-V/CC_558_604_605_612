# CC_558_604_605_612

## ToDo-List 

This WebApp is developed using Flask and MongoDB. We have connected Flask to MongoDB using Pymongo. Dockerfile is used to create docker images and docker containers.


## Built Using the following

	Flask : Python Based mini-Webframework
	MongoDB : Database Server
	Pymongo : Database Connector ( For creating connection between MongoDB and Flask )
	HTML5 : For Form and Table


## Run the application using the following Commands

Make sure that Docker Desktop is up and running. To run the following commands, make sure that you are inside the project directory, where `docker-compose.yaml` file is present.

```
Create a container called test-mongodb using the following command
    $ docker run -d -p 27017:27017 --name test-mongodb mongo:latest
    
    
Install the necessary requirements
    $ pip install -r requirements.txt
    
  
Run app.py using Python
    $ python app.py
    

Go to http://localhost:5000 with any of the browsers
    $ open http://localhost:5000
```
