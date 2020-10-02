
<h1 align="center">Basic Linux/Unix Commands</h1>

- `pwd` : _to print current directory location_

- `ls` : _to list contents of the current directory_

    - flags with ls:-
    
        - `-a`: _list all files including hidden ones (starting with '.')_
        
        - `--color`: _colored list[=always/never/auto]_
        
        - `-l`: _list with long format_
        
        - `-la`: _list long format along with hidden files_
        
        - `-lh`: _list long format with readable file size_
        
        - `-ls`: _list long format with file size_
        
        - `-r`: _list in reverse order_
        
        - `-R`: _list recursively directory tree_
        
        - `-s`: _list file size_
        
        - `-S`: _sort by file size_
        
        - `-t`: _sort by time & date_
        
        - `-X`: _sort by extension name_
        
        - `~`: _list user's home directory_
        
        - `-d */`: _list directories only_
        
        - `-d $PWD/*`: _list files and directories with full path_

- `cd`: _to go to a directory_

- `cd ..`: _go back_

- `touch`: _create file_

- `cp`: _copy file to a location_

- `mv`: _move file to a location_

- `locate`: _locate a file in Linux system_

- `cat`: _display contents of a file_

- `sudo`: _for command to be done in root or administrative privileges_

- `mkdir`: _for creating a folder_

- `rm`: _for deleting folder or file_

    - flags with rm:-
        - `-f, --force`: _ignore nonexistent files and arguments, never prompt_
        - `-i`: _prompt before every removal_
        - `I`: _prompt once before removing more than three files, or when removing recursively; less intrusive than -i, while still giving protection against most mistakes_
		- `--interactive[=WHEN]`: _prompt according to WHEN: never, once (-I), or always (-i); without WHEN, prompt always_
		- `--one-file-system`: _when removing a hierarchy recursively, skip any directory that is on a file system different from that of the corresponding command line argument_
	      - `--no-preserve-root`: _do not treat '/' specially_
	      - `--preserve-root`: _do not remove '/' (default)_
		  - `-r, -R, --recursive`: _remove directories and their contents recursively_
		  - `-d, --dir`: _remove empty directories_
		  - `-v, --verbose`: _explain what is being done_
		  - `--help`: _display this help and exit_
		  - `--version`: _output version information and exit_

- `man`: _for showing the manual pages of a command_

- `df`: _to see available disk space in each partition of system_

- `du`: _to know the disk usage of a file in your system_

- `tar`: _used to compress and decompress various tar archives_

- `uname -a`: _to show the system information_

- `chmod`: _to make a file executable_

- `ping`: _to check connection to your server_

- `clear`: _to clear the terminal_

- `dig domain`: _get DNS for domain_

- `wget -c file`: _continue stopped download_

- `wget -r url`: _recursively download files from url_

- `date`: _show current date/time_

- `uptime`: _show uptime_

- `whoami`: _who are you logged as_

- `ssh user@host`: _connect to host as user_

- `ssh -p port user@host`: _connect using port p_

- `reboot`: _reboot the system_

- `shutdown`: _shut down the system_

    - flags with shutdown:-
	- `--help`: _show help_
	
        - `--halt`: _halt the machine_
	
        - `--poweroff`: _power-off the machine_
	
        - `--reboot`: _Reboot the machine_
	
        - `-h`: _equivalent to --poweroff, overridden by --halt_
	
        - `-k`: _don't halt/power-off/reboot, just send warnings_
	
        - `--no-wall`: _don't send wall message before halt/power-off/reboot_
	
        - `-c`: _cancel a pending shutdown_
