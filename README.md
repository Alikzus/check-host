# check-host

Check-host is used to monitor if a host is alive or not (with ping). I use it
both on- and offsite.

## Usage

```shell
check-host hostname
check-host -f config-file
check-host -t config-file
```

**Note:** If called from crontab as a cronjob you would probably want to add ```> /dev/null```.
