# instagram-clone
## Description
A clone of instagram that resembles the functionalities of instagram such us signing up and logging in, uploading photos,like and comment on posts, and follow other users
## Screenshots 
###### Home page
 ![Screenshot from 2022-06-07 13-39-40](https://user-images.githubusercontent.com/99794154/172368730-82c8487a-136d-48dd-bc13-fa8b227e58f2.png)

 ###### Signup
 ![Screenshot from 2022-06-07 11-16-46](https://user-images.githubusercontent.com/99794154/172368888-237bba77-8ca6-411c-86e3-e98bb77fc96d.png)
 ###### User Profile
 ![Screenshot from 2022-06-07 14-31-52](https://user-images.githubusercontent.com/99794154/172369368-89ed4692-fc1e-4823-b831-d81fcae42350.png)
 ![Screenshot from 2022-06-07 14-31-43](https://user-images.githubusercontent.com/99794154/172369481-8fc6560d-f0dd-4f1f-bf02-a78fe97edfe2.png)
 ![Screenshot from 2022-06-07 14-33-26](https://user-images.githubusercontent.com/99794154/172369615-6475d43e-cebc-413a-a9ea-4e8cb625a2dd.png)
## User Story  
  
* Sign in to the application to start using.  
* Upload a pictures to the application. 
* Search for different users using their usernames.  
* See your profile with all your pictures.  
* Follow other users and see their pictures on my timeline.  
  

  
## Setup and Installation  
To get the project .......  
  
##### Cloning the repository:  
 ```bash 
 https://github.com/sandrakinoti16/instagram-clone 
```
##### Navigate into the folder and install requirements  
 ```bash 
cd ig pip install -r requirements.txt 
```
##### Install and activate Virtual  
 ```bash 
- python3 -m venv virtual - source virtual/bin/activate  
```  
##### Install Dependencies  
 ```bash 
 pip install -r requirements.txt 
```  
 ##### Setup Database  
  SetUp your database User,Password, Host then make migrate  
 ```bash 
python manage.py makemigrations instagram
 ``` 
 Now Migrate  
 ```bash 
 python manage.py migrate 
```
##### Run the application  
 ```bash 
 python manage.py runserver 
``` 
##### Running the application  
 ```bash 
 python manage.py server 
```
##### Testing the application  
 ```bash 
 python manage.py test 
```
Open the application on your browser `127.0.0.1:8000`.  
  
  
## Technology used  
  
* [Python3.6](https://www.python.org/)  
* [Django 1.11](https://docs.djangoproject.com/en/2.2/)  
* [Heroku](https://heroku.com)  
  
  
## Known Bugs  
* There are no known bugs currently but if you spot any, email me with the email in the contact information below  
  
## Contact Information   
If you have any question or contributions, please email me at [sandrakinya6@gmail.com]  
  
## License 

* *MIT License:*
* Copyright (c) 2022 **Sandra Kinoti**
