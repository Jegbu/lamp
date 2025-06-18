##Apache Setup -EC2 Test!#

Insalled Apache using sudo yum install httpd -y
Started Apache with: sudo 'systemctl start httpd'
Enable Apache on boot: 'sudo systemclt enable httpd'


## MariaDB Setup
Added MAriaDB repo manually for Amazon Linux 2023
Insalled MariaDb with: sudo dnf insalled -y MariaDB-server
Started MariaDB sudo systemctl start mariadb
Started with: sudo mysql_secure_installation 
