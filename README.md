# SaguCulinary: Pengembangan Aplikasi Chatbot menggunakan Watson Assistant untuk memberikan informasi tentang makanan khas melayu dari sagu dikabupaten lingga

------------------------------
Deskripsi
-----------------------------------------------
Kuliner dari pohon sagu di Kabupaten Lingga menawarkan keunikan dan kelezatan yang mencerminkan kekayaan alam daerah tersebut. Kabupaten Lingga, yang terletak di Provinsi Kepulauan Riau, Indonesia, memiliki tradisi kuliner yang khas dengan menggunakan sagu sebagai bahan utama dalam beberapa hidangan tradisional.Kuliner dari pohon sagu Kabupaten Lingga menggabungkan cita rasa tradisional dengan keanekaragaman alam setempat. Kelezatan hidangan-hidangan ini mencerminkan keunikan budaya kuliner Kabupaten Lingga dan kekayaan alam yang melimpah dengan pohon sagu. Jika Anda berkunjung ke Kabupaten Lingga, mencoba kuliner dari pohon sagu adalah cara yang sempurna untuk menikmati keunikan kuliner setempat dan merasakan kelezatan tradisional yang memikat lidah.

-----------------------------------------
Alur 
-----------------------------------------
![User](https://github.com/phrzl/Capstone-projeck-IL/assets/95897478/3f04e125-fa40-4d9a-94ad-59e1654ba438)

----------------------------------------
Flow
----------------------------------------
1. Masuk ke akun IBM Cloud
2. Menggunakan watson Assisten 
4. Menggunakan twilio untuk memasukan URL Webhook ke WhatsApp with Twilio
5. Masuk ke Twillio dan masukan URL ke Sandbox Configuration
----------------------------------------
Komponen 
----------------------------------------

- https://www.ibm.com/products/watson-assistant : Buat, uji, dan gunakan bot atau agen virtual di seluruh perangkat seluler, informasi, atau bahkan di robot fisik.
- https://console.twilio.com/ : Konfigurasi URL Webhook WhatsApp ke dalam Twilio untuk memungkinkan pesan dikirim dan diterima melalui WhatsApp.

----------------------------------------
Impelenetasi 
----------------------------------------
Buka Dialog, dan kita akan melihat:

![Screenshot 2023-07-12 221121](https://github.com/phrzl/Capstone-projeck-IL/assets/95897478/748ceda1-c9bc-4daa-86d8-74ae0785fda7)

Setiap slot mewakili bidang yang akan diisi di chatbot: Beranda 

![Screenshot 2023-07-12 221432](https://github.com/phrzl/Capstone-projeck-IL/assets/95897478/21f16834-3f5b-458a-9ebb-186eedb3b62c)

setiap Dialog Berada memiliki intents : #beranda

![Screenshot 2023-07-12 221822](https://github.com/phrzl/Capstone-projeck-IL/assets/95897478/eca5c282-3f5a-4432-ae1e-bd8b99444100)


Setiap slot mewakili bidang yang akan diisi di chatbot: Tentang Kami

![Screenshot 2023-07-12 221529](https://github.com/phrzl/Capstone-projeck-IL/assets/95897478/a4b7e93d-5a87-416d-a8e5-395773660df6)

setiap Dialog Tentang kami memiliki intents : #Tentang kami

![Screenshot 2023-07-12 222017](https://github.com/phrzl/Capstone-projeck-IL/assets/95897478/5b548ff7-3aa9-4296-a0ae-5ca164ec3b1a)

Setiap slot mewakili bidang yang akan diisi di chatbot: Menu terdapat option 

![Screenshot 2023-07-12 222054](https://github.com/phrzl/Capstone-projeck-IL/assets/95897478/a5081ddd-c03d-4274-9b24-915ef2af123a)

setiap Dialog Menu memiliki intents : #Menu

![Screenshot 2023-07-12 222300](https://github.com/phrzl/Capstone-projeck-IL/assets/95897478/738f7817-3b2c-4915-9d3c-77880cd1c3bb)

setiap Dialog Menu memiliki My Entities : @Menu

![entities menu](https://github.com/phrzl/Capstone-projeck-IL/assets/95897478/865a798b-d4f7-4979-9a85-9eb2b611fc8a)

Setiap slot mewakili bidang yang akan diisi di chatbot: Harga

![dialog harga](https://github.com/phrzl/Capstone-projeck-IL/assets/95897478/d98d784f-79cd-4681-9d9a-2b6a26afac3d)

setiap Dialog Harga memiliki intents : #Harga

![intents](https://github.com/phrzl/Capstone-projeck-IL/assets/95897478/4004d6e2-7341-4685-9e3b-07203ccc2006)

setiap Dialog Harga memiliki My Entities : @Harga

![entities menu](https://github.com/phrzl/Capstone-projeck-IL/assets/95897478/413a15a9-1e7b-40bc-a16d-4aaea94f8002)


















































































