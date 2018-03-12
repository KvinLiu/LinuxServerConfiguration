# About The Server
This is a test server, all info to access list right down

# Server IP adderss
34.228.167.137

# SSH port
2200

# Third-party Application
1. server app **apache** `sudo apt-get install apache2`: this is the server for my app.
2. mod_wsgi **libapache2-mod-wsgi**: `sudo agt-get install libapache2-mod-wsgi`: this mod is for apache can
   talk to python.
3. databse **SQLite** `sudo apt-get install sqlite3`: this is the database for my app.
4. **virtualenv** `sudo apt-get install virtualenv`: this is the tool for create a isolate pyhton dependency
for my app.
5. **pip** `sudo apt-get install python-pip`; Use pip to install project dependency library. because of **virtualenv**
first `source /projectfolder/bin/activate`, then `pip -r requirements.txt` cloud install all dependences.

# Apache2 Config file
In order to let apache server talk to python framework, mod_WSGI were installed.
1. The config file located `/etc/apache2/sites-avaible`, when in that directory, I
2. create a new file `catalog.conf`
3. Type command  `sudo a2ensite catalog` enable the site, use `sudo a2dissite 000-default` to disable
default site.
4. Type `sudo service apache2 restart` to restart apache server.


# View webstie
Type `34.228.167.137` in browser to visit the catalog website

