# smart-invoice-version-3
Smart Invoice Version 3 Documentation

Installation Instructions:
Server minimum requirement:
1.	Your version of PHP is 5.5.9 or higher (detected 5.6.25).
2.	Your version of PHP has the mbstring extension loaded.
(For WAMP users, the intl extension is "activated" by default. But to make it work you have to go to php folder (by default) C:\wamp\bin\php\php{version}, copy all the files that looks like icu*.dll and paste them into the Apache bin directory C:\wamp\bin\apache\apache{version}\bin. Once you done please restart Apache server.)
3.	Your version of PHP has the openssl extension loaded.
4.	Your version of PHP has the intl extension loaded.
(For XAMPP users, intl extension is installed, but you need to enable extension by uncommenting the following line extension=php_intl.dll in the php.ini file. Once you uncomment the extension=php_intl.dll, then you must restart apache server using XAMPP control panel. (Note: php.ini file mostly in the following directory C:\xampp\php)
 
<div> 
<img src="https://4.bp.blogspot.com/-n34kJbxrk4Q/Wo5s2yqtPkI/AAAAAAAAIOE/E1mg5TGn1Z4iPPkVz_VjsHb_hoAR3ogqwCLcBGAs/s1600/smart-invoice-installation-requirement.png" alt="Smart Invoice Version 3 Installation Requirement"/>
</div>

Once you corrected above things, 
"	please upload and extract the zip files in your server. 
"	Create new database in MySQL, and import invoice_v3.sql file into the database.
"	Now change database credentials in the following location config/site_config.php file.
<pre>
define('BASE_PATH', 'http://localhost/smart-lite/'); 
define('DB_HOST', 'localhost');
define('DB_NAME', 'invoice_v3');
define('DB_USER','root');
define('DB_PASSWORD','');
</pre>

Now you have done all the changes in order to run application successfully, if you still have any problem let me know 

if you face difficulty, then give me call via Skype muni.a1 ... I will happy to help you.
