# Library-Management-System
Certainly! A Library Management System (LMS) is a software application designed to help manage various aspects of library operations. Here are the key features and components typically found in a Library Management System:
<br>

## Development
The backend of the system is developed on **[Laravel 4.2 PHP MVC Framework](http://laravel.com/)** and requires PHP 5.6 with the appropriate MCrypt extension.
The front end is built on **[Edmin Responsive Bootstrap Admin Template](http://egrappler.com/responsive-bootstrap-admin-template-edmin/)** ([Demo](http://www.egrappler.com/edmin/index.html)) which is built on [Bootstrap v2.2.2](http://bootstrapdocs.com/v2.2.2/docs/) using [jQuery](https://blog.jquery.com/2013/02/04/jquery-1-9-1-released/) and [Underscore-Dot-JS](http://underscorejs.org/)

## Contribute
+ For reporting bug about an incorrect file not being processed, open a new issue.
+ PRs are always welcome to improve exisiting system.

## Setup

### Prerequisite: Install MySQL (for Linux)

> If you don't already have the MySQL Database Server installed, you will need to install it to use this project. If it is installed, you can skip to step 4.

1. Oracle provides detailed instructions to install MySQL on any Linux distribution. See ["Installing MySQL on Linux"](https://dev.mysql.com/doc/refman/8.0/en/linux-installation.html) for details and instructions. 
2. Altneratively, you can probably install a working MySQL server that is compatible with this project by running:

`apt-get update && apt-get install mysql-server`

3. *You may be prompted to choose a root password for MySQL during the installation.*
4. You should [create a MySQL user](https://dev.mysql.com/doc/refman/8.0/en/adding-users.html) for this project, [create a database](https://dev.mysql.com/doc/refman/8.0/en/create-database.html) for this project, and may need to give the mysql user permissions to access the database. Instructions to configure the project are provided below.

## Features
 + Librarians can be given their authorized login ID and password without which the system can not be accessed.
 + Students can only access limited features, i.e., public access level features which include **searching a book** and **student registration form**.
 + After logging in librarians can search for a specific book, book issue or student from the home panel.
 + Librarians need to make an entry for new books. To automate the process they simply need to enter the number of issues, then the Issue ID for each book issue is generated automatically.
 + Another responsibility of a librarian is to approve students in situations where approval is needed, i.e. where documents are to be verified or some manual work. Librarians have a panel to simply approve / reject students and to view all approved students. The librarian ID is stored alongside each approved/rejected student to keep track.
 + The most important function of any libra
