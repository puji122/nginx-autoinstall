# installnginx
```bash
siti ismayanti
```
# Indonesia local Repository
* Kambing.ui.ac.id debian7
```bash
debian 7 indonesia by kambing.ui.ac.id
deb http://kambing.ui.ac.id/debian/ wheezy main contrib non-free
deb http://kambing.ui.ac.id/debian/ wheezy-updates main contrib non-free
deb http://kambing.ui.ac.id/debian-security/ wheezy/updates main contrib non-free
```
# debian key 
* Error W: There is no public key available for the following key IDs
```bash
aptitude install debian-keyring debian-archive-keyring
apt-key update
apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 8B48AD6246925553
```
# Clone nginx on my repository
```bash
git clone https://github.com/puji122/nginx-autoinstall.git
cd nginx-autoinstall
chmod +x nginx.sh
chmod 755 nginx.sh
```
# install mysql - server
* Installation fix complete (y)
```bash
service mysql restart
mysql_secure_installation
Remove anonymous users? Y
Disallow root login remotely? Y
Remove test database and access to it? Y
Reload privilege tables now? Y
```
# Last install phpmyadmin
* At the time of install phpMyAdmin there are 2 choices of apache or httpd . Indeed, there is no option for nginx . 
* So choose (*)apache press key of space & (enter) .
```bash
configuring phpmyadmin
webserver to reconfigure automaticaly
chose 
* apache
then the contents of password for authentication with mysql
enter the same password with mysql
Access phpmyadmin in the browser
ipserver : 5555
```
<img src="https://github.com/puji122/nginx-autoinstall/blob/master/Untitled.jpg"/>
# ~GoOd LuCk~
* regards~PujiErmanto
