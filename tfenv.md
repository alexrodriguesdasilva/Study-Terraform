# What is tfenv?
#### tfenv is a terraform version manager

# Installation:
#### Clone source files into ~/.tfenv:
```shell
git clone https://github.com/tfutils/tfenv.git ~/.tfenv
```
#### Add ~/.tfenv/bin to your $PATH:
```shell
echo 'export PATH="$HOME/.tfenv/bin:$PATH"' >> ~/.bash_profile
```
#### Create symlink to the executable:
```shell
sudo ln -s ~/.tfenv/bin/* /usr/local/bin
```

# Usage:
#### To get installed version:
```shell
tfenv --version
```
#### To get list of all available commands:
```shell
tfenv --help
```
#### To list all installed versions:
```shell
tfenv list
```
#### To list all installable versions from remote repositories:
```shell
tfenv list-remote
```
#### To install a specific version of Terraform use:
```shell
tfenv install [version]
```
#### To switch to a specific version use
```shell
tfenv use [version]
```