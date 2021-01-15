### Applications needed to run the project ###
1) XAMPP Server which includes MYSQL Server as well
2) Any code editor(VS Code)



### How To Run this Project ###
To run this project, you must have installed a virtual server i.e. XAMPP on your pc. 
Put the blood bank source code into C://xampp/htdocs/BloodBankManagement
1)Create folder in C:/xampp/htdocs/ as "BloodBankManagement"
 Put the downloaded code into C:/xampp/htdocs/BloodBankManagement
2)How to Run this Project:
To run this project, you must have installed a virtual server i.e. XAMPP on your pc. 
Put the blood bank is in PHP source code into C://xampp/htdocs/
	1)Start the XAMPP server first
	2)Open browser and go to URL http://localhost/phpmyadmin
	3)Then click on databases tab
4)Import the whole database already existed in the project folder "sql/bloodbank.sql"
	5)Dummy credentials are created for testing purpose
		These are dummy credential already exists in database
			1) Hospitals(admin)
			please Login credentials already existed in database:
			email: hospital1@gmail.com
			passwd: hospital1

			email: hospital2@gmail.com
			passwd: hospital2
			2) Blood Receivers(users)
			email: battu@gmail.com
			passwd: battu

			email: vamsi@gmail.com
			passwd: vamsi
6)To open the website locally "http://127.0.0.1/BloodBankManagement/index.php"
7)If anyone wants to create own credentials that also can be done using "Registration" option 
based on type of user you are. In this Application 2 roles are there in this project. 
	(i). Hospital-Admin
    	(ii). Receiver
8)After the Registration you have accesses in the application based on, he/she Role.
This application is implemented based RBAC Policy (Role Based Access Control System).


### Other specification about dependent applications ###
If anyone wants to create own profile in this application see "Registration" and do necessaries.
That person details are reflected to the database tables in the backend.
