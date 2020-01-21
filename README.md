# oracle-wallet-mozilla-ca
Ansible role to convert Mozilla CA file into Oracle wallet so it could be used in PL/SQL

If you are doing many HTTPS calls from PL/SQL to many different sites, managing oracle wallet with all the reuired trusted certificates is quite painful.
But Linux distros already come bundled with all the trusted CA certs from Mozilla, would it be nice just to convert it to Oracle wallet format so PL/SQL could use it?

Here is an Ansible role just for this, you could run it regularly to make sure you have the latest Mozilla trusted certs.
