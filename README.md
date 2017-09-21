# Java Socket Example

Contoh penerapan socket dengan bahasa pemrograman Java yang terdiri dari 2 jenis yaitu server dan client.

Provider sebagai server yang membukan koneksi. Saat koneksi stabil maka client yang bernama Requester dapat mengirimkan data

Dalam contoh ini, client mengirimkan pesan "Hi my server". Untuk mengakhiri koneksi, client mengirimkan pesan "bye" dan server akan menjawab dengan pesan yang sama yaitu "bye". Maka koneksi akan berakhir dan server menunggu untuk koneksi baru.

Kedua program ini harus berjalan di mesin yang sama, kamu dapat mengganti alamat "localhost" dengan alamat ip yang kamu gunakan saat ini saat menjalankan server.


### Prerequisites

Yang dibutuhkan untuk menjalankan project ini:

```
Gradle 4.1
Java 8
```

## Authors

* **Karim Zerioh ** - *Initial work* - [Zerioh](http://zerioh.tripod.com/index.html)
* **rizupz** - *Forking*

## Reference
* [Understanding getinputstream and getoutputstream](https://stackoverflow.com/a/22564428)
* [What is InputStream & Output Stream? Why and when do we use them?](https://stackoverflow.com/questions/1830698/what-is-inputstream-output-stream-why-do-we-use-them-and-when-do-we-use-each) 
* [java DataOutputStream getOutputStream() getInputStream()](https://stackoverflow.com/questions/4913559/java-dataoutputstream-getoutputstream-getinputstream)
* [io buffers tutorial](https://stackoverflow.com/questions/4913559/java-dataoutputstream-getoutputstream-getinputstream)