# HAProxy Windows Build

## Run as a service with nssm.exe

```
Path: C:\path\to\haproxy.exe
Startup Directory: C:\path\to\
Arguments: -C C:\path\to -f haproxy.cfg -db
```

If the above fails, recommend using a Scheduled Task to continuously start HAP.

## Run manually
```
C:\path\to\haproxy.exe -C C:\path\to\ -f haproxy.cfg
```
or daemonize
```
C:\path\to\haproxy.exe -C C:\path\to\ -f haproxy.cfg -D
```
