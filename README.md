# Bookstore

#### Epicodus Drupal Week 1 Independent Project - Site Building with the Drupal Interface

#### _By Maggie Harrington_
##### _4-21-17_


## Description

##### _A sample small business website for a bookstore written in Drupal_.

##### Project Objectives:

* Create an "About" page and a "Locations" page.
* Create a "Book Review" custom content type. Name the fields correctly and place in the correct order.
* Create a Contact form with a "Contact" link in the main menu.
* Set the 4 "Book Review" fields to required. The rating field must use either radio buttons or a menu.
* Create a "New Books" view and display it as a block.
* Create a feature for the "Book Review" content type and the "New Books" view.
* Create a "Reviewer" role and assign it the correct permissions.
* Create a coupon block on the front page and make it only visible to authenticated users.
* Create a "Site Configuration" feature tracking the specified Strongarm variables. Make changes and then recreate your "Site Configuration" feature.
* Export your database at the end of your project and include the .zip file in a db-backup folder within in the sites directory. Include it with your repository.

##### This project demonstrates the following skills:

* Learn basic Drupal terminology and see how the parts of a project are structured.
* Practice the steps for setting up a new Drupal project with a database.
* Learn how to use Git to track your Drupal projects and set up local development environments for ongoing projects.
* Practice site building using Drupal's browser interface.
* Learn how to add and organize content on your sites using Basic Pages, Articles, Blocks and Custom Content Types.
* Learn to change the look and feel of your site by configuring themes.
* Start using both Core and Contrib modules.
* Start using the Features module to keep your configuration settings in code.


## Setup/Installation Requirements

##### Requirements:

* MAMP (see https://www.mamp.info/en/downloads/ for installation details)


##### Clone Project:

* Open the terminal and enter `cd Desktop`

* Enter `git clone ` and copy/paste the project link: https://github.com/maggie-harrington/drupal-week1-bookstore

* Enter `cd drupal-week1-bookstore`


##### Import Database and Configure:

* In MAMP Preferences, change document root to project folder listed above. Make sure Apache Port is set to 8888 and MySQL Port is set to 8889.

* In your web browser, open phpMyAdmin: http://localhost:8888/MAMP/index.php?page=phpmyadmin&language=English

* Click the 'Import' tab, leave the default settings and make sure the character set is 'utf-8'.

* Click the 'Choose File' button next to 'Browse your computer' and navigate to sites/db-backup/bookstore.sql.zip , then click 'Go'.

* Select the 'Privileges' tab and click 'Add User', then enter 'bookstore' for both the username and password.

* Navigate to localhost:8888 in your web browser to view the project. (Make sure to keep the terminal window containing the server open while the project runs.)


## Support and contact details

If you run into any issues or have questions, ideas or concerns, please feel free to contact me at maggie.harrington@gmail.com


## Technologies Used

Written using Drupal, MAMP, Atom, and Git.

Modules used: Views, Features, Strongarm


## MIT License

Copyright (c) 2017 Maggie Harrington
