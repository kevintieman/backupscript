# backupscript

Script to backup config from network devices, using the native ansible module. 
Also uses the shell module to initiate the push to the repository, this implies
that git config is needed in the ./config_backups/ directory.
