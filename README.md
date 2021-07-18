# custom_linux_command
Custom Command for Linux Debain and Ubuntu Based System.
The Commands Includes -
  internsctl = Running "internsctl" with no flags will show the manual page to the user.

  internsctl --help	      	             = Shows this Help page.

  internsctl --version	 	               = Shows the version of the tool.

	internsctl cpu getinfo 	 	             = Shows the information about the CPU.

	internsctl memory getinfo 	           = Shows the information about the RAM.

	internsctl user create <username>      = Creates a new user on the system who can login to the system.

	internsctl user list 		               = Lists all the user present in the system.

	internsctl user list --sudo-only       = Lists all the user with 'sudo' permission.

	internsctl file getinfo <filename>     = Shows information about a file. 

	internsctl file getinfo [OPTIONS] <filename>
			OPTIONS:

			--size, -s          =   Shows size of the file.
			--permissions, -p   =   Shows the permission details of the file.
			--owner, -o         =   Shows the Owner of the file.
			--last-modified, -m =   Shows the Timestamp of last modification
