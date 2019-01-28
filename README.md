# Bounce Servers

Custom ruby script to bounce servers from your local machine. Can also be extended to run any command on multiple servers at once. 

* Bounces servers in a loop
* The script calls 'bounce' script on server
* 'bounce' is an executable file on server, it has 'stop' and 'start' commands with a 3 seconds delay
* this script loops over all the production servers and tries to bounce

NOTE: All the servers need to have same username and password.