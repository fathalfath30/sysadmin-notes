### Standard web server installation using apache, mysql and php

```shell script
# install apache2
sudo apt-get install apache2

# enable apache rewrite module
sudo a2enmod rewrite

# enable apache ssl module (optional)
sudo a2enmod ssl 

# install mysql-server and mysql-client
sudo apt-get install mysql-{client,server}

# run mysql_secure_installation
sudo mysql_secure_installation

# add the PPA to your package repository list : 
sudo add-apt-repository ppa:ondrej/php

# update repository cache :
sudo apt-get update

# install php7.4:
sudo apt-get install php7.4

# install php7.4 basic module
sudo apt-get install php7.4-{bcmath,bz2,intl,gd,mbstring,mysql,zip,fpm}
```
