### Pendahuluan
Ini Merupakan Script Bash Untuk Menginstall Beberapa apps untuk server raspberrypi, yaitu list apps nya
* Nginx
* PHP7.0
* Mysql
* phpMyAdmin
* vsftpd

Dan Beberapa Edit Konfigurasi yaitu :
* edit /etc/nginx/sites-available/default
* edit conf /etc/nginx/nginx.conf
* edit /etc/rc.local > dengan add /etc/init.d/ssh start agar ssh aktif secara otomatis
* edit /etc/php/7.0/fpm/php.ini
* edit .bash_history

OS Server Tested : Saya Menggunakan Debian 9 Stretch, Mungkin bisa digunakan untuk Ubuntu 16.04 - 17.10
dan versi tingkat atas nya,

### Instalasi 
Persiapan Sebelum Instalasi, Install dahulu git dengan <code>sudo apt-get install git</code>
Setelah Itu  :

1. instalasi cukup dengan <code>git clone https://github.com/rifkytech/nginx.git</code>
2. Kemudian <code>cd nginx</code>
3. setelah itu <code>chmod 777 install</code>
4. nah selesai, untuk install nginx nya, cukup dengan perintah <code>./install</code>


Jika Ada Error Perintah, mohon segera hubungi saya@rifky.tech
