## Apache Setup

Insalled Apache using sudo yum install httpd -y
Started Apache with: sudo 'systemctl start httpd'
Enable Apache on boot: 'sudo systemclt enable httpd'


## MariaDB Setup
Added MAriaDB repo manually for Amazon Linux 2023
Insalled MariaDb with: sudo dnf insalled -y MariaDB-server
Started MariaDB sudo systemctl start mariadb
Started with: sudo mysql_secure_installation

## PHP Setup
-Installed PHP using: sudo dnf install -y php php-mysql php-fpm
-Restarted Apache: 'sudo systemctl restart httpd' 
- Verified PHP is working by accessing index.php in browser
