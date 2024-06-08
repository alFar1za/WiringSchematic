# WiringSchematic
Schematic Wiring Mobil -  Magang UASC -  High Voltage - Muhammad Akbar Alfariza

![image](https://github.com/alFar1za/WiringSchematic/assets/171551786/64baabe7-7b3a-4762-9813-74e026eab110)


![image](https://github.com/alFar1za/WiringSchematic/assets/171551786/e836e4f2-a4cb-4501-ae5a-c1e0f8835507)

Di rangkaian terdapat :
Baterai 72V yang merupakan Sumber daya utama untuk seluruh sistem. Dan wire (+) Terhubung ke 2 jalur yang pertama ke wire (+) untuk port charger battery dan terdapat dioda untuk mencegah aliran balik arus dari sistem ke baterai saat melakukan pengisian, lalu ke MCB ( Miniature Circuit Breaker) yang berfungsi untuk pengaman utama terhadap arus lebih yang dapat merusak komponen lain di dalam sistem, dan wire jg menyambung ke sistem High Brake yang dimana fungsinya untuk menyalakan sistem pengereman dan untuk mengaktifkan fitur lainnya seperti stoplamp pada mobil saat ditekan.

![image](https://github.com/alFar1za/WiringSchematic/assets/171551786/1a37d0f3-ae22-4ddf-b0ad-4369473a00eb)

Dapat kita lihat dari gambaran schematic di atas terdapat switch untuk Kontak Kunci yang dimana fungsinya untuk menghidupkan dan mematikan sistem. Saat kunci diputar, kontak akan menyalurkan daya dari baterai ke komponen lain seperti wirenya terhubung ke kaki (B+) pada microcontroller VOTOL EM100 dan Kaki Konverter (72V+), dan juga wire mcb terhubung ke kaki (B+) pada microcontroller. Pada kaki KONVERTER (12V+) terdapat switch yang berfungsi untuk STARTER dan terdapat fuse 10A lalu tersambug ke kaki CONTACTOR (12V+). Untuk kaki GND pada KONVERTER dan CONTACTOR yang akan terhubung melalui wire (-72V) pada battery lalu tersambung ke microcontroller pada kaki (B-). Kaki 5V CONTACTOR menjadi OUTPUT untuk CONTACTOR sendiri. Selanjutnya untuk kaki microcontroller (U) akan terhubung ke MOTOR (U), (W) pada MicroController terhubung ke (W) pada Motor. dan Kaki Microcontroller (V) akan terhubung juga ke kaki (V) pada MOTOR.

*Penjelasan*!
Konverter berfungsi untuk Mengubah tegangan 72V dari baterai menjadi 12V untuk mensuplai daya ke komponen lain yang membutuhkan tegangan lebih rendah.

Contactor berfungsi sebagai Sakelar elektromagnetik yang menghubungkan atau memutuskan aliran arus utama berdasarkan perintah dari sistem kontrol.

Cukup sekian penjelasan yang dapat saya jelaskan mengenai schematic wiring, CMIIW! Thank you ! :) 

