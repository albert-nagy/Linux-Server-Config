#Linux Server Configuration Project

##URL

https://repertorio.symphonic-music.com

##IP Address

35.157.212.201

##Software installed

- apache2
- libapache2-mod-wsgi-py3
- postgresql
- python3-pip
- sudo -H pip3 install psycopg2-binary python-slugify
- sudo -H pip3 install flask oauth2client markdown
- Recreate Google and FB client secret files
- Clone Repertorio repository
- certbot python-certbot-apache

##Configurations

- Update system packages
- Set timezone to UTC
- Create new user
- Add permission to sudo
- Set up key-based SSH
- Set up firewall
- Disable remote root login
- Create catalog role for PostgreSQL
- Prevent Apache from serving .git directory
- Configure Apache to serve app using WSGI
- Set up DNS at freedns.afraid.org
- Change ServerName in Apache 
- Enable HTTPS for FB Login to work:
	- Install and configure Certbot
	- Enable port 443 in firewalls
- Add new domain, redirect URLs and JavaScript origin to Facebook and Google OAuth apps


