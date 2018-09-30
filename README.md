# Bungeecord and Spigot installer for Linux

* [Requirements](#system-requirements)
* [Features](#features)
* [Supported versions](#supported-versions)
* [Installing](#installing)
* [Launch](#launch)
* [Updating](#updating)
* [Bugs](#bugs)
* [License](#license)

# Requirements

* Unix-like OS

* curl




# Features 

* Auto-Updater
* Automatically install all prerequisites
* Install both BungeeCord and Spigot at the same time.
* Using the latest stable versions of Spigot.


# Supported versions
* 1.8
* 1.9.x
* 1.10.x
* 1.11.x
* 1.12.x
* 1.13 (Beta)

# Installing

* **curl** is required to download the script.

* If you are logged in as root 
```bash
curl https://uploads.admlbs.fr/download.php?file=mcinstall --output /usr/bin/mcinstall && chmod 0777 /usr/bin/mcinstall
```

* If it's not the case : 

```bash
sudo curl https://uploads.admlbs.fr/download.php?file=mcinstall --output /usr/bin/mcinstall && chmod 0777 /usr/bin/mcinstall
```

# Launch

* To launch the script you must use sudo or being root

```bash
mcinstall
```

# Updating

* To update the script you must use sudo or being root

```bash
mcinstall update
```
# Bugs


* Please report all bugs to adam@laabase.ovh


# License

This programm is distribued under GNU General Public License v3.0
