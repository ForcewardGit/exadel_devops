# Troubleshooting a problem with SSH access
First of all, this problem may arise when trying to connect to a remote server using ssh for the first time.<br>
In order to connect to a remote server using SSH, I need to perform several steps:
* I need to know my server's name or IP;
* I need to know my credentials (username, password);
* I need to know to which port I should connect to (if the default one is changed);
* Open a terminal where I can run SSH commands;
* Type: `ssh my_username@host_ip_address -pPORT_NUMBER`;
* Then, write my password;
* If the remote server is not identified by my PC, I should add it to a list of known hosts, I can do that after hitting my password since I will be prompted to to do so if needed;
* And now I can do my work on this server as I am now connected to it!
