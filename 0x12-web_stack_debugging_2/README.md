This project focuses on debugging issues in a web stack environment by creating a Bash script that accepts one argument. The script will run the whoami command under the user passed as an argument.

Script Usage
To use the script, follow these steps:

Open a terminal.
Navigate to the directory where the script is located.
Run the script by providing a user as an argument, like this:
./0-iamsomeoneelse <user>
Replace <user> with the desired username to run the whoami command under.
Example
Here's an example of running the script:

$ whoami
root
$ ./0-iamsomeoneelse www-data
www-data
$ whoami
root
