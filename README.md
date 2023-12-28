# [Oink!](https://github.com/RLado/Oink) snap package
### Build
> Requires: snapcraft, make, go
```
snapcraft
```

### Installing Oink!
```
snap install <oink_pkg>.snap
```

⚠️ The configuration file in **/var/snap/oink/common/config.json** must be modified before activating the DDNS daemon.

### Running the service
```
snap start --enable oink
```

*You may check on the service logs by using `snap logs oink`*

