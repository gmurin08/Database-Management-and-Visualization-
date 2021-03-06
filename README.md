# Database Management and Visualization

![Screenshot](assets/CS340.gif)

## About the Project/Project Title
This Python middleware module serves as a means of connecting a database on the back end to an interface on the front end. The module utilizes the PyMongo library, which allows for easy interface between MongoDB and our chosen back-end language of Python. On the front-end, the dash framework is utilized as a versatile solution for vizualizing the data


## Motivation
The purpose of this project is to create a clean, concise, reusable module to handle database create read upate and delete operations using Python. The modular nature of this project will allow for easy adaptation to a variety of different use cases with a little bit of modification by the end user.

## Installation

Tools Required for Installation:<br>
•	MongoDB <br>
  Download Instruction:<br>
 https://docs.mongodb.com/manual/administration/install-community/ <br>
•	Python3:<br>
```sudo apt-get update && sudo apt-get install python3.6```<br>
•	Jupyter Notebook (Or your favorite Python IDE):<br>
```pip install jupyter```<br>
•	Pymongo:<br>
```pip install pymongo```



## Getting Started 

To get a local project up and running follow these steps:

1. Create a local MongoDB server by using the following command (make note of the port number): <br>
```/usr/local/bin/mongod_ctl mongo start```

2.	Login to your administrative account using the command:<br>
```mongo –authenticationDatabase “admin” -u “<your_username>” -p```
3.	Create a database, if necessary, exit mongo shell, and navigate to the project dataset’s directory. Import using the following command:<br>
```monogimport --db AAC --collection animals --type=csv --headerline --port <YOUR PORT NUMBER> --file= ./aac_shelter_outcomes.csv```
4.	In ```AnimalShelter.py```, modify the class constructor to match the port number of your MongoDB instance.
5. Open a terminal emulator and navigate to the scripts directory
6. Open jupyter notebook using the ```jupyter``` command in the directory
7. Open and run ```AACShelter.ipynb```






