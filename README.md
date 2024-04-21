## Reflection

### what is AMQP?
- AMQP (Advanced Message Queuing Protocol) adalah suatu protokol pengiriman pesan yang memungkinkan client untuk berkomunikasi dengan messaging middleware brokers. Jadi,ini adalah open standard application layer protokol yang memungkinkan client untuk berkomunikasi secara asinkronus dengan client lainnya melalui middleware. Hal ini dilakukan dengan mengirim dan menerima pesan.

### what it means? guest:guest@localhost:5672 , what is the first guest, and what is the second guest, and what is localhost:5672 is for?
- guest:guest merupakan username dan password yang digunakan untuk autentikasi dengan AMQP server. Di sini username dan passwordnya adalah guest yang merupakah default dari RabbitMQ saat instalasi.
- localhost:5672 merupakan hostmname dan nomor port dimana server AMQP berjalan.