# ultimate-bash-additions

This is an archive of all bash customizations.

### Utility Scripts

- [comic_rpacker](utilities/comic_repacker) - This script reads a ZIP archive, converts the supported files to PNG, and then repackages them as CBR.

### Bash Functions

- [ssh_key_setup](bash_functions/ssh_key_setup) ssh_key_setup
  - [gitkeyadd](bash_functions/ssh_key_setup#gitkeyadd) - Adds git SSH Key to current SSH Agent, sets up for SSH Agent if one is not already running.
  - [gitkeydel](bash_functions/ssh_key_setup#gitkeydel) - Removes key from SSH Agent.
- [check_and_source](bash_functions/check_and_source) - sources a file if exists.
- [add_to_path](bash_functions/add_to_path) - Special function to add paths Cleanly



> [!NOTE]
> All scripts are written for bash 5.1.16(1) and python 3.10.XX.
