# Permissions

- `0-iam_betty`: Switches the current user to `betty`.
- `1-who_am_i`: Prints the effective username.
- `2-groups`: Prints the groups of the current user.
- `3-new_owner`: Changes the owner of `hello` to `betty`.
- `4-empty`: Creates an empty file named `hello` using the `touch` command.
- `5-execute`: Adds execute permission for the owner of `hello`.
- `6-multiple_permissions`: Adds execute permission for the owner and group, and read permission for others on `hello`.
- `7-everybody`: Adds execute permission for the owner, group, and others on `hello`.
- `8-James_Bond`: Sets the permissions of `hello` so the owner and group have none, while others have read, write, and execute.
- `9-John_Doe`: Sets the mode of `hello` to `753` (rwxr-x-wx).
- `10-mirror_permissions`: Sets the mode of `hello` to match the mode of `olleh`.
- `11-directories_permissions`: Adds execute permission for the owner, group, and others to all immediate subdirectories of the current directory.
- `12-directory_permissions`: Creates a directory named `my_dir` with permissions `751`.
- `13-change_group`: Changes the group owner of the file `hello` to `school`.
- `14-change_owner_and_group`: Changes the owner to `vincent` and the group owner to `staff` for all non-hidden entries in the current directory.
- `15-symbolic_link_permissions`: Changes the owner and group owner of the `_hello` symbolic link to `vincent` and `staff`.
- `16-if_only`: Changes the owner of `hello` to `vincent` only if its current owner is `guillaume`.
