# HSQLclient

Thin client for HSQL, a Java-based relational database engine.

See code base and discussions on https://sourceforge.net/projects/hsqldb

## Install / Usage
```sh
brew install hsqlclient/tap/hsqlclient
```


---
```
$ hsqlclient --help

Usage: java DatabaseManagerSwing [--options]
where options include:
    --help                show this message
    --driver <classname>  jdbc driver class
    --url <name>          jdbc url
    --user <name>         username used for connection
    --password <password> password for this user
    --urlid <urlid>       use url/user/password/driver in rc file
    --rcfile <file>       (defaults to 'dbmanager.rc' in home dir)
    --dir <path>          default directory
    --script <file>       reads from script file
    --noexit              do not call system.exit()
```
