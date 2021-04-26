# belajar-dasar-backend-dicoding
Penggunaan bahasa pemrograman nodeJS dengan framework Hapi, dan penggunaan dependency ESLint agar penulisan code menjadi serumpun.
Video pelaksaannya dapat dilihat di https://youtu.be/E6fYSknOW-E

**Kriteria Submission:**
Kriteria 1 : API dapat menyimpan buku
Kriteria 2 : API dapat menampilkan seluruh buku
Kriteria 3 : API dapat menampilkan detail buku
Kriteria 4 : API dapat mengubah data buku
Kriteria 5 : API dapat menghapus buku
Tambahkan fitur query parameters pada route GET /books (Mendapatkan seluruh buku).
?name : Tampilkan seluruh buku yang mengandung nama berdasarkan nilai yang diberikan pada query ini. Contoh /books?name=”dicoding”, maka akan menampilkan daftar buku yang mengandung nama “dicoding” secara non-case sensitive  (tidak peduli besar dan kecil huruf).
?reading : Bernilai 0 atau 1. Bila 0, maka tampilkan buku yang sedang tidak dibaca (reading: false). Bila 1, maka tampilkan buku yang sedang dibaca (reading: true). Selain itu, tampilkan buku baik sedang dibaca atau tidak.
?finished : Bernilai 0 atau 1. Bila 0, maka tampilkan buku yang sudah belum selesai dibaca (finished: false). Bila 1, maka tampilkan buku yang sudah selesai dibaca (finished: true). Selain itu, tampilkan buku baik yang sudah selesai atau belum dibaca.
Menerapkan CORS pada seluruh resource yang ada.
Menggunakan ESLint dan salah satu style guide agar gaya penulisan kode JavaScript lebih konsisten.
