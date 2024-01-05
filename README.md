File code untuk tugas SRO berkaitan dengan mobile robot untuk line following menggunakan infrared.

Nama: Anak Agung Maharaja Adhisthanaya Indrawan
NRP: 5022211239

Komponen yang digunakan:
1. Raspberry Pi 4 Model B
2. Arduino Uno R3
3. Arduino Shield
4. Infrared Sensor (2 pcs)
5. DC Motor (2 pcs)
6. Body Robot
7. Powerbank (Source)

Raspberry Pi menggunakan powerbank sebagai power source dan Raspberry pi juga bertindak sebagai ROS. Ini menggunakan rosserial. Raspberry pi dan Arduino tersambung menggunakan kabel USB dan Arduino shield langsung masuk ke socket yang telah ada di Arduino. 
Sensor infrared tersambung ke Arduinno untuk mendapatkan nilai treshold dari hitam dan putih sesuai dengan environment robot (dikalibrasi). Arduino telah diberikan input kode untuk publish sensor kanan dan kiri sehingga user dapat melihat data yang dilihat dari sensor.
Ketika sensor detect garis hitam, maka itu akan berdampak ke pergerakan DC motor dan sesuai dengan yang telah diberikan nilai input dari sensor infrared.

Video YouTube: https://youtu.be/MfktvyXe47A
