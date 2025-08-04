# command-injection
✅ Suluhisho: Ku-install au kuhamisha DVWA
Hatua kwa hatua (Kali Linux/Debian):

    Nenda kwenye folder la web server:

cd /var/www/html

Angalia kama dvwa ipo:

ls

Kama hakuna dvwa, basi tuipakue.

Pakua DVWA kutoka GitHub:

sudo git clone https://github.com/digininja/DVWA.git dvwa

Weka permissions vizuri:

sudo chown -R www-data:www-data dvwa
sudo chmod -R 755 dvwa

Install dependencies (kama bado):

sudo apt install php php-mysqli mariadb-server git -y

Start Apache & MySQL tena:

sudo service apache2 restart
sudo service mysql restart

Browser:![Uploading Screenshot From 2025-08-04 14-55-45.png…]()


http://127.0.0.1/dvwa
