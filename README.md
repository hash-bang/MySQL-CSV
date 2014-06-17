MySQL-CSV
=========
Quick and dirty script to output a MySQL table into CSV form.

	mysql-csv <database> <table> [fields]

If fields are omitted '*' is assumed.


Installation
------------
Either just run:

	sudo make install

or copy the 'mysql-csv' script into `/usr/bin` manually.


Examples
--------
Output all users in the users table with all fields:

	mysql-csv mydb users

Output only user ids and email addresses:

	mysql-csv mydb users 'userid, email'
