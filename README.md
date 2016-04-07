# Description

This Jenkins slave docker image that used for run python applications, that require mongodb.

Mongodb is not started with a container, so it should be started manually in job configuration:
```
sudo /usr/bin/mongod --fork --logpath /var/log/mongod.log
```
