# garudacbt-vdi

vdi ini merupakan cloud image dari aplikasi yang dikembangkan oleh https://garudacbt.github.io/cbt/
adapun, image ini sudah dioptimasi untuk kebutuhan ujian online bersama secara offline

1. Download file ova nya dari https://drive.google.com/drive/folders/1kJYoHioLOGe1619YEdewV5on6KOfV2dN?usp=share_link   dengan ukuran 2.1 GB
2. file garudacbt2023.v.1.ova importkan ke virtualboxnya melalui menu file --> import Appliance
3. klik saja next sampai finish
4. Perhatikan Settingan Pada Network Bridger Adapter, Pastikan Arah Bridgenya sama dengan ethernet yang terhubung ke router
   dengan Segment IP 192.168.1.0/24
5. untuk akses aplikasi gunakan 192.168.1.100    username : admin
                                                 Password : admin123

http://192.168.1.100/phpmyadmin            -----> untuk akses database
                                                username : root
                                                Password : garudacbtdb2023!
                                                
 
![image.png]( https://cloud.origrata.com/index.php/apps/files_sharing/publicpreview/7DREcKCFCG3BrDk?x=1366&y=307&a=true&file=garudacbt.jpg )

cara ganti network 
![image.png](
https://cloud.origrata.com/index.php/apps/files_sharing/publicpreview/fz4Ype6iwGmnPSJ?fileId=64897&file=/garudacbt1.jpg&x=1366&y=768&a=true)

![image.png](https://cloud.origrata.com/index.php/apps/files_sharing/publicpreview/fz4Ype6iwGmnPSJ?fileId=64898&file=/garudacbt2.jpg&x=1366&y=768&a=true)

![image.png](https://cloud.origrata.com/index.php/apps/files_sharing/publicpreview/fz4Ype6iwGmnPSJ?fileId=64899&file=/garudacbt3.jpg&x=1366&y=768&a=true)

setelah networknya dirobah
tekan 

ctrl + O => untuk menuliskan yang dirobah
ctrl + m => untuk menyimpan
ctrl + x => untuk keluar dari nano