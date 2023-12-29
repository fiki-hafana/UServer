# UServer
OS Ubuntu Server 22.04 with Webserver + MultiPHP 
--------------------------------------------------------------------   
Prepared for web application developer to test their web system. Using this box will help web developer easy to manage and test their web. 

Requirements
--------------------------------------------------------------------
- Install [VirtualBox](https://www.virtualbox.org/)
- Install vagrant using the installation instructions in the [Getting Started document](https://developer.hashicorp.com/vagrant/tutorials/getting-started)
- Run `vagrant box add fikihafana/UbuntuWebserver22`
- Run `vagrant box init fikihafana/UbuntuWebserver22`
- Run `vagrant up` to start your box

Features of this box and WebServer Control Panel
--------------------------------------------------------------------
Web domains
--------------------------------------------------------------------
- Add multiple domains and quickly install apps on them.
- Nginx FastCGI cache support for Nginx + PHP-FPM
- Nginx Proxy cache support for Nginx + Apache2
- Per-domain TLS certificates for web domains
- MultiIP support for Web/Mail/DNS
- Support for PHP version 5.6 up to 8.2 with PHP8.2 as default

--------------------------------------------------------------------
DNS
--------------------------------------------------------------------
- Manage your own DNS server!
- Create your own nameservers
- Easy DNS cluster setup
- Support for DNSSEC on domains

--------------------------------------------------------------------
Mail
--------------------------------------------------------------------
- Host your own emails, no need to pay a business mail provider!
- Per-domain TLS certificates for inbound and outbound mail services (Exim 4, Dovecot, Webmail)
- SMTP relay setup for Exim in case port 25 is blocked by the provider
- Rate limit adjustable per user or email account
- Let’s Encrypt support for mail domains
- Latest version of Roundcube
- Optional SnappyMail installation

--------------------------------------------------------------------
Databases
--------------------------------------------------------------------
- From e-commerce to blogs, databases are always useful and you can choose between MySQL and PostgreSQL.
- Support for MariaDB 10.2 -> 10.11 with 10.11 as default
- Support for MySQL 8
- Support for PostgreSQL
- Latest version of phpMyAdmin and phpPgAdmin

--------------------------------------------------------------------
Server admin
--------------------------------------------------------------------
Ultra-configurable and user-friendly, This is as powerful as you could want. Automated backups to SFTP, FTP and via Rclone with 50+ Cloud storage providers


Login Details
--------------------------------------------------------------------
- SSH Port : 22
- SSH login : vagrant
- SSH Pass : vagrant
- Sudo Pass : not used / blank
- admin email : admin@localhost
- FQDN hostname : host.localhost.com

- WebPanel Port : 8083
- Web Admin URL:  https://127.0.0.1:8083 (do port forwarding)
- Username : admin
- Password : hestiacp


Donate if you like it, so we can add and test other projects
---------------------------------------------------------------------------------------------------
- BTC : 14Q3sA4iA1daGniK8nihunmkn92gayFh3S
- DOGE : D5rySM3uoDYga9smf3BZb3uJMQBCpcq3s9
- TRON (TRC20) : TNRUebvGMnFaXpoG6o6VJrpFWSw5p8N7rP
- ZIL : zil103ecrqkmkvsljj7lkqfwqgmjajx2vd8cpshpwk
- BNB (BEP20) : 0x219ce5217d9fe76b32a8d6b963f6d12942b558b9
