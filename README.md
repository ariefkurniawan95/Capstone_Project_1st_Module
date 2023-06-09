# Capstone Project
## Data Nilai Siswa (Sistem Akademik Terpadu Purwadhika)
### Capstone project data nilai siswa dibuat menggunakan bahasa pemrograman python. 

<br>


## <li>Latar Belakang</li>

<text text-align: center> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Tujuan dari aplikasi Data Nilai Siswa (Sistem Akademik Terpadu Purwadhika) adalah untuk mengelola  nilai siswa. Fitur utama yang terdapat pada aplikasi ini adalah dapat melakukan fungsi  CRUD (Create, Read, Update dan Delete) terhadap nilai-nilai siswa. Collection Data Types yang digunakan untuk menyimpan nilai siswa adalah dictionary dalam list. <br>
  Menu yang dapat diakses pada aplikasi ini adalah sebagai berikut ini :
  <br>
  <img src="https://user-images.githubusercontent.com/103922811/241995327-06690fce-5927-40cb-ba6e-1b58d41a55b2.png" width="500"/> 
  <br></br>
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Program flow yang terdapat pada aplikasi ini adalah seperti gambar berikut ini :
  <img src="https://user-images.githubusercontent.com/103922811/242028082-55fb53fa-e130-4157-b6c2-9720d4ca334a.png" width="750"/> 
  </text>
<ol>
    <b><li>Menambah Nilai Siswa</li></b>
    <text text-align: center;>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Pada menu ini, dengan memilih menu nomor 1, user dapat menambahkan nilai siswa. Apabila student belum terdaftar maka pengguna dapat memilih menu no 2 untuk mendaftarkan studentnya terlebih dahulu. Opsi nomor 3 dipilih apabila ingin kembali ke menu utama. Untuk memasukkan nilai siswa, pengguna perlu menginput NIS terlebih dahulu, apabila student (NIS) belum terdaftar, maka nilai tidak dapat diinput. Jika student sudah terdaftar, maka tahapan berikutnya adalah memvalidasi apakah student tersebut sudah memiliki nilai pada semester tersebut atau belum. Jika nilai pada seemester yang ingin diinput telah terisi, maka pengguna tidak dapat melakukan input nilai pada database.
      <br>
      <img src="https://user-images.githubusercontent.com/103922811/241999207-c4cd39e8-cf0f-427a-8a45-019235df500b.png" width="700" height="165" /> 
      <br>
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Berikut adalah tampilan apabila pengguna berhasil memasukan nilai ke dalam <i>database</i>.
      <br>
        <img src="https://user-images.githubusercontent.com/103922811/242000154-9a605d9d-f85a-40ea-b368-4a183ad80be3.png" width="500"/> 
  </text>
     <b><li>Menampilkan Nilai Siswa</li></b>
  <text>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Selain dapat menginput nilai siswa, aplikasi ini juga dapat menampilkan nilai siswa. Nilai  siswa dapat ditampilkan secara keseluruhan (Menampilkan nilai seluruh semester) atau dapat memilih nilai pada semester tertentu saja. 
    <br></br>
    <img src="https://user-images.githubusercontent.com/103922811/242000342-ebb925aa-a71f-4f81-a430-bf90a0faa7c1.png" width="700" height="125"/>
  Proses validasi yang terjadi yakni sama, pertama-tama pengguna harus memasukkan NIS yang ingin ditampilkan nilainya. Sistem akan mengecek terlebih dahulu apakah student terkait sudah terdaftar atau belum. Jika student terdaftar maka akan masuk ke tahapan berikutnya yakni mengecek apakah nilai pada semester yang ingin ditampilkan tersedia atau tidak. Berikut adalah tampilan pada saat sistem menampilkan nilai seluruh semester dan juga nilai pada semester tertentu.
  <br></br>
  Tampilan pada saat sistem menampilkan seluruh nilai siswa pada seluruh semester.
  <img src="https://user-images.githubusercontent.com/103922811/242000658-064fb816-5772-48c0-8e55-c2aedd41a2a1.png" width="700" height="375"/>
   <br></br>
  Tampilan pada saat sistem menampilkan nilai pada semester tertentu.
  <img src="https://user-images.githubusercontent.com/103922811/242001092-ff720d58-0269-404b-868b-8726c26743a3.png" width="700" height="145"/>
  </text>
