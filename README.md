# garudacbt-vdi

vdi ini merupakan cloud image dari aplikasi yang dikembangkan oleh https://garudacbt.github.io/cbt/
adapun, image ini sudah dioptimasi untuk kebutuhan ujian online bersama secara offline

1. Download file ova nya dari https://drive.google.com/drive/folders/1kJYoHioLOGe1619YEdewV5on6KOfV2dN?usp=share_link   dengan ukuran 1.4 Gb 
2. file garudacbt.ova importkan ke virtualboxnya melalui menu file --> import Appliance
3. klik saja next sampai finish
4. Perhatikan Settingan Pada Network Bridger Adapter, Pastikan Arah Bridgenya sama dengan ethernet yang terhubung ke router
   dengan Segment IP 192.168.1.0/24
5. untuk akses aplikasi gunakan 192.168.1.100    username : admin
                                                 Password : admin123

http://192.168.1.100/phpmyadmin            -----> untuk akses database
                                                username : root
                                                Password : garudacbtdb2023!
