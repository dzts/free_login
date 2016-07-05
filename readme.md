###This is for the SSH password login, or cancel free password login;###
   Through the machine generated public key and private key, the generated public key to add to the remote server ~/.ssh/authorized_keys file.

####command add_free_login####
   ./free_login <username@host> <username@host> <username@host> ...
   username@host is ssh username@host

####command cancel_free_login####
   ./cancel_free_login <username@host> <username@host> <username@host> ...
   username@host is ssh username@host

####login failed ####
If you have executed the add_free_login command, you can not login, please perform setenforce 0; try again.
