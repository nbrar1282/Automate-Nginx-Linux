# Server Configuration Repository

This public Git repository contains configuration files and scripts for setting up a server with specific software, security settings, and file placement for a front-end and back-end application.

## Directory Structure
- `/var/www/my-site/`:
  - `index.html`: Front-end index.html
- `/var/www/`:
  - `hello-server`: Backend binary hello-server
- `/etc/nginx/sites-available/`:
  - `hello.conf`: Nginx configuration for hello server
- `/etc/nginx/sites-enabled/`:
  - `hello.conf`: Symbolic link to hello.conf
- `/etc/systemd/system/`:
  - `hello-server.service`: Systemd service for hello-server
 
**Note** : Copy & paste the contents of cloud-config.yaml file while creating the new servers web1 and web2 in digital ocean. 
