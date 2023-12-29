Buatlah Sebuah Form yang nantinya akan menerima data berupa
- Nama Lengkap
- Asal Sekolah
- Nomor Telpon
- Email
- Password
- Konfirmasi Password
- Alamat Lengkap
- Gender
- Jenjang (SD/SMP/SMA)
- Pilihan Makanan Favorit bisa lebih dari 1. (Bebas makanannya opo wae)
- Pilihan Anime Favorit yang memuat value berupa poin rating => 1. Bocchi The Rock 7.0 , 2.Chainsaw Man 10.0, 3.One Piece 9.2
- File bukti upload twibbon
Data form akan dikirim dengan format parameter metadata :
metadata : {
    nama_lengkap,
    sekolah,
    telpon,
    email,
    password,
    alamat,
    gender,
    jenjang,
    makanan_fav,
    anime_fav,
    file_twibbon
}

Semua isian wajib diisi kecuali Asal Sekolah dan Makanan Favorit Opsional

Meta data akan dikirim ke sebuah handler beralamatkan https://api.tangkepin.com/data dengan method POST