<b><li>Memperbaharui Nilai Siswa</li></b>
  <text>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Pada menu ini, pengguna dapat memperbaharui nilai siswa baik seluruh nilai dalam suatu semester tertentu atau hanya satu pelajaran saja. Apabila seluruh nilai dalam suatu semester berarti nilai yang akan terupdate adalah nilai matematika, fisika, kimia dan biologi. Apabila menggunakan opsi perbaharui satu pelajaran, maka nilai yang akan terupdate hanya 1 pelajajran saja. Berikut adalah tampilan sub menu untuk memperbaharui nilai siswa.
  <br></br>
  <img src="https://user-images.githubusercontent.com/103922811/242002383-452eb863-5e3c-4179-a5b7-90ab08084099.png" width="700" height="115"/>
  <br></br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Jika pengguna berhasil memperbaharui nilai, maka akan muncul notifikasi bahwa data telah berhasil diperbaharui. berikut ini merupakan tampilan apabila data telah berhasil diperbaharui.
  <br></br>
  Tampilan Untuk Salah Satu Nilai Pelajaran Yang Berhasil Diperbaharui
  <img src="https://user-images.githubusercontent.com/103922811/242020371-3874d687-4c19-45ad-b708-267d3af68035.png" width="700" height="400"/>
  <br></br>
  Tampilan Untuk Seluruh Nilai Pada Satu Semester Yang Berhasil Diperbaharui
  <img src="https://user-images.githubusercontent.com/103922811/242021230-7009537b-bf6b-42d5-bd06-0407a6f4b151.png" width="700" height="400"/>
  </text>
  <b><li>Menghapus Nilai Siswa</li></b>
  <text>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Pada aplikasi ini, pengguna dapat menghapus 2 hal yakni nilai per semester siswa dan juga data siswa secara keseluruhan. apabila nilai per semester yang dihapus maka nilai seluruh pelajaran pada semester yang dipilih akan terhapus. jika data siswa yang dipilih maka baik NIS, Nama ataupun seluruh nilai yang sudah didaftarkan akan terhapus. Berikut adalah tampilan menu navigasi pada bagian menu menghapus nilai.
  <br></br>
  Tampilan menu navigasi pada halaman menghapus nilai siswa.
<img src="https://user-images.githubusercontent.com/103922811/242006613-4f9c3b3d-de5c-4594-92d3-74f18f31931b.png" width="700" height="140"/>
<br></br>
setelah memilih menu apakah akan menghapus nilai per semester atau data siswa, pengguna akan diminta verifikasi kembali apakah benar akan menghapus data nilai ataupun data siswa. Berikut adalah tampilan baik menghapus nilai per semester atau menghapus data siswa.
 <br></br>
 Tampilan menu navigasi pada halaman menghapus nilai siswa
 <img src="https://user-images.githubusercontent.com/103922811/242006902-1674373b-5b6c-4d95-bfed-3a5c2da43444.png" width="700" height="400"/>
  <br></br>
   Tampilan menu navigasi pada halaman menghapus data siswa
 <img src="https://user-images.githubusercontent.com/103922811/242006708-4afa636c-9419-4b66-bfe7-1cb52d79f753.png" width="700" height="140"/>
<br></br>
</text>
<br></br>
    <b><li>Menambah Data Siswa</li></b>
    <text>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Berikut adalah fitur untuk menambahkan data siswa. Pada menu ini pengguna dapat mendadftarkan Nomor Induk Siswa(NIS) dan juga nama lengkap siswa. Apabila data berhasil ditambahkan maka akan muncul notifikasi bahwa data siswa telah berhasil ditambahkan.
Berikut adalah tampilannya:
  <br></br>
<img src="https://user-images.githubusercontent.com/103922811/242007247-add25a95-b5d3-4e08-8efc-6709d43af49f.png" width="700" height="140"/>
<br></br>
    </text>
   <b><li>Menampilkan Data Siswa</li></b>
   <text>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Menampilkan data siswa merupakan fitur terakhir yang ada pada aplikasi ini. pada menu ini pengguna dapat mengurutkan data siswa berdasarkan NISnya baik secara descending maupun ascending. Berikut adalah tampilannya menu dan hasil sortingnya. 
 <br></br>
<img src="https://user-images.githubusercontent.com/103922811/242007382-4e0ef905-6c46-469e-be83-629664d0d5b1.png" width="700" height="140"/>
<br></br>
Berikut adalah tampilan mengurutkan siswa secara ascending berdasarkan NISnya.
<img src="https://user-images.githubusercontent.com/103922811/242007525-e543ab9f-5003-49b7-aea7-e37ea0a07c60.png" width="700" height="140"/>
<br></br>
dan berikut merupakan tampilan mengurutkan siswa secara descending berdasarkan NISnya.
<img src="https://user-images.githubusercontent.com/103922811/242007653-7bb348be-9b83-4df2-ba94-721301a2635b.png" width="700" height="140"/>
</text>
<b><li>Exit</li></b>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; pada navigasi yang terakhir ini, apabila user memasukan input 7, maka pengguna akan keluar dari program. berikut adalah tampilannya :
 <br></br>
<img src="https://user-images.githubusercontent.com/103922811/242007840-1b72adbe-c8b3-4bf3-9000-01bc3feb348b.png" width="850" height="100"/>

<text>Demikian aplikasi yang dibuat menggunakan python untuk mengelola nilai siswa. Pada aplikasi ini kita dapat menggunakan fungsi untuk menjalankan fitur CRUD (Create, Read, Update dan Delete) untuk mengelola nilai-nilai siswa. </text>

</ol>
  
