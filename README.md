# frappeinstallGudie
- sudo apt install git python3-dev python-pip redis-server
- sudo apt install software-properties-common
- sudo apt-get update
- sudo apt-get install mariadb-server
change to root
- mysql_secure_installation
- apt-get install mariadb-client-10.3
- nano /etc/mysql/my.cnf
```
[mysqld]
character-set-client-handshake = FALSE
character-set-server = utf8mb4
collation-server = utf8mb4_unicode_ci

[mysql]
default-character-set = utf8mb4
```
- service mysql restart
- curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.11/install.sh | bash
- nvm install 14
- node -v

v14.17.2
- npm install -g yarn
- apt-get install xvfb libfontconfig
- https://wkhtmltopdf.org/downloads.html
- dpkg -i wkhtmltox_file.deb
- pip3 install frappe-bench
- bench --version


5.2.1
- cd ~
- bench init frappe-bench
- bench start

-$ bench find .
/home/frappe/frappe-bench is a bench directory!
- $ bench new-app (appname)
- bench new-site library.localhost
- $ bench --site library.localhost add-to-hosts
 http://library.localhost:8000
- $ bench --site library.localhost install-app library_management

Installing library_management...
- $ bench --site library.localhost list-apps
frappe
library_management



