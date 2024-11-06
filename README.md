<p align="center">
<img src="https://imgur.com/ADnTh6c.png" height="60%" width="75%">
</p>

<h1>Linux-File_Permissions</h1>
understanding and manipulating file permissions in Linux. This is essential knowledge in Linux for securing files and directories.<br />


<h2>Environments and Technologies Used</h2>

- GoogleLab
- Virtual Machine
  

<h2>Operating Systems Used </h2>

- Windows 11</b> (21H2)

<h2>Check file and directory details</h2>

<p>
<img src="https://imgur.com/IatK7c2.png" width="80%">

</p>
<p>
To view permissions and details of files and directories, use commands like ls -l or stat. These commands reveal important information, such as the permissions string, owner, group, and last modification time. 
ls -la reveals hidden files these files are identified with a (.) in front of the file.
</p>
<br />

<h2>Describing the Permissions String</h2>
<p>
<img src="https://imgur.com/KQJkB3q.png" height="80%" width="80%">
</p>
<p>
Linux permissions strings (e.g., drwxr-xr-x) show the access levels for files and directories. The string is divided into three groups for the users, group, and others, each indicating read, write, and execute permissions.
</p>
<br />

<h2>Change File permissions</h2>
<p>
<img src="https://imgur.com/W9L86jE.png" height="80%" width="80%">
</p>
<p>
The chmod command allows changes to file permissions. Permissions can be set using symbolic (e.g., chmod u+x) and file you want to change permissions to (e.g., project_k.txt)
</p>
<br />


<h2>Change File Permissions on a Hidden File</h2>
<p>
<img src="https://imgur.com/RebZbfz.png" height="80%" width="80%">
</p>
<p>
Hidden files, which start with a dot (.), can have their permissions adjusted using chmod just like regular files. This is important for securing hidden configuration files within directories. (e.g., .project_x.txt)
</p>
<br />

<h2>Change Directory Permissions</h2>
<p>
<img src="https://imgur.com/8pM6j3B.png" height="80%" width="80%">
</p>
<p>
Changing directory permissions with chmod affects access to the contents of the directory. Directory permissions control whether users can view, create, or execute files within the directory. for example (e.g., chmod g-r,g-w drafts)
<br />

<h2>Summary</h2>
<p>
</p>
<p>
Understanding and managing Linux file permissions is crucial for system security. By controlling file access through permissions, users can protect sensitive files and data effectively.
<br />
