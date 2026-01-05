File Creation
Creates a file named sample_data.txt in the home directory and writes sample content into it.

Hard Link Creation
Creates a hard link sample_hard.txt pointing to the same inode as sample_data.txt. Both files share the same data.

Symbolic Link Creation
Creates a symbolic (soft) link sample_soft.txt that points to the original file path.

Inode Verification
Displays the inode numbers of the files. The hard link shares the inode with the original file, while the symbolic link has a different inode.

File Metadata Inspection
Shows detailed information about sample_data.txt, including permissions, owner, size, and timestamps.

Disk Usage Check
Displays the total disk space used by the home directory in a human-readable format.

File Size Overview
Lists all files in the home directory with sizes in a human-readable format.

Link Deletion Test
Deletes the symbolic link sample_soft.txt and verifies that the original file sample_data.txt remains unaffected.

Disk Utility Demonstration
Uses du to show disk usage for each file/directory and df -h to display filesystem disk space usage in a human-readable format.
