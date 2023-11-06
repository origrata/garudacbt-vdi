# garudacbt-vdi

vdi ini merupakan cloud image dari aplikasi yang dikembangkan oleh https://garudacbt.github.io/cbt/
adapun, image ini sudah dioptimasi untuk kebutuhan ujian online bersama secara offline

Gunakan VirtualBox Versi 7.0

1. Download file ova nya dari  
https://drive.google.com/file/d/1ZxAL05jgC319ziHR_x6eQJpn18Ryg1D7/view?usp=drive_link 
2. file garudacbt-1.5.1.ova importkan ke virtualboxnya melalui menu file --> import Appliance
3. klik saja next sampai finish
5. untuk akses aplikasi gunakan IP komputer hostnya   username : admin
                                                 Password : admin123

6. Login OS 
username : garudacbt
password : garudacbt2023!

7. Monitoring Server Dengan Cockpit Berbasis WEB 
   https://host:9090

root akses sudo su 

password: garudacbt2023!

http://host/phpmyadmin            -----> untuk akses database
                                                username : root
                                                Password : garudacbtdb2023!
                                                
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
