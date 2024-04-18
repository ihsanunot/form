Validasi terakhir yang didukung oleh browser secara bawaan adalah penentuan format data menggunakan regular expression (regex). 
Regex adalah pola yang untuk menentukan kombinasi karakter string yang tepat. Ada banyak sekali method yang mendukung regex, terutama method dari object String.

Namun, ada caranya sendiri jika ingin menerapkan regex dalam form field. Kita gunakan atribut pattern untuknya.

Contohnya, kita memiliki form control yang meminta user memasukkan username-nya. Umumnya, username memiliki aturan penulisan.

- Tidak diawali dengan angka.
- Tidak mengandung white space atau spasi.
- Tidak mengandung karakter spesial, seperti dolar ($).

Masih banyak aturan lainnya selain tiga di atas. Mari kita lihat contoh penerapan validasinya dalam formulir dengan regex.
