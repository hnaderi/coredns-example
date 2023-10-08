### CoreDNS docker-compose example

This is a simple example for a dns server deployment using CoreDNS, that supports auto loading of zone files.
It scans and loads zone files automatically using `auto` plugin, so you can update the zone files manually, or use [git-sync](https://github.com/kubernetes/git-sync) to pull a git repository of your zone files.

#### Use
```
docker-compose up
```

