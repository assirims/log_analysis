# Logs Analysis

Log Analysis is a project in the Full-Stack Nanodegree from Udacity.

## Project Summary

This project summarizes and reports questions from a large database of a News website/application. The project aims to strength the concepts of using Git, PSQL queries, and Python programming language.

The questions the SQL queries answers are the following:

1. What are the most popular three articles of all time?
2. Who are the most popular article authors of all time?
3. On which days did more than 1% of requests lead to errors?


## Requirements

### You will need:
You should have the following to run the project:

[Vagrant](https://www.vagrantup.com/) - A virtual environment builder and manager.

[VirtualBox](https://www.virtualbox.com/) - An open source virtualization product by Oracle.

[Git](http://git-scm.com/) - An open source version control system (VCS).

[Python3](https://www.python.org/downloads/release/python-371/) - The code uses version 3.7.1 of Python


### To Run

Launch Vagrant VM by running `vagrant up`, you can the log in with `vagrant ssh`

To load the data, use the command `psql -d news -f newsdata.sql` to connect a database and run the necessary SQL statements.

The database includes three tables:
- Authors table
- Articles table
- Log table

To execute the program, run `python3 newsdata.py` from the command line.

To run the code, follow the steps below:

1. Download and install Python3.

2. Download and install Vagrant and VirtualBox.

3. Download the [VagrantFile](https://github.com/udacity/fullstack-nanodegree-vm/blob/master/vagrant/Vagrantfile) and [database](https://d17h27t6h515a5.cloudfront.net/topher/2016/August/57b5f748_newsdata/newsdata.zip)

4. Launch Vagrant VM by running `vagrant up`.

5. Use the command `psql -d news -f newsdata.sql` to connect a database and run the necessary SQL statements.
