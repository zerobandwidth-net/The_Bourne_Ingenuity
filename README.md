## The Bourne Ingenuity ##

This repository is a collection of scripts, functions, samples, and other hacks for working in the bash (Bourne Again SHell) environment.

* `/android_hacks/adb_backup`
    * Creates a backup of an Android device that is connected over ADB. Root access to the device is not required, but the target package must explicitly allow backups in its Android manifest.
* `/bash_function_demos/func_get_local_path`
    * A function to get a file path as input from the user, and store it in a session variable.
* `/bash_function_demos/func_print_padded_text`
    * A function to print a status message -- that is, a line with a message left-justified at the beginning and some status token in brackets on the right.
* `/doihave`
    * _(Debian-based systems only)_ Uses `dpkg` to check the installation status of any package whose name includes the input argument.
* `/git_hacks/func_ensure_repo_contents`
    * A function to ensure that a target path contains the contents of a specific Git repository.
* `/git_hacks/git-mkbranch`
    * A script to create a local Git branch, push it to the remote repo, and ensure that the local and remote branches are linked.
* `/git_hacks/gitloc`, `/git_hacks/wgr`, `/git_hacks/wgb`
    * Scripts that display information about whether the current path is controlled by Git. These may be used as scripts or functionized so that they're available in every session. See also `/sample_bashrc/bash_functions`.
* `/sample_bashrc/bashrc`, etc.
    * A sample `.bashrc` which organizes several common session-init tasks into discrete supporting files.


* 
