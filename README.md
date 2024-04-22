### a. what is amqp?
AMQP adalah singkatan dari Advanced Message Queuing Protocol. Ini adalah protokol jaringan yang memungkinkan klien untuk berkomunikasi dengan broker pesan, yang memfasilitasi komunikasi yang terurut di antara aplikasi. AMQP didefinisikan sebagai protokol yang berbasis pada pertukaran pesan yang membuatnya sangat berguna untuk sistem yang memerlukan komunikasi antar layanan yang stabil dan efisien, seperti dalam aplikasi berbasis cloud dan microservices.

### what it means? guest:guest@localhost:5672 , what is the first guest, and what is the second guest, and what is localhost:5672 is for?
Bagian ini dari URL AMQP dapat dipecah menjadi beberapa komponen:
("guest" pertama) adalah username yang digunakan untuk mengakses broker pesan. Dalam hal ini, "guest" adalah username default yang sering digunakan dalam konfigurasi RabbitMQ yang dijalankan di lingkungan lokal.

("guest" kedua) adalah password yang digunakan bersama dengan username untuk autentikasi ke broker pesan. Password ini juga "guest" yang merupakan pasangan default untuk username di banyak broker pesan.

localhost:5672 adalah alamat server tempat broker pesan berjalan. "localhost" berarti broker pesan berjalan pada mesin lokal yang sama dengan klien yang mengaksesnya. Angka "5672" adalah port yang digunakan untuk mengakses RabbitMQ, yang merupakan implementasi dari AMQP.



