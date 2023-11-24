# garudacbt-vdi

vdi ini merupakan cloud image dari aplikasi yang dikembangkan oleh https://garudacbt.github.io/cbt/
adapun, image ini sudah dioptimasi untuk kebutuhan ujian online bersama secara offline

Gunakan VirtualBox Versi 7.0

ip default VDI : 10.0.2.2 

webserver : nginx
php       : php7.4-fpm
Database  : mariadb

1. Download file ova nya dari  
https://drive.google.com/file/d/1ycH4S2ZGjcV5gHBX5KFnfPsDZeZgalJy/view?usp=sharing 
2. file garudacbt-1.5.2.ova importkan ke virtualboxnya melalui menu file --> import Appliance
3. klik saja next sampai finish
4. Untuk Network Gunakan topologi NAT network dengan ip local 10.0.2.0/24
   port forwarding
   ![image.png](https://cloud.origrata.com/index.php/apps/files_sharing/publicpreview/XLSjCdsRSSnst2f?x=1366&y=301&a=true&file=port%2520forwarding.jpg)
   
6. untuk akses aplikasi gunakan IP komputer hostnya   username : admin
                                                 Password : admin123

7. Login OS 
username : garudacbt
password : garudacbt2023!

root akses sudo su 

password: garudacbt2023!

http://ip_komputer_anda/phpmyadmin            -----> untuk akses database
                                                username : root
                                                Password : garudacbtdb2023!

http://ip_komputer_anda/filemanager/
                                                
 ![image.png]( https://cloud.origrata.com/index.php/apps/files_sharing/publicpreview/7DREcKCFCG3BrDk?x=1366&y=307&a=true&file=garudacbt.jpg )
 

cara ganti network 
![image.png](https://cloud.origrata.com/index.php/apps/files_sharing/publicpreview/fz4Ype6iwGmnPSJ?fileId=64897&file=/garudacbt1.jpg&x=1366&y=768&a=true)


![image.png](https://cloud.origrata.com/index.php/apps/files_sharing/publicpreview/fz4Ype6iwGmnPSJ?fileId=64898&file=/garudacbt2.jpg&x=1366&y=768&a=true)


![image.png](https://cloud.origrata.com/index.php/apps/files_sharing/publicpreview/fz4Ype6iwGmnPSJ?fileId=64899&file=/garudacbt3.jpg&x=1366&y=768&a=true)

setelah networknya dirobah
tekan 

ctrl + O => untuk menuliskan yang dirobah
ctrl + m => untuk menyimpan
ctrl + x => untuk keluar dari nano

ketik == >netplan apply

sudo init 6 => untuk restart VM
