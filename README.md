# OBBS-demo

---------------------------------------------RoyalBanquett-------------------------------------------------
<br>
Step 1: Install XAMPP and PostgreSQL<br>

Before enabling PostgreSQL extensions in PHP, you need to install XAMPP and PostgreSQL on your system.<br>

1. Install XAMPP<br>
--> Download XAMPP from the official website: https://www.apachefriends.org<br>
--> Run the installer and follow the on-screen instructions to install XAMPP.<br>
--> Once installed, open the XAMPP Control Panel and start Apache and PHP services.<br>

2. Install PostgreSQL<br>

--> Download PostgreSQL from the official website: https://www.postgresql.org/download/<br>
--> Run the installer and complete the installation process.<br>

During installation, you will be asked to set a password for the PostgreSQL superuser (postgres)—remember this password.<br>
After installation, open SQL Shell(psql) to manage your databases.<br>

------------------------------------------****************************-------------------------------------------

Step 2: Enable PostgreSQL Extensions in PHP<br>
--> XAMPP does not include PostgreSQL (pgsql) extensions by default, so you need to enable them manually.<br>
--> Enable pgsql and pdo_pgsql Extensions<br>
--> open the php.ini file located in your XAMPP installation folder (e.g., C:\xampp\php\php.ini).<br>
--> Open the file in a text editor.<br>
--> Find the following lines and remove the ; at the beginning to enable them:<br>

extension=pgsql<br>
extension=pdo_pgsql<br>

--> Save the file and restart Apache from the XAMPP Control Panel to apply the changes.<br>

---------------------------------*******************************------------------------------------------

Step 3: Copy Source Code to the htdocs Folder<br>
After installing XAMPP and PostgreSQL and enabling the necessary extensions, follow these steps:<br>

--> Extract the downloaded project zip file.<br>
--> Locate the source code folder (e.g., RoyalBanquett).<br>
--> Copy the entire folder.<br>
--> Paste it into the htdocs directory of your XAMPP installation.<br>
--> Default path: C:\xampp\htdocs\<br>
--> Ensure all project files are correctly placed inside htdocs to be accessible via the browser.<br>

---------------------------------*******************************------------------------------------------

Step 4: Import the SQL File into PostgreSQL<br>
After copying the source code to the htdocs folder, you need to set up the database in PostgreSQL. Follow these steps:<br>

1. Open the PostgreSQL SQL Shell (psql)<br>

--> Search for SQL Shell (psql) in the Start menu and open it.<br>
--> Enter the following details when prompted:<br>
--> Server: Press Enter (default: localhost)<br>
--> Database: Create a database with name royaldb<br>
--> Port: Press Enter (default: 5432)<br>
--> Username: Enter your PostgreSQL username (default: postgres)<br>
--> Password: Enter the password you set during installation<br>

Import the SQL File<br>
Locate the roayalbanquet.sql file inside the SQL folder of the extracted project.<br>

--> Open the SQL Shell (psql)<br>
--> Open the royalbanquet file and copy all the content<br>
--> past inside Sql shell and hit enter<br>

---------------------------------------*******************************------------------------------


Step 5: Run the Project<br>
After setting up the database, follow these steps to run the Royalbanquett Management System:<br>

Start XAMPP Services<br>

--> Open the XAMPP Control Panel.<br>
--> Start Apache to enable the PHP server.<br>
--> Ensure PostgreSQL is Running<br>
--> Open pgAdmin or SQL Shell (psql) and verify that the PostgreSQL server is running.<br>

Open the Project in a Browser<br>
Open your web browser and enter the following URL:<br>
--> http://localhost/RoyalBanquett<br>
--> Replace RoyalBanquett with your actual project folder name if it's different.<br>

----------------------******************************----------------------------------

Admin Credential<br>
Username: admin<br>
Password: Test@123<br>

User Credential<br>
Username: anvi@gmail.com<br>
Password: Anvi@123<br>
Or Register a new user.<br>
