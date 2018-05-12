# xcodepandawastandardstable

X-code Pandawa Standard for Ubuntu 16.04 LTS v1.0.4 Stable
------------------------------------------

![alt text](http://xcode.or.id/04_small-logo.png)

Aplikasi untuk membangun NAT, DHCP Server, bandwidth managemen, access log, cache web, port forwarding, VPN Server, apache2, mysql-server, virtualhost, DNS Server & Samba secara cepat termasuk konfigurasinya. 

Cara menggunakan :
------------------

Pastikan di CPU anda sudah terinstall Ubuntu Server 16.04 dengan 2 LAN Card jika ingin dibangun router. Jika server aja, cukup 1 LAN Card.

Jika belum diinstall bisa download ISO-nya 

Dari release ubuntu

- http://releases.ubuntu.com/16.04/ubuntu-16.04.4-server-i386.iso (32 bit)

- http://releases.ubuntu.com/16.04/ubuntu-16.04.4-server-amd64.iso (64 bit)

Dari kambing (Indonesia)

- http://kambing.ui.ac.id/iso/ubuntu/releases/16.04.4/ubuntu-16.04.4-server-i386.iso (32 bit)

- http://kambing.ui.ac.id/iso/ubuntu/releases/16.04.4/ubuntu-16.04.4-server-amd64.iso (64 bit)

Perintah instalasi dan menjalankannya
-------------------------------------

- Download : 

- git clone https://github.com/kurniawandata/xcodepandawastandardstable

- cd xcodepandawastandardstable

- chmod -R 777 *

- ./xcoderouter (untuk router)

- ./xcodeserver (untuk server)

Perbaikan dari v1.0.0 ke 1.0.1
---------------------

- Instalasi dengan deb dihapus, cukup menggunakan git clone sehingga jika ada bug bisa cepat diperbaiki

- Instalasi X-code Pandawa dimasukkan juga langsung setting ip, sehingga setelah restart, langsung bisa digunakan ip-nya

- Penambahan informasi tentang penggantian nama enp0s3 ke eth0

- rc.local tidak ditambahkan tapi disalin dari direktori support, sehingga semakin memudahkan untuk reset rc.local ke awal untuk mendukung x-code pandawa 

Perbaikan dari v1.0.1 ke 1.0.2
---------------------

- Penambahan fitur DHCP Leases

Perbaikan dari v1.0.2 ke 1.0.3
---------------------

- Fitur DHCP Leases (Real time)


Support gratis
--------------

- Training X-code pandawa standard gratis di Jogja : http://xcodetraining.com/xcodepandawa 

- Group whatsapp, untuk bergabung, kontak Lina :  0813 9388 2080

Progammer 
---------

- Programmer : Kurniawan. xcode.or.id. trainingxcode@gmail.com

Donasi
------ 

- Bagi yang ingin donasi dapat kontak Lina : Phone / whatsapp : 0813 9388 2080 

License
------- 

- GNU General Public License 
