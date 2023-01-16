# Jexactyl-Installer (By NineNodes Team)


Read more about [jexactyl](https://jexactyl.com/) here. This script is not associated with the official Pterodactyl Project or jexacyl.

## Features

- Automatic installation of the Jexactyl Panel (dependencies, database, cronjob, nginx).
- Automatic installation of the Pterodactyl Wings (Docker, systemd).
- Panel: (optional) automatic configuration of Let's Encrypt.
- Panel: (optional) automatic configuration of firewall.

## Supported installations

List of supported installation setups for panel and Wings (installations supported by this installation script).

### Supported panel operating systems and webservers

| Operating System | Version | nginx support      | PHP Version |
| ---------------- | ------- | ------------------ | ----------- |
|     Ubuntu       | 18.04   | :white_check_mark: | 8.0         |
|     Ubuntu       | 20.04   | :white_check_mark: | 8.0         |
|     Ubuntu       | 22.04   | :white_check_mark: | 8.0         |
| ---------------- | ------- | ------------------ | ----------- |
|     Debian       | 9       | :white_check_mark: | 8.0         |
|     Debian       | 10      | :white_check_mark: | 8.0         |
|     Debian       | 11      | :white_check_mark: | 8.0         |
| ---------------- | ------- | ------------------ | ----------- |
|      CentOS      | 6       | :red_circle:       | 8.0         |
|      CentOS      | 7       | :white_check_mark: | 8.0         |
|      CentOS      | 8       | :white_check_mark: | 8.0         |
|      CentOS      | 8       | :white_check_mark: | 8.0         |

### Supported Wings operating systems

| Operating System | Version | Supported          |
| ---------------- | ------- | ------------------ |
| Ubuntu           | 18.04   | :white_check_mark: |
| Ubuntu           | 20.04   | :white_check_mark: |
| Ubuntu           | 22.04   | :white_check_mark: |
| ---------------- | ------- | ------------------ |
| Debian           | 9       | :white_check_mark: |
| Debian           | 10      | :white_check_mark: |
| Debian           | 11      | :white_check_mark: |
| ---------------- | ------- | ------------------ |
| CentOS           | 6       | :red_circle:       |
| CentOS           | 7       | :white_check_mark: |
| CentOS           | 8       | :white_check_mark: |

_\* Ubuntu 16 & Debian 8 & CentOS 6 no longer supported since Pterodactyl does not actively support it._

## Using the installation scripts

To use the installation scripts, simply run this command as root. The script will ask you whether you would like to install just the panel, just Wings or both.

```bash
bash <(curl -s https://raw.githubusercontent.com/NineWhiteDream/jexactyl-installer/v0.13.0/install.sh)
```

_Note: On some systems, it's required to be already logged in as root before executing the one-line command (where `sudo` is in front of the command does not work)._

