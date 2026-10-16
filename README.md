<img width="1272" height="588" alt="Screenshot 2026-10-16 042230" src="https://github.com/user-attachments/assets/9ee1abbe-d3c4-470d-a492-fb5ea3d96827" />

<img width="1002" height="680" alt="Screenshot 2026-10-16 042050" src="https://github.com/user-attachments/assets/0f2f5480-7de7-48e0-b679-367ef679caf1" />

<img width="1022" height="573" alt="image" src="https://github.com/user-attachments/assets/441a4024-5a37-457b-b395-aa77054d227a" />

Penjelasan aliran data (Main → CharacterManager → MainWindow)
Aliran data dimulai dari Main.java yang membuat data karakter beserta nama, tipe, dan levelnya, kemudian mengirimkannya ke CharacterManager untuk dikelola. CharacterManager bertugas menyimpan data karakter dan menyediakan data tersebut kepada MainWindow. 
Selanjutnya, MainWindow menampilkan daftar karakter secara dinamis menggunakan perulangan serta menghitung rata-rata level untuk ditampilkan pada JLabel statistik.
Dalam konsep MVC (Model-View-Controller), CharacterManager berperan mengelola data sebagai bagian dari Model,MainWindow berperan sebagai View, sedangkan Main menginisialisasi dan menghubungkan komponen aplikasi.


Nama :Assassin
Tipe :Assassin
Level: 40
Alasan pemilihan:Karakter dengan serangan cepat dan damage tinggi, sehingga diberikan level lebih tinggi daripada karakter awal.

Nama :Paladin
Tipe :Tank
Level:50
Alasan pemilihan:Karakter dengan pertahanan kuat dan kemampuan bertahan hidup tinggi, sehingga dipilih sebagai karakter dengan level tertinggi.
Kesimpulan: Penambahan Assassin level 40 dan Paladin level 50 membuat jumlah karakter menjadi lima. Level kedua karakter baru juga memengaruhi perhitungan rata-rata level secara otomatis,
sehingga statistik pada MainWindow akan diperbarui sesuai data yang dikelola oleh CharacterManager

https://1drv.ms/w/c/ACEA0258ECD9ACB9/IQCkgSEQK5ZMQLZTNUKrQsTPAcVjs1zjawx5umytOn84YhI?e=J58NMI
