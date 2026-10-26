# WordPress Deployment on Ubuntu Server Using VMware Workstation

**Live Portfolio:** [Visit My IT Portfolio](https://jenisitportfolio.wordpress.com/)

**Project Documentation:** This repository documents the deployment of WordPress on an Ubuntu Server virtual machine using VMware Workstation. It includes implementation steps, screenshots, troubleshooting, and verification.

## Project Overview

This project demonstrates the deployment of WordPress in a virtualized Linux server environment. It covers virtual machine configuration, Ubuntu Server installation, web server setup, PHP installation, database services, WordPress configuration, and troubleshooting.

The project was completed as a hands-on IT home lab to strengthen practical skills in Linux server administration and web service deployment.

## Lab Environment

- **Host Operating System:** Windows 11
- **Virtualization Platform:** VMware Workstation
- **Server Operating System:** Ubuntu Server
- **Web Server:** Apache
- **Database Server:** MariaDB
- **Application Runtime:** PHP
- **Content Management System:** WordPress

## Implementation Steps

### 1. Virtual Machine Setup

Created an Ubuntu Server virtual machine in VMware Workstation and configured its virtual hardware and networking.

![VMware virtual machine settings](screenshots/Vm-Settings.png)

### 2. Ubuntu Server Installation

Installed Ubuntu Server and verified that the virtual machine booted successfully.

![Ubuntu Server installation](screenshots/2.png)

### 3. Apache Web Server Installation

Installed Apache to provide the web server required to host WordPress.

![Apache installation](screenshots/Apache2-install.png)

### 4. PHP Installation and Verification

Installed PHP and the required components to support WordPress. Verified the PHP installation.

![PHP installation](screenshots/PHP-install.png)

![PHP version verification](screenshots/PHP-version.png)

### 5. MariaDB Installation

Installed MariaDB to provide the database service required by WordPress.

![MariaDB installation](screenshots/Mariadb-Install.png)

### 6. WordPress Setup

Downloaded and configured the WordPress application files and accessed the WordPress installation page through a web browser.

![WordPress download](screenshots/Wordpress-Download.png)

![WordPress application files](screenshots/Wordpress-files.png)

### 7. Troubleshooting

Initially, the Apache default page appeared instead of the WordPress setup page. I investigated the issue and renamed the default `index.html` file so WordPress could load as the website's main page.

![Troubleshooting the Apache default page](screenshots/Troubleshooting.png)

### 8. Verification

Completed the WordPress installation, accessed the WordPress dashboard, and published a technical blog post to verify that the website was functioning.

![WordPress dashboard](screenshots/WordPressDashboard.png)

![Published WordPress blog post](screenshots/Blog-Post.png)

## Skills Demonstrated

- Linux server administration
- Virtual machine deployment and configuration
- Apache web server installation
- PHP installation and verification
- MariaDB database setup
- WordPress deployment and configuration
- Web application troubleshooting
- Technical documentation and screenshot evidence

## Project Outcome

Successfully deployed a working WordPress website on an Ubuntu Server virtual machine and documented the implementation process, including configuration steps, troubleshooting, and verification.

## Notes

This deployment runs in a local virtual lab environment. Access from outside the local environment would require additional hosting and networking configuration. The live portfolio linked above is hosted separately on WordPress.com.
