# [Oink!](https://github.com/RLado/Oink) snap package
### Build
> Requires: snapcraft, make, go
```bash
snapcraft
```

### Installing Oink!
```
snap install <oink_pkg>.snap
```

⚠️ The configuration file in **/var/oink/common/config.json** must be modified before activating the DDNS daemon.

### Running the service
```
snap start oink
```

*You may check on the service logs by using `snap logs oink`*

