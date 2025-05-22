1. **Try to run one server, and three clients.**
![2.1](img/2.1.png)
Dari gambar, setiap kali satu klien mengirim pesan, server akan menangkapnya lalu melakukan broadcast ke semua klien yang terhubung, termasuk pengirimnya sendiri. Server bisa melakukan ini karena ia menyimpan daftar koneksi aktif dan terus memantau kedatangan pesan. Begitu pesan masuk, server langsung meneruskannya ke setiap koneksi dalam daftar.








