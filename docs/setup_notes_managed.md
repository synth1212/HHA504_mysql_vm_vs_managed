# Instruction on Setup steps for managed MySQL:

## Cloud SQL
1. Select to create a sandbox MySQL instance.
2. Name instance and set a password.
3. Select a region press and press create.

## Configuration
1. Add `0.0.0.0/0` to authorized networks.
2. Disable SSL only connection for security.
3. Add a new user with a username and set a password for it.

## Roadblocks
1. Initially tried using the connection name to connect to the database externally. However, found the public IP and used that to connect to the database.

## Time to setup
It took a total aboutabout 15 minutes to create of the database, connecting to the python script, and running a query to check if the script worked properly.