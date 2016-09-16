# Proxmox-to-GDrive
Functions and order:

All backups go to here automatically:
/var/lib/vz/dump

Install Go using Apt-Get

Install rclone if uninstalled or update available
Can use Go to do this automatically

check for new backups
clone backups to Google Drive with rclone :http://wiki.linuxquestions.org/wiki/Rsync_with_Google_Drive
check if too many backups from a single VM
check if too many backups total
delete if too many backups from VM
delete if too many backups total
