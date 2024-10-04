# Invidious-Updater (And Installer)

```bash
                  ╔═══════════════════════════════════════════════════════════════════╗
                  ║                        Invidious Update.sh                        ║
                  ║               Automatic update script for Invidious               ║
                  ║                      Maintained by @tmiland                       ║
                  ╚═══════════════════════════════════════════════════════════════════╝
```
[![GitHub release](https://img.shields.io/github/release/tmiland/Invidious-Updater.svg?style=for-the-badge)](https://github.com/tmiland/Invidious-Updater/releases)
[![licence](https://img.shields.io/github/license/tmiland/Invidious-Updater.svg?style=for-the-badge)](https://github.com/tmiland/Invidious-Updater/blob/master/LICENSE)
![Bash](https://img.shields.io/badge/Language-SH-4EAA25.svg?style=for-the-badge)

## Script to install and update [Invidious](https://github.com/iv-org/invidious)

```bash
1) Install Invidious           7) Uninstall Invidious
2) Update Invidious            8) Set up PostgreSQL Backup
3) Deploy with Docker          9) Install Nginx 
4) Add Swap Space             10) Install Inv sig helper
5) Run Database Maintenance   11) Install YouTube tsg.
6) Start, Stop or Restart     12) Exit
```
### Installation
See [Install.md](./INSTALL.md)

If you're looking for a quick way to install, check out [Invidious-Installer](https://github.com/tmiland/invidious-installer)

![invidious_update](https://raw.githubusercontent.com/tmiland/Invidious-Updater/master/img/invidious_update.gif)

### Tested on

| Debian | Ubuntu |
| ------ | ------ |
| [<img src="https://raw.githubusercontent.com/tmiland/Invidious-Updater/master/img/Debian_12.png" height="140" width="280">](https://raw.githubusercontent.com/tmiland/Invidious-Updater/master/img/Debian_12.png) | [<img src="https://raw.githubusercontent.com/tmiland/Invidious-Updater/master/img/Ubuntu.png" height="140" width="280">](https://raw.githubusercontent.com/tmiland/Invidious-Updater/master/img/Ubuntu.png) 

| CentOS | Fedora |
| ------ | ------ |
| [<img src="https://raw.githubusercontent.com/tmiland/Invidious-Updater/master/img/CentOS.png" height="140" width="280">](https://raw.githubusercontent.com/tmiland/Invidious-Updater/master/img/CentOS.png) | [<img src="https://raw.githubusercontent.com/tmiland/Invidious-Updater/master/img/Fedora_40.png" height="140" width="280">](https://raw.githubusercontent.com/tmiland/Invidious-Updater/master/img/Fedora_40.png)

| Arch | PureOS |
| ------ | ------ |
| [<img src="https://raw.githubusercontent.com/tmiland/Invidious-Updater/master/img/Arch.png" height="140" width="280">](https://raw.githubusercontent.com/tmiland/Invidious-Updater/master/img/Arch.png) | [<img src="https://raw.githubusercontent.com/tmiland/Invidious-Updater/master/img/PureOS.png" height="140" width="280">](https://raw.githubusercontent.com/tmiland/Invidious-Updater/master/img/PureOS.png)

| Linux Mint |
| ------ |
| [<img src="https://raw.githubusercontent.com/tmiland/Invidious-Updater/master/img/Mint_22.png" height="140" width="280">](https://raw.githubusercontent.com/tmiland/Invidious-Updater/master/img/Mint_22.png)

## Recommendation

***It is recommended to use this script on a fresh installation to avoid unwanted complications.***
  * I recommend a Debian 12 Droplet on [DigitalOcean](https://m.do.co/c/f1f2b475fca0)

## Testing

Tested and working on:

| Debian | Ubuntu | CentOS | Fedora | Arch | PureOS |
| ------ | ------ | ------ | ------ | ------ | ------ |
| [<img src="https://raw.githubusercontent.com/tmiland/Invidious-Updater/master/img/os_icons/debian.svg?sanitize=true" height="128" width="128">](https://raw.githubusercontent.com/tmiland/Invidious-Updater/master/img/os_icons/debian.svg?sanitize=true) | [<img src="https://raw.githubusercontent.com/tmiland/Invidious-Updater/master/img/os_icons/ubuntu.svg?sanitize=true" height="128" width="128">](https://raw.githubusercontent.com/tmiland/Invidious-Updater/master/img/os_icons/ubuntu.svg?sanitize=true) | [<img src="https://raw.githubusercontent.com/tmiland/Invidious-Updater/master/img/os_icons/cent-os.svg?sanitize=true" height="128" width="128">](https://raw.githubusercontent.com/tmiland/Invidious-Updater/master/img/os_icons/cent-os.svg?sanitize=true) | [<img src="https://raw.githubusercontent.com/tmiland/Invidious-Updater/master/img/os_icons/fedora.svg?sanitize=true" height="128" width="128">](https://raw.githubusercontent.com/tmiland/Invidious-Updater/master/img/os_icons/fedora.svg?sanitize=true) | [<img src="https://raw.githubusercontent.com/tmiland/Invidious-Updater/master/img/os_icons/arch.svg?sanitize=true" height="128" width="128">](https://raw.githubusercontent.com/tmiland/Invidious-Updater/master/img/os_icons/arch.svg?sanitize=true) | [<img src="https://raw.githubusercontent.com/tmiland/Invidious-Updater/master/img/os_icons/pureos.svg?sanitize=true" height="128" width="128">](https://raw.githubusercontent.com/tmiland/Invidious-Updater/master/img/os_icons/pureos.svg?sanitize=true)

- [X] Tested extensively on Debian 9/10/11/12
  - [X] Docker option tested and working
- [X] Tested on Ubuntu 16.04
  - [X] Docker option tested, not working
- [X] Tested on Ubuntu 18.10
  - [X] Docker option tested and working
- [X] Tested on CentOS 8
  - [ ] Docker option tested and working
- [X] Tested on Fedora 40
  - [X] Docker option tested and working
- [X] On Bash on Debian on Windows (in Gnome-Boxes)
  - [X] Systemd not working
  - [X] Docker option not working
- [X] Tested on Linux Mint 22
  - [X] Docker option tested and working
  - See [#15](https://github.com/tmiland/Invidious-Updater/issues/15)
- [X] Tested on Arch Linux
  - [X] Docker option tested and working
  
  ~~If you get permission issues, set selinux to permissive. 
  See how to here: [How do I enable or disable SELinux ?](https://fedoraproject.org/wiki/SELinux_FAQ#How_do_I_enable_or_disable_SELinux_.3F)~~
  #### SELinux will be set to permissive on Fedora and CentOS

  ~~***Postgresql 11 will be installed by default in both Fedora and CentOS. (If not already installed)***~~
  Postgresql will be default from repo on Fedora and CentOS
  
#### Latest install log - version: 1.4.4

[install log Debian 10](https://github.com/tmiland/Invidious-Updater/blob/master/log/install_log_debian.log)

## Changelog

See [Changelog](https://github.com/tmiland/Invidious-Updater/blob/master/CHANGELOG.md)

## Compatibility and Requirements

- Debian 8 and later
- Ubuntu 16.04 and later
- Linux Mint 22
- PureOS (Not tested)
- CentOS 8
- Fedora 40
  - Docker support
    - [OS requirements](https://docs.docker.com/install/linux/docker-ce/fedora/)
- Arch Linux

## Credits
- Code is mixed and customized from these sources:
  - [Invidious](https://github.com/omarroth/invidious#linux)
  - [inv_sig_helper](https://github.com/iv-org/inv_sig_helper)
  - [YouTube trusted session generator](https://github.com/iv-org/youtube-trusted-session-generator)
  - [nginx-autoinstall](https://github.com/angristan/nginx-autoinstall)
  - [Git-Repo-Update](https://github.com/KillianKemps/Git-Repo-Update)
  - [ghacks user.js updater.sh](https://github.com/ghacksuserjs/ghacks-user.js/blob/master/updater.sh)
  - Plus many more.

## Feature request and bug reports
- [Bug report](https://github.com/tmiland/Invidious-Updater/issues/new?assignees=tmiland&labels=bug&template=bug_report.md&title=Bug-report:)
- [Feature request](https://github.com/tmiland/Invidious-Updater/issues/new?assignees=tmiland&labels=enhancement&template=feature_request.md&title=Feature-request:)
- [IRC Freenode: #InvidiousUpdater](irc://freenode.net/#InvidiousUpdater)

## Donations
<a href="https://coindrop.to/tmiland" target="_blank"><img src="https://coindrop.to/embed-button.png" style="border-radius: 10px; height: 57px !important;width: 229px !important;" alt="Coindrop.to me"></img></a>

## Web Hosting

Sign up for web hosting using this link, and receive $200 in credit over 60 days.

<a href="https://www.digitalocean.com/?refcode=f1f2b475fca0&amp;utm_campaign=Referral_Invite&amp;utm_medium=Referral_Program&amp;utm_source=badge"><img src="https://web-platforms.sfo2.digitaloceanspaces.com/WWW/Badge%203.svg" alt="DigitalOcean Referral Badge"></a>

#### Disclaimer 

*** ***Use at own risk*** ***

### License

[![MIT License Image](https://upload.wikimedia.org/wikipedia/commons/thumb/0/0c/MIT_logo.svg/220px-MIT_logo.svg.png)](https://github.com/tmiland/Invidious-Updater/blob/master/LICENSE)

[MIT License](https://github.com/tmiland/Invidious-Updater/blob/master/LICENSE)
