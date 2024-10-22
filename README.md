# Inheritance
<br>praktikum3</br>
<br>**Penjelasan**:</br>
Superclass ```Pegawai```: Kelas ini berisi atribut``` nama``` dan ```gajiPokok```, beserta method setter dan getter untuk masing-masing atribut. Kelas ini juga memiliki method ```cetakInfo()``` untuk menampilkan informasi dasar pegawai.

**Subclass** ```Manager```: Kelas ini mewarisi kelas```Pegawai```, dengan menambahkan atribut ```tunjangan```. Ada method setter dan getter untuk tunjangan, serta override method ```cetakInfo()``` untuk menampilkan informasi tunjangan.

**Subclass** ```Programmer```: Sama seperti ```Manager```, kelas ini mewarisi ```Pegawai```, dengan tambahan atribut ```bonus```. Setter dan getter disediakan untuk bonus, dan method ```cetakInfo()``` di-override untuk menampilkan informasi bonus.

Kelas **Main**: Kelas ini digunakan untuk menguji implementasi dengan membuat objek ```Manager``` dan ```Programmer```, lalu mencetak informasi masing-masing dengan memanggil method ```cetakInfo()```.
