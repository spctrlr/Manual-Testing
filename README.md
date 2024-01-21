# Manual testing project 


## Summary
OpenCart is an online store management system developed by Hong Kong-based OpenCart Limited. It is PHP-based, using a MySQLi (MySQL, MariaDB, Percona Server) or PostgreSQL database and HTML components.[2] Support is provided for different languages and currencies. It is freely available under the GNU General Public License. More at [Wikipedia](https://en.wikipedia.org/wiki/OpenCart) or [OpenCart](https://www.opencart.com/).

The repo contains two folders and the tested OpenCart version. _Linux_ folder contains ***.odt*** format and _Windows_ folder ***.xlsx*** format.<br>
I don't own any responsibility how ***.xlsx*** files will be  displayed, there is possibility they will not be as functional as ***.odt*** ones.<br>
Each folder contains _FRS_, _TestPlan_, _Test Scenarious_, _Test Cases_, _Test Case Results_ and _Bug Report_.<br>

Tests and test environment are created under linux at the time of testing.


## Requirements
Since the project is not going to be uploaded, we need to install the following:<br>
* PHP 5.4**<br>
* Database (MySQL suggested)**<br>
* Web Server (Apache suggested)**<br>


## Install and configure

In order to set up our own environment we are going to insall XAMPP. Go to [XAMPP](https://www.apachefriends.org) page and download appropriate version for your operating system.
1. For windows<br>
  1. Run the installer and follow the instructions.

- For Linux<br>
  1. Change installer permissions<br>
    `chmod 755 xampp-linux-*-installer.run`<br>
  2. Run the installer<br>
    `sudo ./xampp-linux-*-installer.run`<br>
  3. Start XAMPP<br>
    `sudo /opt/lampp/lampp start`<br>
  4. Stop XAMPP<br>
    `sudo /opt/lampp/lampp stop`<br>
  5. Check if its installed/started correct:<br>
    `firefox https://localhost`<br>
