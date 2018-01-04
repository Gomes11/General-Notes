# Linux

## General Notes
# TODO

## Essential Configurations
- `.bash_profile`
Is the file where all the user configuration files are called. One of the examples is the .bashrc file.
- `.bashrc`
Is the file that usually contains the user configurations and aliases for the current user session. It is normally located under '$HOME' or '/root/'

## Essential Directories
- `/home/`
It is the user directory. Usually identified by the environemnt variable $HOME
- `/root/`
It is the root dirctory. Usually serves the purpose of storing everything that requires root permissions to get into. When a user is granted root access, the default directory is this one.
- `/bin/`
It is the directory that contains the essential command binaries that need to be available in single user mode (e.g., cat, ls, cp, etc). It is available for all users.
- `/sbin/`
It is the directory that contains the essential system binaries (e.g., init, ip, mount, etc)
- `/usr/bin/`
It is the directory that contains the non-essential command binaries, that is the commands that are not needed in single user mode. It is avaialable for all users.
- `/usr/sbin/`
It is the directory that contains the non-essential binaries, such as the deamons for the several network devices.
- `/usr/local/`
It is a tertiary hierarchy that is destined for local data, specific to the current host. Typically it has further subdirectories such as /bin/, /lib/, /share/, etc...

## TODO: Complete further sections
