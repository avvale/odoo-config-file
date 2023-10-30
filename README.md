# [Odoo](https://www.odoo.com "Odoo's Homepage") Config file

## Installation procedure

##### 1. Download the script:
```
sudo wget https://raw.githubusercontent.com/avvale/odoo-config-file/main/odoo-server.conf
```

##### 2. Modify the parameters as you wish.
Configure the configuration file with the appropriate properties.
```
nano odoo-server.conf
```

##### 3. Replaces the current configuration file
Copy and overwrite the configuration file, creating a copy of the original file named odoo-server.conf~
```
cp -b odoo-server.conf /etc/odoo-server.conf
```

##### 4. Restart Odoo server
```
sudo service odoo-server restart
```
or
```
sudo service odoo-server stop
sudo service odoo-server start
```