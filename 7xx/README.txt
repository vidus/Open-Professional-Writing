-----------------------------------------------------
Open Professional Writing Installation Instructions
-----------------------------------------------------

----------------------------
Method 1: Database Import
----------------------------
1. Copy the contents open-pw folder into your web directory.  If using apache, it should be yoursite.com/public_html/(contents_of_folder)

 2.Create a database using mysql or mariadb, and a user with full privileges on that database.  

 3.Next, import the provided mysql database into your newly created database.

 4.Edit the settings.php file located in the openpw folder at /sites/default/settings.php.  You should edit the  database, database user, and password fields to correspond to the database you've created.

 5.Navigate to your URL.  Login with the username admin and the password tester55.  You should now find yourself at the front page of the Open Professional Writing Base base site.

--------------------------------
Method 2: Backup and Migrate
--------------------------------
 1.Copy the contents open-pw folder into your web directory.  If using apache, it should be yoursite.com/public_html/(contents_of_folder).  Once copied, delete the settings.php file located at /sites/default/settings.php.  Then, copy default.settings.php and rename the new copy settings.php.  This creates a new and unedited copy of the settings file.

 2.Create a database using mysql or mariadb, and a user with full privileges on that database.

 3.Navigate to your site's url, entering in the database name, username, and password when prompted.  

 4.Once install has completed, enable the Backup and Migrate module. 

 5.Next, go to Configuration, and then Backup and Migrate.  Use the Restore function to import the provided openpw database into your site.  When the process is finished, your site should be changed to the official Open Professional Writing base site.  Your username and password will be changed to UN: admin PW: tester55



