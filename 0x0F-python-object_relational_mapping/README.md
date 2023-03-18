# Python - Object-relational mapping

	In this project, I learned about how object-relational mapping is used for database scripting. I became familiar with using MySQLdb and SQLAlchemy to query, create, edit, and delete tables in MySQL.


## Tests heavy_check_mark

	tests: Folder of SQL and Python scripts for setting up test tables for all files. Provided by ALX.

## Tasks page_with_curl


	0. Get all states

0-select_states.py: Python script that uses MySQLdb to list all states in the database hbtn_0e_0_usa.
Usage: ./0-select_states.py <mysql username> <mysql password> <database name>.

## Results are ordered by ascending states.id.

	1. Filter states

	1-filter_states.py: Python script that uses MySQLdb to list all states with names starting with N in the database hbtn_0e_0_usa.
Usage: ./1-filter_states.py <mysql username> <mysql password> <database name>.
Results are ordered by ascending states.id.
	
	2. Filter states by user input

	2-my_filter_states.py: Python script that uses MySQLdb to display all values matching a given name in the states table of the database hbtn_0e_0_usa.
Usage: ./2-my_filter_states.py <mysql username> <mysql password> <database name> <state name searched>.
Results are ordered by ascending states.id.
Uses string formatting to construct the SQL query.


	3. SQL Injection...

	3-my_safe_filter_states.py: Python script that uses MySQLdb to display all values matching a given name in the states table of the database hbtn_0e_0_usa.
Usage: ./3-my_safe_filter_states.py <mysql username> <mysql password> <database name> <state name searched>.
Results are ordered by ascending states.id.
Safe from SQL injections.


	4. Cities by states

	4-cities_by_state.py: Python script that uses MySQLdb to list all cities from the database hbtn_0e_4_usa.
Usage: ./4-cities_by_state.py <mysql username> <mysql password> <database name>.
Results are ordered by ascending cities.id.

	5. All cities by state

	5-filter_cities.py: Python script that uses MySQLdb to list all cities of a given state in the database hbtn_0e_4_usa.
Usage: ./5-filter_cities.py <mysql username> <mysql password> <database name>.
Results are sorted by ascending cities.id.

	6. First state model

model_state.py: Python module defining a class State that inherits from SQLAlchemy Base and links to the MySQL table states.


	7. All states via SQLAlchemy

	7-model_state_fetch_all.py: Python script that uses SQLAlchemy to list all State objects from the database hbtn_0e_6_usa.
Usage: ./7-model_state_fetch_all.py <mysql username> <mysql password> <database name>.
Results are sorted by ascending states.id.

	8. First state

	8-model_state_fetch_first.py: Python script that uses SQLAlchemy to print the first State object from the database hbtn_0e_6_usa, ordered by states.id.
Usage: ./8-model_state_fetch_first.py <mysql username> <mysql password> <database name>.
If the states table is empty, prints Nothing.

