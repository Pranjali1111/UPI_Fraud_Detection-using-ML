# UPI Fraud Detection Using Machine Learning
This project aims to detect fraudulent transactions in UPI systems using machine learning algorithms such as Random Forest, Naive Bayes, Decision Tree, Logistic Regression, and Linear Regression. The system analyzes transaction patterns and user behavior to classify whether a receiver is fraudulent or not. If fraud is detected, an alert is triggered with an explanation. The frontend is built using HTML, CSS, Bootstrap, and JavaScript, while the backend is powered by Django with SQLite3 as the database.

### Basic Features of The App
    
* Register – Users can register and create a new profile
* Login - Registered users can login using username and password
* User Profile - Once logged in, users can create and update additional information such as avatar and bio in the profile page
* Update Profile – Users can update their information such as username, email, password, avatar and bio
* Remember me – Cookie Option, users don’t have to provide credentials every time they hit the site
* Forgot Password – Users can easily retrieve their password if they forget it

![Screenshot (441)](https://github.com/user-attachments/assets/00bba8ed-96cf-4d2a-a4cf-a9c7a842ae47)
![Screenshot (448)](https://github.com/user-attachments/assets/0d00649f-9d48-4f9c-8368-4463ed04f570)
![Screenshot (449)](https://github.com/user-attachments/assets/e6192bfa-135b-4655-9613-8c98e2fb2401)
![Screenshot (450)](https://github.com/user-attachments/assets/6cf622d6-512b-4c5c-83dc-1462c27ab58f)
![Screenshot (451)](https://github.com/user-attachments/assets/cc7ff7de-1f8f-445e-b827-02c912390f0c)



## Tutorial
[Here](https://dev.to/earthcomfy/series/14274) is a tutorial on how to build this project.

### Quick Start
To get this project up and running locally on your computer follow the following steps.
1. Set up a python virtual environment
2. Run the following commands
```
$ pip install -r requirements.txt
$ python manage.py migrate
$ python manage.py createsuperuser
$ python manage.py runserver
```
   
3. Open a browser and go to http://localhost:8000/

