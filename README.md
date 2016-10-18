# Linux Tips

## Mount local folder by samba network server
```sh
mount -t cifs //NETWORK_IP/PATH
```

## Dump MySQL Database to file
```sh
mysqldump --databases DATABASE_NAME > PATH.sql -u USER -p
```

## Get PID by process name
```sh
ps ax | grep MY_NAME
```
