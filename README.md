# Server
## Installieren

```
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install git-core
apt-get install  gnupg2
git clone https://github.com/thorstenkloehn/Server.git /Server
cd /Server
```
* [Rust](https://www.rust-lang.org/tools/install)
* [caddy](https://caddyserver.com/docs/install)
```
bash install.sh

```

## Mysql
```
wget -c https://dev.mysql.com/get/mysql-apt-config_0.8.16-1_all.deb
sudo dpkg -i mysql-apt-config*
sudo apt update
sudo apt-get install mysql-server

```
## Wordpress

```
sudo apt install php-fpm php-common php-mysql php-gmp php-curl php-intl php-mbstring php-xmlrpc php-gd php-xml php-cli php-zip


mkdir /wordpress
cd /wordpress
wget https://de.wordpress.org/latest-de_DE.zip

```
