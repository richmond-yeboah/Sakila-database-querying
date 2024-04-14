# Sakila-database-querying
This projects a an exhibition of my skills and knowledge in using programming languages like SQL and Python at the same. Using SQL to query the database for information and reading the output of the query into pandas dataframe and visualization with python libraries.

# Introduction to the sakila database
The Sakila database is a nicely normalized schema modeling a DVD rental store, featuring things like films, actors, film-actor relationships, and a central inventory table that connects films, stores, and rentals. It contains 16 tables of which some are rental, store, actor, payment, and customer table.

# Connecting to the database
First I import needed libraries and then I create a text file to house my environmental variables (database credentials). I then use the load_dotenv() function to get the text file housing our environment variables. The getenv method helps me to secretly get credentials from the text file and assign them the appropriate variable names without showing the credentials (For safety sake) and then I create a variable to help me with the connection.

# Querying the Database, Analysis and Visualization
After creating a connection to the database, I then run SQL queries to get an output and assign it to a variable name in pandas where I can analyze it to create visualizations to communicate insights.
