# java-assignment

Requirements 
To start the program: run java urldatabase. Further, the program will wait for the user to enter the following commands.
The command storeurl shall take a URL as a parameter and save that into a table with a unique short key and a count(usage count) initialized to 0.
Use local variables instead of a database to store the data.
Use any appropriate logic to generate the unique short key.
The command get shall take a URL as a parameter and return the unique short key after incrementing the usage count.
The command count shall take a URL as a parameter and should return the latest usage count.
The command list should return all urls and counts. The return value is in JSON.
The command exit should terminate the program
