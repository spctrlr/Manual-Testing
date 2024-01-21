# Manual testing project 


## Project Overview
Welcome to the OpenCart manual testing project! OpenCart is an online store management system developed by OpenCart Limited. This project aims to ensure the reliability and functionality of OpenCart through comprehensive manual testing. The repository includes two folders for Linux and Windows, each containing essential documents such as Functional Requirements Specification (FRS), Test Plan, Test Scenarios, Test Cases, Test Case Results, and Bug Report. The testing environment was set up and executed on a Linux system.


## System Requirements
Before diving into testing, make sure to have the following components installed:<br>

* PHP 5.4<br>
* Database (MySQL suggested)<br>
* Web Server (Apache suggested)<br>


## Installation and Configuration

In order to set up our own environment we are going to insall XAMPP. Go to [XAMPP](https://www.apachefriends.org) page and download appropriate version for your operating system.<br>

### For windows<br>
   1. Download XAMPP from XAMPP, run the installer, and follow the on-screen instructions.<br>
   2. Continue with Section 2 of the Linux guide.



### For Linux<br>

1. Change installer permissions<br>
 `chmod 755 xampp-linux-*-installer.run`<br>
 
   1.2 Run the installer<br>
    `sudo ./xampp-linux-*-installer.run`<br>
  
   1.3 Start XAMPP<br>
    `sudo /opt/lampp/lampp start`<br>
  
   1.4 Stop XAMPP<br>
    `sudo /opt/lampp/lampp stop`<br>
  
   1.5 Verify installation by checking:<br>
    `firefox https://localhost`<br>

2. Extract opencart-4.0.2.1.zip, move it to the XAMPP htdocs directory:<br>
  `sudo mv opencart-4.0.2.1 /opt/lampp/htdocs/`<br>
  
   2.1 Grant user permisions to read & write /htdocs directory<br>
	`sudo chmod -R 777 /opt/lampp/htdocs`<br>
  
   2.2 Change `config-dist.php` to `config.php` in `/opt/lampp/htdocs/opencart/upload/` and `/opt/lampp/htdocs/opencart/upload/admin/`.
  
   2.3 Create a database _'opencart'_ in _https://localhost/phpmyadmin/_ and set the _'Collation'_ from the drop-down menu next to the database name.<br>
  
   2.4 Establish a connection between the application and the database by navigating to _https://localhost/opencart/_, clicking on the _/upload_ folder, and following the instructions.
