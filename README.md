# Development Kit Vagrant with PHP7-MariaDB-Nginx for Symfony
For now the project is configured for using with Symfony, but you can change the nginx.conf in **Resources/templates/nginx.conf** as you want.

## Install
````
vagrant up default
````

## Access via ssh
```
vagrant ssh default
```

## Sync
````
vagrant rsync default
```

## Default settings
* **Private newtork**: 166.66.66.2
* **Server name**: server.devel.local
* **Files Path**: /var/www/current
* **Mysql user**: root
* **Mysql password**: 12345678

###Improvements
If you think that you can improve this machine, fork this repo, and send me a pull request. I'll be happy to add your new features.




