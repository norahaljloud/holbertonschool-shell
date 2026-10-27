# Permissions

- 0-iam_betty: Switches the current user to betty using su.
- 1-who_am_i: Prints the effective username of the current user using whoami.
- 2-groups: Prints all groups the current user belongs to using groups.
- 3-new_owner: Changes the owner of the file hello to the user betty using chown.
- 4-empty: Creates an empty file named hello in the current working directory using touch.
- 5-execute: Adds execute permission for the owner of the file hello using chmod u+x.
- 6-multiple_permissions: Adds execute permission for the owner and group, and read permission for others, on hello.
- 7-everybody: Adds execute permission for the owner group and other users on hello using chmod a+x.
- 8-James_Bond: Sets hello permissions to 007, giving all permissions to others and none to the owner or group.
- 9-John_Doe: Sets the permissions of hello to 753, giving the owner rwx, the group r-x, and others -wx.
- 10-mirror_permissions: Sets the permissions of hello to match the permissions of olleh using chmod --reference.
- 11-directories_permissions: Adds execute permission for the owner, group, and others to all subdirectories of the current directory without changing regular files.
- 12-directory_permissions: Creates a directory named my_dir with permissions 751 using mkdir -m.
- 13-change_group: Changes the group owner of the file hello to school using chown.
