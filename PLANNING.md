## Bookstore: Planning
###### Epicodus Drupal Week 1 Independent Project - Site Building with the Drupal Interface

### Project Setup

* Download Drupal 7 core zip at https://www.drupal.org/project/drupal/releases/7.54

* Unzip and move to Desktop, rename project folder

* From within project folder:
`cp sites/default/default.settings.php sites/default/settings.php`
`chmod -R a+w sites/default`

###### MAMP:

* Change document root to project folder, Apache Port: '8888' and MySQL Port: '8889', 'start servers'

###### phpMyAdmin:

* 'Databases' > 'Create database' (database name: 'bookstore'; collation: 'utf8_general_ci') > 'Create'

* 'Privileges' > 'Add user' (username: 'bookstore'; password: 'bookstore'; host: select 'local') > 'Go'

###### Drupal Web Interface:

* localhost:8888/install.php

* 'Select an installation profile' (Standard') > 'Save and Continue'

* 'Choose language' ('English') > 'Save and Continue'

* 'Database configuration' (Database configuration: 'MySQL, MariaDB, or equivalent'; Database name: bookstore; username: 'bookstore': password: 'bookstore') > 'Advanced Options' (Database host: '127.0.0.1'; Database port: '8889') > 'Save and Continue'

* 'Configure Site' (Site name: 'Bookstore'; e-mail: 'maggie.harrington@gmail.com') > 'Site Maintenance Account' (username: 'bookstore'; password: 'bookstore') > 'Server Settings' (Default country; Default time zone) > 'Save and Continue'


### Project Stages:
* Create an 'About' page and a 'Locations' page.
* Enable 'Contact' module, create a 'Contact' form with a 'Contact' link in main menu.
    (Set permissions to all users.)
* Install Views and Chaos Tools modules.
* Install Features module.
* Install Strongarm module.
* Create 'Site Configuration' feature tracking site_name, site_slogan, theme_default and site_frontpage.
    (Generate in modules directory, enable in Features management page, commit with repository.)
* Change default theme, name and slogan, set 'About' page to front page.
* Recreate 'Site Configuration' feature.
    (Generate in modules directory, enable in Features management page, commit with repository.)
* Create 'Book Review' custom content type with fields: 'Book Title', 'Book Author', 'Rating', and 'Review Body'.
    (Set all 'Book Review' fields to required and in order given above. The 'Rating' field must use either radio buttons or a menu.)
* Create a feature for 'Book Review' content type.
    (Generate in modules directory, enable in Features management page, commit with repository.)
* Create a 'New Books' view and display as a block.
    (Set block to display the 3 newest book reviews as an unformatted list of linked titles. Don't use a pager.)
* Add 4 book reviews.
* Add 'New Books' view to 'Book Review' feature, recreate feature.
    (Generate in modules directory, enable in Features management page, commit with repository.)
* Create 'Reviewer' role and assign permissions.
    (The 'Reviewer' role should have all the same permissions as an authenticated user, and also be able to create new book reviews. They should be able to edit and delete their own book reviews, but not anyone else's.)
* Create account for a user with 'Reviewer' role.
* Create a coupon block on front page, visible to authenticated users but not anonymous.
    ("This week: use this coupon code to get 25% off on all Science Fiction!")
* Create 'Book Reviews' view to display 'Book Review' content as a page.
* Recreate 'Book Review' feature to include 'Book Reviews' view.
* Export database at the end of project and include the .zip file in a db-backup folder within in the sites directory. Include it with your repository.

Submit to Epicenter before 5 pm!
