# Basic Commands For Linux 

* Echo - Print to Screen
* ls - List files & folders
* cd my_dir1 - change directory
* pwd - Present working directory
* mkdir new_directory - Make Directory
* cd new_directory; mkdir www; pwd - multiple commands
* mkdir -p /tmp/asia/india/bangalore - make directoy heirarchy
* rm -r /tmp/my_dir1 - remove directory
* cp -r my_dir1 /tmp/my_dir1 - Copy Directory
* touch new_file.txt - Create a new file (no contents)
* cat > new_file.txt - Add contents to file
* cat new_file.txt - View contents of file
* cp new_file.txt copy_file.txt - Copy File
* mv new_file.txt sample_file.txt - Move(rename) File
* rm new_file.txt - Remove(delete) File

# Vi Editor

* Command Mode and Insert Mode
* To escape from insert mode press esc
* To get into Insert mode press i 
* Move around is all the arrows or K, J, H, L
* Delete - X or dd
* Copy & Paste - yy or p
* Scroll Up/Down - Ctrl +u or Ctrl +d
* : Command
* :w Save
* :q Quit(discard)
* :wq Save+Quit
* /of Find press n key to go through occurrances 

# More Linux Commands

* User Accounts
* whoami
* id
* su aparna
* ls /root (ls: Cannot open directory /root: Permission Denied
* sudo ls /root 
* Download Files 
* curl insert URL -O Save-file.txt
* wget insert URL -O
* Check OS Version ls /etc/*release*
* cat /etc/*release*

# Package Management

* Centos uses RPM (Red hat package Manager)
* rpm -i telnet.rpm - Install Package
* rpm -e telnet.rpm - Uninstall Package
* rpm -q telnet.rpm - Query Package
* YUM - Uses RPM underneath and helps to install all dependant packages
* Sudo yum install -y ansible
* install a certain version of program - sudo yum install -y ansible-2.8.11

# Services 

* Service httpd start - Start HTTPD Service
* systemctl start httpd - Start HTTPD Service
* systemctl stop httpd - Stop HTTPD Service
* systemctl status httpd - Check HTTPD service status
* systemctl enable httpd - Configure HTTPD to start at startup
* systemctl disable httpd - Configure HTTPD to not start at startup
* Check the value for the directive ExecStartPre in the file /usr/lib/systemd/system/app.service 
* OR simply run the command - systemctl cat app.service and see the value.
