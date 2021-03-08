# ft-util
Library of Scripts for Futur-Tech Devs

## Install

    cd <your_repo>

    mkdir ft-util && cd ft-util && wget https://raw.githubusercontent.com/Futur-Tech/ft-util/main/deploy_ft_util && chmod +x deploy_ft_util && ./deploy_ft_util

You can edit which script you need by editing deploy_ft_util

## Update script

    ./deploy_ft_util

## Script available
### ft_util_bak-cleaner

.BAK file cleaner

### ft_util_conf-update

Config File Updater Script

Note: comments on the same lines of a variable set in a target conf will be kept inside the target file

### ft_util_file-deploy

file-deploy Script

OPTION **NO-BACKUP** can be specified to avoid creating a backup

### ft_util_inc_var
### ft_util_log

Logging Script v1.1 Guilaume Hullin

the $LOG_DEBUG should be declared in the script which use ft_util_log in order to log debug message

the $LOG_FILE can also contains several path separated with space

### ft_util_sshauth

Credit: https://rumkin.medium.com/how-to-organize-ssh-keys-access-7b822db312a8

    ft_util_sshauth "<user>" "<usergroup>"

Will compile the authorized_keys files from files in authorized_keys.d/
If authorized_keys.d/ doesnt exist, the script will create it and exit
ft_util_sshkey v1.0 (2021-02-24) Guilaume Hullin

### ft_util_sshkey
