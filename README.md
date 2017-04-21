# Lending Tree Books

## Created by Xia Amendolara and Matt Kelley April 21st, 2017

  This webstie was created using Drupal, a PHP framework, at Epicodus. This website is a mockup of a bookstore website calld Lending Tree Books.

## User Story

* As a user I would like to view information about the bookstore on the "About" page, and find locations on the "Locations" page.

* As a user I would like to be able to contact the bookstore, regardless of being logged in.

* As a user I would like to view the about page first when I navigate to the site.

* As a user I would like to be able to leave review for books when logged into an account.

* As a user I would like to be able to view new books on the book review page, and I would like to be able to be routed to more information about the book.

* As a user I would like to be able to create a specific account as a reviewer, I want to have all the same premissions to the site as an authenticated user.

* As a user I would like to see any promotions or coupons on the about page when I log in.


## Implementation Plan

| Objective | Implementation | Status |
|:-------------:|:-------------:|:-------------:|
| Download the Drupal core and create a new project | cd bookstore project | completed |
| Remove the .gitignore file | $ git rm .gitignore | completed |
| Add README.md | $ touch README.md | completed |
| Create two basic pages "About" and "Locations" | add content/basic page | complete |
| Enable the Contact module and grant permissions to all visitors | enable module in the Drupal toolbar | incomplete |
|Install the views module, features module, and the strong arm module | $ drush dl module-name and then enable modules in the Drupal toolbar |
| Create a feature for "Site Configuration" | add feature  | incomplete |
| Update the sites theme and set the about page to be landing page | install new theme and set about page to be landing page | incomplete |
| Add a "Book Review" content type with all fields required | label: "Book Title" text: "Book Author" select: "Book Rating" body: "Book Review" | incomplete |
| Create a new feature called "Book Review"  and generate it within the modules directory | enable within the Drupal toolbar /modules | incomplete |
| Create a new view to display  a "New Books" block (w/out pager) | create view with routable "titles" only | incomplete |
| Add books to test that the views is working | add books | incomplete |
| Create a role called "Reviewer" that has the same permissions as an authenticated user | create new user role | incomplete |
| Create a special coupon to be displayed on the landing page, only viewable by logged in users | create block | incomplete |



## Setup/Installation Requirements

  * Follow the link to the Git repository for this project. [Github](https://github.com/Xesme/cameron-coffee.git)
  * In the terminal run `$ git clone link-to-repo-here`
  * In the terminal run `$ cd project-name`
  * Open MAMP and and click on preferences
  * In the preferences menu navigate to webserver and set your document root to project-folder and click okay
  * Click start server in MAMP homescreen
  * On the MAMP homepage click `myphpadmin` to be redirected to the tools page
  * Use the import tab to import the project sql file located in project-root/sites/db_backup/
  * Use the users tab to create a new user with all privledges
  * Open your broswer and go to `localhost:8888` to view the web application in browser.

## Bugs
There are no known bugs at this time, but please contact the creator with questions or concerns regarding this application.

## Technologies Used
* Drupal
* PHP
* Git
* SQL

## Licensing
This application features MIT licensing.

Copyright &copy; 2017 **Xia Amendolara and Matt Kelley** All Rights Reserved.
