
<h1 align="center">Basic Linux/Unix Commands</h1>

- `!!`: _repeats your previous command_

- `cat`: _concatenate and print files_

    - flags with cat:-

        - `-b`: _Number the non-blank output lines(starting with 1)_

        - `-n`: _Number all output lines even the blank ones_

        - `-E`: _Display $ at end of each line_

- `cd`: _to go to a directory_

- `cd ..`: _go back_

- `chmod`: _to make a file executable_

- `clear`: _to clear the terminal_

- `cp`: _copy file to a location_

- `cut`: _allows to select fields_

  - flags with cut:-
    - `-d DELIM` or `--delimiter=DELIM`: _use DELIM as delimiter instead of TAB_
	
    - `-f FIELD_NUMBER[,FIELD_NUMBER_LIST]`: _select only these fields_
	
    - `-z`: _line delimiter is NUL not newline_

    - `-s`: _do not print lines not containing delimiters_

    - `--help`: _display help text and exit_

    - `--version`: _display version information and exit_

- `date`: _show current date/time_

- `df`: _to see available disk space in each partition of system_

- `dig domain`: _get DNS for domain_

- `du`: _to know the disk usage of a file in your system_

- `echo`: _to display line of text/string that are passed as an argument_
    - flags with echo:-

    - `-n`: _do not append a newline_

    - `-E`: _Explicitly suppress interpretation of backslash escapes_
    
- `exit`: _Close the terminal window or end the execution of a shell script_

- `find` : _to search for files in a directory hierarchy_

    - flags with find:-
    
        - `-inum N` : _Search for files with inode number ‘N’_
                
        - `-links N` : _Search for files with ‘N’ links_
        
        - `-print` : _Display the path name of the files found by using the rest of the criteria_
		
		- `-empty` : _Search for empty files and directories_

- `grep`: _to search a file for particular pattern of characters_

    - flags with grep:-
    
        - `-i`: _ignores the cases for matching_
        
        - `-n`: _display the matched line and corresponding line number_
        
        - `-r`: _recursively read all the files under each directory_

- `history`: _Display or manipulate the history list(history list contains the commands you have previously issued on terminal)_

    - flags with history:-
        - `-c`: _clear the history list_

        - `-w`: _write the current history to the history file_

        - `-r`: _read the history file and append contents to history list_

- `kill`: _to send a signal to process. by default, the message is sent as termination signal_

- `locate`: _locate a file in Linux system_

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

- `man`: _for showing the manual pages of a command_

- `mkdir`: _for creating a folder_

    - flags with mkdir:-

        - `-v`: _Print a message for each created directory_

        - `-p`: _No error if existing,make parent directories as needed_

- `mv`: _move file to a location_

- `netstat` : _to displays various network related information such as network connections, routing tables, interface statistics, masquerade connections, multicast memberships etc._

    - flags with netstat:-
    
        - `-a`: _To List All Network Ports_
        
        - `-at`: _To List All TCP Ports_
        
        - `-s`: _To Show Statistics for All Ports_
        
        - `-au`: _To List UDP Ports connections_
        
        - `-l`: _To List all LISTENING Connections_
        
        - `-tp`: _To Display Service name with PID_
        
        - `-g`: _To Display IPv4 and IPv6 Information_

- `nslookup`: _to get domain name or IP address_

- `ping`: _to check connection to your server_

- `pwd` : _to print current directory location_

- `reboot`: _reboot the system_

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
    
- `ssh -p port user@host`: _connect using port p_

- `ssh user@host`: _connect to host as user_

- `sudo`: _for command to be done in root or administrative privileges_

- `tail` : _to output the last part of files_

    - flags with tail:-
    
        - `-n` : _print last N number of lines_
                
        - `-f` : _for monitoring the file_
        
        - `-pid` : _Display the pid_

- `tar`: _used to compress and decompress various tar archives_

- `touch`: _create file_

- `uname -a`: _to show the system information_
     
- `uniq`: _report or omit repeated lines_

  - flags with uniq:-
    - `-c` or `--count`: _prefix lines by the number of occurrences_
	
    - `-i`: _ignore differences in case when comparing_
	
    - `-d`: _only print duplicate lines, one for each group_

    - `-u`: _only print unique lines_

    - `--help`: _display help text and exit_

    - `--version`: _display version information and exit_

- `uptime`: _show uptime_

- `wc`: _print line, word, and byte counts for file_

  - flags with wc:-
    - `-l` or `--lines`: _print the line counts_
	
    - `-c` or `--bytes`: _print the byte counts_
	
    - `-m` or `--chars`: _print the character counts_

    - `-L` or `--max-line-length`: _print the maximum display width_

    - `-w` or `--words`: _print the word counts_

    - `--help`: _display help text and exit_

    - `--version`: _display version information and exit_

- `wget -c file`: _continue stopped download_

- `wget -r url`: _recursively download files from url_

- `whereis`: _searches the paths of binary files, manual and sources for files matching the criteria provided_

  - flags with whereis:-
    - `-b`: _search only for binaries_
	
    - `-m`: _search only for manuals_
	
    - `-s`: _search only for sources_

    - `-h` or `--help`: _display help text and exit_

    - `-v` or `--version`: _display version information and exit_

- `which`: _searches for a command in the PATH and gives you the first one it finds_

  - flags with which:-
    - `-a`: _if commands with the same name exist in more than one path, specify the -a parameter so that which continues its search_

- `whoami`: _who are you logged as_
