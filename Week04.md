# Week 4

## Learning Activities & Resources

XAMPP Administration: Studied the Apache Friends FAQ to understand how to resolve port conflicts and manage the MySQL service through the Control Panel.  
Database Migration Techniques: Followed the Official phpMyAdmin Documentation on Exporting/Importing to move the paveyrgn.sql database from a remote server to a local instance.  
WordPress Configuration: Consulted the WordPress.org wp-config.php Codex to learn how to manually define database constants and site URLs.  
File System Structures: Researched the WordPress Directory Hierarchy to troubleshoot why a "missing stylesheet" error occurs even when the wp-content folder is present.  

https://www.apachefriends.org/faq_windows.html  
https://docs.phpmyadmin.net/en/latest/import_export.html  
https://developer.wordpress.org/themes/classic-themes/basics/template-hierarchy/  

## Estimated hours

3

## Content Insights
The biggest thing I learned this week is that a website is a conversation between a folder of PHP files and a database. Moving from the cloud to XAMPP, I had the database, but had to manually rebuild the file structure.
I got stuck on a "Stylesheet is missing" error even though I could see the files right there in my htdocs folder. It turns out WordPress is very sensitive about folder nesting. If the theme is sitting inside a sub-folder created by the Unzip process, the whole site breaks. I also learned that you can "force" the site to stay on your local computer by hard-coding the URL into the wp-config.php file.
This stops the database from trying to "call home" to CloudAccess every time I hit refresh.

## Career/Employability/Learning Insights
This week taught me that being "tech-savvy" is not about knowing where all the buttons are—it is about knowing what to do when the buttons disappear. When the CloudAccess dashboard did not have a bulk download tool, I had to stop looking for a shortcut and just handle the files manually. That kind of pivot is exactly what happens in a real job when a vendor’s tool breaks.
Looking at this from a Data Science perspective, the database import/export was a huge eye-opener. Seeing my UniTasker data as a raw .sql file made me realize that data is just a portable set of instructions. If I cannot move data cleanly from one environment to another without breaking the "handshake" between systems, the data is useless.
