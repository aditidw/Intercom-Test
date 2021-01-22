# Intercom-Test

## General Info
Intercom-test is a simple application in python which prints out the names of all Intercom customers within a 100km radius distance. It uses the great-circle distance formula in it's algorithm to calculate spherical distance. 

## Technologies

Project is created with :
* Python 3.9.1
* Jupyter Notebook 6.2.0

## Setup

Firstly, clone this repo and navigate to the repo folder: 
```
$ git clone https://github.com/aditidw/Intercom-Test.git
```
Install python:
```
install python3 python3-pip
```
Now you can install Jupyter Notebook:
```
pip install notebook
```
Now on the command promt type 
```
Jupyter Notebook
```
The code can now be viewed in your browser at this URL: http://localhost:8888/notebooks/Your_Folder/Intercom_Test.ipynb
The JSON file is also stored in this file as well under the name : customers.json

## Usage

1. Reading the files and loading the data
![alt text](https://github.com/aditidw/Intercom-Test/blob/main/img/1.PNG)

2. Converting the Data into Dataframes
![alt text](https://github.com/aditidw/Intercom-Test/blob/main/img/2.PNG)

3. Converting strings into datatypes and creating new column for the 'office_location' and checking to see if the values are of the same data types or not
![alt text](https://github.com/aditidw/Intercom-Test/blob/main/img/3.PNG)

4.Now using Great Circle Distance we will calculate the distance between the Intercom Dublin office and Customers coordinates, we get,
![alt text](https://github.com/aditidw/Intercom-Test/blob/main/img/4.PNG)

5. Creating a new column after for the distance between user and the office
![alt text](https://github.com/aditidw/Intercom-Test/blob/main/img/5.PNG)

6. Finding the all the users which are within the radius of 100 km of the office and sorting them in ascending order of their User_id
![alt text](https://github.com/aditidw/Intercom-Test/blob/main/img/6.PNG)

7. Reading the solution to output.txt file
![alt text](https://github.com/aditidw/Intercom-Test/blob/main/img/7.PNG)
