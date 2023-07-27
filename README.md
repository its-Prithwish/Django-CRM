<h1>CRM Project using Django and MySQL</h1>
<h3> Introduction</h3>
<p>This repository contains the source code for a Customer Relationship Management (CRM) project built using Django and MySQL. The CRM system is designed to help businesses manage their interactions with current and potential customers data efficiently.</p>

<h3> Table of Contents</h3>
<li> Requirements</li>
<li>Setup</li>
<li>Usage</li>
<li>Features</li>
<li>Contributing</li>
<li>License</li>
<h3>Requirements</h3> 
To run this CRM project locally, you need the following:

<li>Python 3.x</li>
<li>Django 3.x</li>
<li>MySQL server</li>
<li>MySQL client for Python (MySQLdb)</li>

<h2>Setup</h2> 
<h3>Clone the repository to your local machine using :</h3>
gh repo clone its-Prithwish/Django-CRM<br/>

<h3>Create a virtual environment (optional but recommended):</h3>
cd dcrm</br>
python3 -m venv venv</br>
source venv/bin/activate</br>

<h2>Set up the MySQL database:</h2>

<li>Create a new MySQL database for the CRM project.</li>
<li>Open the settings.py file in the crm folder and update the database settings with your MySQL credentials.</li>
<h2>Apply the database migrations:</h2>
python manage.py migrate
<h2>Create a superuser to access the Django admin panel:</h2>
python manage.py createsuperuser

<h2>Usage</h2>
To run the CRM project locally, use the following command:</br>
python manage.py runserver</br>

</br>Visit http://localhost:8000 in your web browser to access the CRM application. You can log in using the superuser credentials created during the setup process.

<h2>Features</h2>
The CRM project comes with the following features:

<li>User authentication and authorization.</li>
<p>Users have to Login to view the database webpage. The Login page is : </p>
<img src="C:\Users\itspk\OneDrive\Desktop\crm ss\1.png">
<p>After Login a message will be displayed..</p>
![2](https://github.com/its-Prithwish/Django-CRM/assets/87355004/7416b277-7bc5-4851-81e7-fa3b8824458b)


<li>Dashboard to view key performance indicators and summaries.</li>
<li>Customer management:</li>
<li>Add customer records.</li> 
<li>View  customer records.</li> 
<li>Edit  customer records.</li> 
<li> Delete customer records.</li>
Task management:
Create and manage tasks for follow-ups, appointments, etc.

<h2>Contributing</h2>
<p>Contributions to the CRM project are welcome! If you find any bugs, have suggestions for improvements, or want to add new features, please create a pull request. Remember to follow the coding conventions and provide clear commit messages.</p>

<h2>License</h2>
This CRM project is licensed under the MIT License. Feel free to use, modify, and distribute the code as per the terms of the license.



