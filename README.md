# Vagrant demo02

With this vagrant repo, you install two ubuntu 18.04 bionic beaver virtual machines. 

This repo is intended for educational purposes only. 

## Prerequisites

This setup is slightly tested (: 

Works on MacOS Catalina.

Software needed:

- Vagrant 2.2.6 or higher
- virtualbox 5.0 or higher
- virtualbox extension pack

__Windows users__

For windows, `git` is needed on the commandline. You can use the Windows packet manager `Chocolatey` for `Powershell` to easily install `git`. 

Chocolatey url
```
https://chocolatey.org/install
```

To install `git` with `Chocolatey` within `Powershell`:
```powershell
choco install git
```

### MacOS Catalina

```bash
brew install vagrant
```

### Ubuntu 18.04

```bash 
apt install -y vagrant
```

### Windows 

Download url
```
https://www.vagrantup.com/downloads.html
```

## Howto start the Vagrant boxes

```
git clone https://github.com/moatn/vagrant02-demo
cd vagrant02-demo
vagrant up
```

## Overview hostnames/ip-addresses

Vagrant name | Hostname | IP Address
--- | --- | ---
web01 | web01.local | 192.168.99.50
web02 | web02.local | 192.168.50.51

__Connection to a vagrant machine and starting the lesson__

```bash
vagrant ssh web01
cat notes/read_first.txt
```

