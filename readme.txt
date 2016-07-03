1.This is for the SSH password login, or cancel free password login;
   through the machine generated public key and private key, the generated public key to add to the remote server ~/.ssh/authorized_keys file.

2.command add_free_login
   ./free_login <username@host> <username@host> <username@host> ...
   username@host is ssh username@host

3.command cancel_free_login
   ./cancel_free_login <username@host> <username@host> <username@host> ...
   username@host is ssh username@host

4.If you have executed the add_free_login command, you can not login, please perform setenforce 0; try again.
