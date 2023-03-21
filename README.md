#### Saya Ihsan Ghozi Zulfikar NIM 2103303 mengerjakan soal Latihan Praktikum 5 dalam mata kuliah DPBO untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin

### Kelas: Mahasiswa
* terdiri dari nim, nama, nilai, dan ras

### Kelas: Menu
* terdiri dari dtm, isUpdate, selectedID, dan listMhs;
fungsi pada kelas Menu:
* setTable: mereturn DefaultTableModel berdasarkan data listMhs
* insertData: menambahkan data baru pada listMhs
* updateData: mengedit data pada listMhs
* deleteData: menghapus data pada listMhs
* resetForm: menghapus isi form
* btnAddActionPerformed: handler tombol add/update
* tblMhsMouseClicked: handler tabel mahasiswa
* btnDeleteActionPerformed: handler tombol delete
* btnCancelActionPerformed: handler tombol cancel
* lain-lain

## Alur
1. Program menampilkan form (textFiled & comboBox), tabel mahasiswa, dan tombol add & cancel
2. User dapat mengisi form dan menekan tombol add untuk menambah mahasiswa pada tabel
- Jika data mahasiswa pada form belum lengkap namun user menekan add, muncul pesan "data gagal digambahkan"
![ss_add1](https://user-images.githubusercontent.com/100748074/226587001-2265167c-3a61-4829-88f5-f1ebba4a4be9.PNG)
- Jika data mahasiswa pada form sudah lengkap namun user menekan add, muncul pesan "data berhasil digambahkan"
3. User dapat mengklik mahasiswa pada tabel mahasiswa untuk memunculkan datanya pada form, mengubah tombol add menjadi update, dan memunculkan tombol delete
- Jika user mengklik tombol delete, prpogram memunculkan dialog delete?
![ss_del1](https://user-images.githubusercontent.com/100748074/226587569-8c160fc8-6946-4164-932a-b64b47dc5ec1.PNG)
- - Jika user memilih yes, maka mahasiswa akan dihapus dari tabel dan form akan dikosongkan
- - Jika user memilih no, maka kembali ke tampilan sebelum memencet tombol delete
- Jika user mengubah isi form dan mengklik update, maka data mahasiswa pada tabel akan berubah, tombol update menjadi add, tombol delete dihilangkan, dan form akan dokosongkan
- jika isi form belum lengkap, muncul pesan "data gagal diubah"
- Jika user mengklik cancel, maka form akan dikosongkan, tombol update menjadi add, dan tombol delete dihilangkan
