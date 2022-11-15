Install the Linux Shell first:

1. Print working directory (pwd)
The pwd command prints your working directory. In other words, it outputs the path of the directory you are currently working in. There are two options: --logical to display your location with any symlinks and --physical to display your location after resolving any symlinks.
Linux shell: ------------------ write pwd <br/>
`` $ pwd ``

2. Make directory (mkdir)
Making directories is easy with the mkdir command. The following command creates a directory called example unless example already exists:
`` $ mkdir <directory name ``

3. Linux shell: cd <directory>
Linux shell: cd .. -----to remove the existing directory:

`` $ mkdir cd ``
`` $ cd .. ``
  
4. List (ls)
Coming from MS-DOS, I was used to listing files with the dir command. I don't recall working on Linux at the time, although today, dir is in the GNU Core Utilities package. Most people use the ls command to display the files, along with all their properties, are in a directory. The ls command has many options, including -l to view a long listing of files, displaying the file owner and permissions.
`` $ ls ``

5. Remove a file (rm)
Linux system provides rm and shred for data removal. To delete file example.txt, type the following:
`` $ rm example.txt ``
  
6. However, it's much safer to install a trash command, such as trashy or trash-cli. Then you can send files to a staging area before deleting them forever:
`` $ trash example.txt ``

7. Copy a file (cp)
Copy files with the cp command. The syntax is copy from-here to-there.
 `` $ cp filename1.txt filename2.txt `` 

8. Move and rename a file (mv)
`` $  mv file1.txt filename.txt `` 

9. Create an empty file (touch)
`` $ touch filename1.txt ``
 To open the file
 `` $ notepad filename1.txt ``

  10.  Change permissions (chmod)
  `` $ chmod +x myfile ``
