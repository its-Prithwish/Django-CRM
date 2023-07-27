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

<h4>1. User authentication and authorization.</h4>
The user have to Login to see the database website. The Login page is :

![1](https://github.com/its-Prithwish/Django-CRM/assets/87355004/fbc72083-f96b-4e8e-a6f2-6cd815b1c954)

After Login a Success message will be shown...


![2](https://github.com/its-Prithwish/Django-CRM/assets/87355004/2cd991bc-2f64-4c8b-9d08-a82002f61532)


<h4><li>2. Register new customers.</li></h4></br>

![8](https://github.com/its-Prithwish/Django-CRM/assets/87355004/20bf7462-36a7-41d6-8cab-220869807e61)


<h4>3. Dashboard to view records.</h4></br>


![5](https://github.com/its-Prithwish/Django-CRM/assets/87355004/3d7369a3-2155-45fc-97be-64b8c2289295)


<h4>4. Record management :</h4></br>
   <li>Add customer records.</li> </br>

  
  ![3](https://github.com/its-Prithwish/Django-CRM/assets/87355004/5e142bf0-43d7-4ee3-8e56-217f431e0f26)

</br>After adding a success message will be displayed...

![4](https://github.com/its-Prithwish/Django-CRM/assets/87355004/22804a14-d3d2-4f01-81fb-f46b2faee3d0)



   
   <li>View individual customer records.</li> </br>

![6](https://github.com/its-Prithwish/Django-CRM/assets/87355004/06f00fb2-9dfc-4ff9-863f-b925907f715a)

   
   <li>Update customer records.</li> </br>


![7](https://github.com/its-Prithwish/Django-CRM/assets/87355004/0b006dfb-b4aa-4efa-960f-58167401471e)


     
 
   <li>Delete customer records.</li></br>
   <p>We can also delete customer records individually. This gives us a extra layer of reliability to maintain the database. No one but authorized users only will be able to delete customers records from the database table. </p>
    

<h2>Contributing</h2>
<p>Contributions to the CRM project are welcome! If you find any bugs, have suggestions for improvements, or want to add new features, please create a pull request. Remember to follow the coding conventions and provide clear commit messages.</p>

<h2>License</h2>
This CRM project is licensed under the MIT License. Feel free to use, modify, and distribute the code as per the terms of the license.
</br>


