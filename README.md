# Collabify_Nginx
Nginx configuration for the backend

The configuration files are located at /etc/nginx on the Collabify server.  Root privileges are needed to make changes to these files.  Right now, this repository is just keeping track of the main config file (nginx.conf) and the config files for each of the individual sites (sites-available/).  To enable access to a site on the server, a symbolic link must also be created in sites-enabled/ which points to the corresponding config file in sites-available/.
