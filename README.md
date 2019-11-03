# Ansible-FTPServer
Configure Anonymous FTP server

Task:
* `vsftpd.conf` is modified to allow anonymous FTP access and uploads
* Directory `/var/ftp/pub` is configured with the appropriate permissions
* Directory `/var/ftp/pub` is configured with the appropriate SELinux context label
* the SELinux boolean `ftpd_anon_write` is set to on

Create a playbook that ensures that the `vsftpd` service is installed, enabled, the firewall is opened, and the above requirements are met. Define variables in the playbook to set vsftpd.conf parameters, and use these in a template.

At the end of the playbook, verify connectivity, uploading the /etc/hosts file from localhost

# Instructor solution
The instructor's solution can be found in the solution folder