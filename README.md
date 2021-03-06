* [Excellent Monitoring Sistem Menggunakan Bot Telegram](#excellent-monitoring-sistem-menggunakan-bot-telegram)
   * [Cara Install dan Join Excellent Monitoring Sistem](#cara-install-dan-join-excellent-monitoring-sistem)
   * [Cara Menggunakan Excellent Monitoring Sistem](#cara-menggunakan-excellent-monitoring-sistem)
      * [<strong>Lock Akun Spam</strong>](#lock-akun-spam)
      * [<strong>Penanganan Cluster Server 4 Excellent</strong>](#penanganan-cluster-server-4-excellent)
      * [<strong>Cek Antrian</strong>](#cek-antrian)
      * [<strong>Cek Isi Email Sender</strong>](#cek-isi-email-sender)
      * [<strong>Hapus Spam KAI</strong>](#hapus-spam-kai)
      * [<strong>Mengaktifkan Kembali Account Relay</strong>](#mengaktifkan-kembali-account-relay)
      * [<strong>Lock, Change Pass dan Hapus Antrian Pada EMS</strong>](#lock-change-pass-dan-hapus-antrian-pada-ems)
      * [<strong>Cek Service Pada Cluster</strong>](#cek-service-pada-cluster)
      * [<strong>Hapus Antrian Email Per Server</strong>](#hapus-antrian-email-per-server)
      * [<strong>Hapus Antrian Email Pada Cluster</strong>](#hapus-antrian-email-pada-cluster)
      * [<strong>Cek Antrian Pada EMS</strong>](#cek-antrian-pada-ems)
      * [<strong>Cek Service EMS</strong>](#cek-service-ems)
      * [<strong>Cek Account Lock</strong>](#cek-account-lock)
      * [<strong>Change Single Pass Pol</strong>](#change-single-pass-pol)


# Excellent Monitoring Sistem Menggunakan Bot Telegram
Excellent Monitoring Sistem menggunakan bot telegram digunakan untuk memantau antrian - antrian di cluster server yang dimiliki oleh excellent, dan ketika antrian penuh ada action yang harus dilakukan, action tersebut menggunakan bot telegram dan berikut adalah langkah langkah untuk dapat menggunakan excellent monitoring sistem bot telegram.
## Cara Install dan Join Excellent Monitoring Sistem 
1. Kontak team support untuk di joinkan ke grup **telegram excellent monitoring system**.
2. Setelah join coba jalankan perintah pertama ```/cekantrian@eik_marbot nama-klaster``` untuk mendapatkan akses ID.
![cluster](https://user-images.githubusercontent.com/56797161/126603715-5fdb5df6-30a2-49ac-aa6a-9b64f471136b.png)
4. Jika ID akses sudah didapatkan, infokan kepada team support untuk didaftarkan.
5. Jika ID sudah didaftarkan oleh team support, pendaftaran sudah berhasil dan selesai 

## Cara Menggunakan Excellent Monitoring Sistem
   - ### **Lock Akun Spam**
     - Jika ada akun yang didapatkan melakukan spam maka kamu dapat melakukan lock terhadap akun email tersebut dengan menggunakan script ```/spamclean@eik_marbot email-spam```.

   - ### **Penanganan Cluster Server 4 Excellent**
     - * Bot telegram monitoring system akan memberitahu jumlah antrian secara berkala di cluster server 4 excellent, jika jumlah antrian lebih dari 200, maka actionnya adalah clean antrian, bisa menggunakan script ```/clearsgln4@eik_marbot```

![clusterbaru4](https://user-images.githubusercontent.com/56797161/126750299-2b94a8db-4e75-4b2e-a38a-c669606ade0a.png)

   - ### **Cek Antrian**
     - Untuk cek antrian dapat menggunakan script ```/cekantrian@eik_marbot server_cluster```, dari perintah tersebut akan menampilkan 10 antrian terbanyak pada pada server cluster dan melihat informasi detail antrian melalui link yang sudah diberikan, dari detail link tersebut juga bisa dilihat untuk akun mana yang dicurigai sebagai spam, indikasinya jika 1 email antriannya lebih dari 20, dan mencari tujuan email yang alamat nya tidak jelas.

![clusterbaru1](https://user-images.githubusercontent.com/56797161/126746856-205618b6-8555-4ce2-bde9-be7435c51de5.png)

   - ### **Cek Isi Email Sender**
     - Setelah mendapatkan list antrian, kamu bisa melakukan cek isi email dari sender untuk mengecek apakah itu email spam atau bukan, kamu dapat menggunakan script ```/postcat@eik_marbot nama_cluster alamat_email```, dari sini juga kamu dapat mengecek tujuan email untuk alamat emailnya valid atau tidak, dan isi dari emailnya jelas/tidak.
![clusterbaru2](https://user-images.githubusercontent.com/56797161/126747455-d5a095c4-fb98-4e08-901d-c2bf9082affd.png)

![clusterbaru3](https://user-images.githubusercontent.com/56797161/126748536-193d95e7-08b1-4d28-a45c-d4183e401968.png)

   - ### **Hapus Spam KAI** 
     - Hapus spam KAI dapat menggunakan Script ```/kailockpass email-spam```

   - ### **Mengaktifkan Kembali Account Relay** 
     - Mengaktifkan kembali account relay dapat menggunakan script```/reactive@eik_marbot account-relay```

   - ### **Lock, Change Pass dan Hapus Antrian Pada EMS** 
     - Lock, Change Pass dan hapur antrian pada EMS dapat menggunakan script ```/lockpassems@eik_marbot nama_server nama_email```

   - ### **Cek Service Pada Cluster** 
     - Cek Service pada cluster  dapat menggunakan script ```/serviceems@eik_marbot nama_server service```

   - ### **Hapus Antrian Email Per Server** 
     - Hapus antrian email per Server dapat menggunakan script ```/pfdel@eik_marbot nama_cluster alamat_email```

   - ### **Hapus Antrian Email Pada Cluster**
     - Hapus Antrian email pada cluster dapat menggunakan script```/batchpfdel@eik_marbot alamat_email``` 

   - ### **Cek Antrian Pada EMS**
     - Cek antrian pada EMS dapat menggunakan script```/antrianems@eik_marbot nama_server``` 

   - ### **Cek Service EMS**
     - Cek Service EMS dapat menggunakan script```/serviceems@eik_marbot nama_server service```

   - ### **Cek Account Lock**
     - Cek account lock dapat menggunakan script```/ceklock@eik_marbot```

   - ### **Change Single Pass Pol**
     - Change single pass pol dapat menggunakan script```/polpass nrp``` 


## Terima kasih
