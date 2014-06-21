# Installations

## Compile from the source code
```
    cd src
    make
```

## Configurations
The default config file is ```sr.conf``` under the same directory. Another file can be provided at the start up.
```
    ./accelng /path/of/sr.conf
```

Currently the config file supports specifying DNS server for domains. 

This part start with ```xfer``` and end with ```:``` in ```sr.conf```.
```
    xfer:
    googleusercontent.com.:8.8.8.8
    google.com.:8.8.8.8
    youtube.com.:8.8.8.8
    s-static.ak.facebook.com.edgekey.net.:8.8.8.8
    :
```

Logging options (optional)
```
    log_path:
    ./log/
```