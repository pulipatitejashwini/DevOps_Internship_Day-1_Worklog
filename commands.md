# Linux Commands Used

# Installed Ubuntu Linux using: VM (EC2 Instance)
# Verified terminal access and login

ssh -i key.pem ubuntu@publicip  # login to VM

# Directory Navigation
# Used basic Linux commands:

pwd           # Shows present working directory
ls            # List all the files 
cd ~          # Change directory

# File & Directory Management
# Created and removed files/directories:

mkdir dir_files                 # Creates Folder
rm -r dir_files                 # Removes Folder
touch file1 file2 file3         # Creates File
rm file3                        # Removes File

# File Viewing & Editing
# Worked with file viewing and editors:

vim file1             # File Editor
cat file1             # View File
less file1            # View Large Files Easily
less +4 file1         # Starts Viewing from line 4
less +F file1         # Shows live updates

# File Permissions & Ownership
# Checked and modified permissions:

ls -l                           # List files and directories in large format
chmod U+X file1                 # gives execute permission to user
chmod o+w file1                 # gives write permission to others
# chown - sudo should be must, only sudo user has access to change ownership
sudo chown root:root file1      # changing user and group ownership to root for file
sudo chown -R root my_folder    # changing user ownership to root for folder 

# System Monitoring
# Basic system monitoring commands:

df -h         # Used to check disk space usage of file systems
free -m       # Used to check RAM usage
top           # Used to monitor system performance in real time
htop          # An advanced and user-friendly version of top

