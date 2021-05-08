# Plex Metadata Agent
#### This plugin acts as an agent for [Plex Media Server](https://plex.tv) and downloads information about films from the [Кинопоиск](https://www.kinopoisk.ru/)

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/muxcc/Kinopoisk.bundle?color=f60&style=flat-square)](https://github.com/muxcc/Kinopoisk.bundle/releases/latest)
[![GitHub Release Date](https://img.shields.io/github/release-date/muxcc/Kinopoisk.bundle?style=flat-square)](https://github.com/muxcc/Kinopoisk.bundle/releases/latest)
[![GitHub commits since latest release (by date)](https://img.shields.io/github/commits-since/muxcc/Kinopoisk.bundle/latest?style=flat-square)](https://github.com/muxcc/Kinopoisk.bundle/releases/latest)
[![GitHub last commit](https://img.shields.io/github/last-commit/muxcc/Kinopoisk.bundle?style=flat-square)](https://github.com/muxcc/Kinopoisk.bundle/commits/master)
[![GitHub repo size](https://img.shields.io/github/repo-size/muxcc/Kinopoisk.bundle?style=flat-square)](https://github.com/muxcc/Kinopoisk.bundle)
[![GitHub all releases](https://img.shields.io/github/downloads/muxcc/Kinopoisk.bundle/total?style=flat-square)](https://github.com/muxcc/Kinopoisk.bundle)
![GitHub top language](https://img.shields.io/github/languages/top/muxcc/Kinopoisk.bundle?style=flat-square)
[![GitHub](https://img.shields.io/github/license/muxcc/Kinopoisk.bundle?style=flat-square)](https://mit-license.org/)

![Plex Metadata Agent](https://github.com/muxcc/AummGit/raw/master/docs/pub/images/kinopoisk.png "This plugin acts as an agent for Plex Media Server and downloads information about films from the Кинопоиск site.")

## Features
#### 1. Loading movie ratings
+ Kinopoisk
+ Rotten Tomatoes
+ IMDb
+ The Movies Database
#### 2. Sources of film reviews
+ Kinopoisk
+ Rotten Tomatoes
#### 3. Download movie trailers
#### 4. Proxy server support (http, sock5)

## Plugin paths and installation
Download the ZIP archive [github.com](https://github.com/muxcc/Kinopoisk.bundle/archive/master.zip)

### Windows
Unpack the downloaded archive into a folder `%LOCALAPPDATA%\Plex Media Server\Plug-ins`.

### MacOS
Unpack the downloaded archive into a folder `~/Library/Application Support/Plex Media Server/Plug-ins`

### Debian / Ubuntu
We check for the presence of the necessary libraries and / or install everything necessary
```
sudo apt update && sudo apt install -y git
cd /var/lib/plexmediaserver/Library/Application\ Support/Plex\ Media\ Server/Plug-ins/
sudo git clone https://github.com/muxcc/Kinopoisk.bundle.git
sudo chown -R plex:plex Kinopoisk.bundle/
sudo service plexmediaserver restart
```
### FreeBSD
Unpack the downloaded archive into a folder `/usr/local/plexdata/Plex Media Server/`

### FreeNAS
Unpack the downloaded archive into a folder `${JAIL_ROOT}/var/db/plexdata/Plex Media Server/`

### QNAP
The specific location may vary. To check, enter in the console <br />
`getcfg -f /etc/config/qpkg.conf PlexMediaServer Install_path`

We copy the issued path, adding at the end `/Library/Plex Media Server`, for example, `/share/CACHEDEV1_DATA/.qpkg/PlexMediaServer/Library/Plex media Server`

### Synology
Unpack the downloaded archive into a folder `/volume1/Plex/Library/Application Support/Plex Media Server/Plug-ins`

## About
This is a fork [Kinopoisk.bundle](https://github.com/amirotin/Kinopoisk.bundle) <br />
by Artem Mirotin aka @amirotin
