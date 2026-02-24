# Shell Permissions Project

This repository contains shell scripts for learning about Linux file permissions, user management, and ownership.

## Scripts Description

| File | Description |
| :--- | :--- |
| **0-iam_betty** | Switches the current user to the user `betty`. |
| **1-who_am_i** | Prints the effective username of the current user. |
| **2-groups** | Prints all the groups the current user is part of. |
| **3-new_owner** | Changes the owner of the file `hello` to the user `betty`.|
| **4-empty** |A script that creates an empty file called `hello`.
| **5-execute** | A script that adds execute permission to the owner of the file `hello`.
| **6-multiple_permissions** | A script that adds execute permission to the owner and the group owner, and read permission to other users, to the file `hello`.
| **7-everybody** | A script that adds execution permission to the owner, the group owner and the other users, to the file `hello`.
| **8-James_Bond** | A script that sets the permission of the file `hello` to 007 (no permissions for owner and group, all permissions for others).
| **9-John_Doe** | A script that sets the mode of the file `hello` to 753 (-rwxr-x-wx).
| **10-mirror_permissions** | A script that sets the mode of the file `hello` to match the mode of the file `olleh`.
| **11-directories_permissions** | A script that adds execute permission to all subdirectories of the current directory.| **12-directory_permissions** | A script that creates a directory called `my_dir` with permissions 751.
| **13-change_group** | A script that changes the group owner to `school` for the file `hello`.
| **14-change_owner_and_group** | A script that changes the owner to `vincent` and the group owner to `staff` for all files and directories in the working directory.
| **15-symbolic_link_permissions** | A script that changes the owner and group owner of a symbolic link `_hello` to `vincent` and `staff`.
| **16-if_only** | This script changes the ownership of the file `hello` based on a specific condition. It demonstrates how to use the `--from` flag with the `chown` command to perform conditional ownership changes.
