# Basic Linux Commands Questions

# Question 1: Can you explain the basic difference between a GUI and a CLI in terms of running tasks on a Linux system?

  * Answer 1: Certainly! A GUI (Graphical User Interface) allows users to interact with a system using visual elements like windows, buttons, and icons.
  * It's more user-friendly and provides a graphical representation of tasks. On the other hand, a CLI (Command Line Interface) requires users to type commands to perform tasks.
  * While it may seem less intuitive at first, it's more efficient for automating tasks and working with remote systems.

# Question 2: Could you share some examples of tasks or workloads you've executed on Linux systems?

  * Answer 2: Of course! I've worked extensively with file management tasks, such as creating and deleting files and directories using commands like touch, mkdir, rm, and rmdir. Additionally,
  * I've used various commands like ls, cp, mv, and find to navigate and manipulate files.
  * I've also been involved in user management tasks, like creating and managing user accounts using commands such as useradd, usermod, and passwd.

# Question 3: How do you use the umask command, and why is it important for file permissions?

  * Answer 3: The umask command is used to set the default permissions for newly created files and directories.
  * It's essential for security and control over who can access and modify files.
  * The umask value subtracts permissions from the maximum possible permissions (typically 666 for files and 777 for directories).
  * For example, a umask value of 022 ensures that files will have permissions 644 and directories will have permissions 755 when created.

# Question 4: Describe how you'd create a symbolic link using the ln -s command. Why would you use symbolic links?

  * Answer 4: To create a symbolic link, I would use the ln -s command followed by the source file or directory and the desired name for the symbolic link.
  * For example, ln -s /path/to/source /path/to/link. Symbolic links are used to create shortcuts or references to files or directories.
  * They can be particularly useful for pointing to frequently accessed files or directories or for simplifying directory structures.

# Question 5: Can you provide an example of how you would change the permissions of a file using the chmod command?

  * Answer 5: Certainly! Let's say I have a file named myfile.txt and I want to give read and write permissions to the owner, read permissions to the group, and no permissions to others.
  * I would use the command: chmod 640 myfile.txt.

# Question 6: How do you use the useradd command to create a new user on a Linux system?

  * Answer 6: To create a new user using the useradd command, I would use the following syntax: sudo useradd username.
  * For example, sudo useradd john would create a new user named "john." By default, a user's home directory is also created at /home/username.

# Question 7: What is the purpose of the groupadd command, and how would you use it to create a new group?

  * Answer 7: The groupadd command is used to create a new group on the system. To create a new group named "developers,"
  * I would run the command: sudo groupadd developers. This group can then be used to manage user access and permissions for shared resources.

# Question 8: Explain how the passwd command is used and why it's important for user security.

  * Answer 8: The passwd command is used to change a user's password. Running passwd username allows the user (or an administrator) to set a new password.
  * It's crucial for user security because it enables users to maintain strong and regularly updated passwords, reducing the risk of unauthorized access to their accounts.

# Question 9: How do you use the ps command to list running processes, and what is its significance?

  * Answer 9: The ps command is used to list the currently running processes on a Linux system. When used without options, ps provides a snapshot of the processes running for the current user.
  * Adding options such as ps aux displays a more detailed list of all processes. It's a useful tool for monitoring system activity, diagnosing issues, and managing processes.

# Question 10: Could you provide an example of how you would use the df command to display disk space usage?

  * Answer 10: Certainly! To display disk space usage in a human-readable format, I would run the command: df -h.
  * This would show information about available, used, and total disk space on all mounted filesystems.

# Question 11: How would you use the du command to estimate the file space usage of a directory?
  
  * Answer 11: To estimate the file space usage of a directory, I would use the du -h command followed by the directory path.
  * For instance, du -h /path/to/directory would display a summary of the space used by that directory and its subdirectories in a human-readable format.

# Question 12: Explain the purpose of SSH keys and how they work.

  * Answer 12: SSH (Secure Shell) keys are used for secure authentication and communication between two computers, often for remote access.
  * They come in pairs: a public key and a private key. The public key is placed on the remote server, while the private key is kept by the user.
  * When the user attempts to log in, the server uses the public key to encrypt a message that can only be decrypted using the private key.
  * This provides a highly secure way of logging into a remote system without transmitting passwords over the network.





