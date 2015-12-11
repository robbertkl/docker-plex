# robbertkl/plex

[![](https://badge.imagelayers.io/robbertkl/plex:latest.svg)](https://imagelayers.io/?images=robbertkl/plex:latest)

Docker container running Plex Media Server:

* Exposes port 32400
* Use a reverse proxy to configure (only allowed from other docker containers)

## Usage

Run like this:

```
docker run -d -v <path-to-media-dir>:/media -p 32400:32400 robbertkl/plex
```

## Authors

* Robbert Klarenbeek, <robbertkl@renbeek.nl>

## License

This repo is published under the [MIT License](http://www.opensource.org/licenses/mit-license.php).
