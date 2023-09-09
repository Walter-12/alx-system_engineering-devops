This folder contains files with scriprs that perform different shell permissions
	0-iambetty switches current user to betty
	1-who_am_i prints username of current user
	2-groups returns all the groups the current user is part of
	3-new_owner changes owner of a file hello to user betty
	4-empty creates an empty hello file
	5-execute adds execute permission to owner of hello file
	6-multiple_permissions adds execute permission to owner and group owner and 		read permission to other users, to hello file
	7-everybody adds execution permission to owner, group owner and other user,		to  hello file
	8-James_Bond sets permissions of file hello as follows                      		Owner: no permission at all                                                         Group: no permission at all                      
            Other users: all the permissions
	9-John_Doe sets mode of file hello to:                                                  -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
	10-mirror_permissions sets mode of file hello same as olleh's mode
	11-directories_permissions adds execute permission to all subdirectories of 		the current directory for owner,group owner and other users
	12-directory_permissions creates a directory called my_dir with permissions 		751 in the working directory
	13-change_group changes the group owner to school for the file hello
	100-change_owner_and_group changes owner to vincent nad group owner to staff		for all files and directories in the working directory
	101-symbolic_link_permissions changes owner and group owner of _hello to     		vincent and staff respectively; _hello file is a symbolic link
	102-if_only changes owner of file hello to betty only if it is owned by user		guillaume
	103-star_wars plays StarWars IV episode in the terminal      
