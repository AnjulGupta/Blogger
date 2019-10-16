# Team Falcon11

Designed a fully working blogger website having features of creating, publishing and viewing blogs and comments etc with specific functionalities mentioned in the problem statement provided.

## Team Members:

1) Anjul Ravi Gupta 	2018201021
2) Monu Tayal			2018201042
3) Danish Mukthar		2018201016
4) Giridhari Lal Gupta 	2018201019

## Features:

### Specific to Authors(Admins):

* Multiple Authors can register.
* A author can post many blogs.
* The auther can edit and delete his/her blogs.
* Author can style his blogs and add images.
* Author can comment.
* Profile option for looking at all profiles and also editing own profile.
* All Users option to look at list of all authors and their contact information.
* Logout option to go back to user mode.

### Specific to Users:

* Users can browse blogs and comment.
* New User option to register for author.
* Login option to login into author profile.
* Achieve option for looking all blogs with their dates.

Built using Python, Flask, sqlite3, FontAwesome and TinyMCE.

## End User Documentation:

Install everything listed in requirements.txt using (or do it manually)

	pip install -r requirements.txt

Clone the repository on your local system

	git clone https://github.com/girdhari9/Falcon.git

Open the directory

	cd Falcon

Generate the sqlite database by running (if falcon.db not already present)

	sqlite3 falcon.db < schema.sql

setup a virtual environment

	python2 falcon.py
