# Week 4

## Learning Activities & Resources

- XAMPP Administration: Studied the Apache Friends FAQ to understand how to resolve port conflicts and manage the MySQL service through the Control Panel.  
- Database Migration Techniques: Followed the Official phpMyAdmin Documentation on Exporting/Importing to move the paveyrgn.sql database from a remote server to a local instance.  
- WordPress Configuration: Consulted the WordPress.org wp-config.php Codex to learn how to manually define database constants and site URLs.  
- File System Structures: Researched the WordPress Directory Hierarchy to troubleshoot why a "missing stylesheet" error occurs even when the wp-content folder is present.  

https://www.apachefriends.org/faq_windows.html  
https://docs.phpmyadmin.net/en/latest/import_export.html  
https://developer.wordpress.org/themes/classic-themes/basics/template-hierarchy/  

## Estimated hours
3

## Content Insights
The most important thing I learned this week is that a website is just a conversation between a folder of PHP files and a database. When I moved from the cloud to XAMPP, I had all the data, but I had to manually rebuild the file structure myself.  
I got stuck on an error that said the stylesheet was missing, even though I could see the files in my folder. It turns out WordPress is very picky about how folders are set up. If the theme is buried inside an extra folder created when unzipping the files, the whole site breaks. I also learned how to keep the site on my local computer by typing the URL directly into the config file.  
Doing this stops the database from trying to connect back to the old cloud server every time I refresh the page.  

## Career/Employability/Learning Insights
This week taught me that being tech-savvy is not about knowing where all the buttons are—it is about knowing what to do when the buttons disappear. When the CloudAccess dashboard did not have a bulk download tool, I had to stop looking for a shortcut and just handle the files manually. That kind of pivot is exactly what happens in a real job when a vendor’s tool breaks.  
Looking at this from a Data Science perspective, the database import/export was a huge eye-opener. Seeing my UniTasker data as a raw .sql file made me realize that data is just a portable set of instructions. If I cannot move data cleanly from one environment to another without breaking the "handshake" between systems, the data is useless.
