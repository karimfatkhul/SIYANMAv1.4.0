.. Sistem Informasi Layanan Akademik Mahasiswa documentation master file, created by
   sphinx-quickstart on Wed Jan  8 08:28:11 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

*****************
Panduan Pengguna
*****************

Berikut panduan penggunanaan SIYANMA untuk peran Mahasiswa

Mahasiswa
=================================================

Peran utama Mahasiswa dalam SIYANMA adalah untuk mengajukan layanan akademik sesuai dengan kebutuhan. Dalam portal SIYANMA sendiri terdapat 2 jenis layanan akademik yang bisa diakses yaitu, layanan tingkat Fakultas dan layanan tingkat Jurusan.

**Layanan tingkat Fakultas**
 1. Pengajuan SKPI (Surat Keterangan Pendamping Ijazah)
 2. Pengajuan SKL (Surat Keterangan Lulus)
 3. Permohonan Cuti
 4. Pemulihan Status

**Layanan tingkat Jurusan**
 1. Izin Magang
 2. Izin Penelitian
 3. Pendaftaran MBKM
 4. Pengajuan Judul Skripsi
 5. Bimbingan Proposal
 6. Pendaftaran Ujian/Seminar Proposal
 7. Pendaftaran Ujian Skripsi


Berikut ini adalah detail panduan penggunaan untuk layanan-layanan di atas.

Layanan akademik tingkat fakultas
----------------------------------

1.SKPI
~~~~~~~~~~~~~~

**Cara mengajukan SKPI**


 1. Mahasiswa melakukan proses otentikasi melalui halaman Login. Gunakan NPM dan PIN CBIS anda sebagai nama pengguna dan kata sandi pada saat Login.

  
  .. figure:: images/login-new.png
     :width: 600
     :alt: gambar 1. halaman login


 2. Jika kombinasi nama pengguna dan kata sandi tidak valid, maka akan muncul pesan error. Ikuti petunjuk pada pesan error untuk mengatasi malasah yang dihadapi. Jika tetap masih ada kendala pada saat Login, Silakan menghubungi **Admin** untuk bantuan lebih detail.
 3. Jika kombinasi nama pengguna dan kata sandi sesuai, Mahasiswa akan diarahkan ke halaman Dashboard.
 4. Pilih menu :code:`SKPI`. Sistem akan mengarahkan ke halaman daftar pengajuan SKPI. Sebagai catatan, Mahasiswa hanya dapat melihat daftar SKPInya sendiri.

  
  .. figure:: images/skpi.png
     :width: 600
     :alt: gambar 1. halaman daftar SKPI


 5. Tekan tombol :code:`Pengajuan SKPI` untuk melakukan pendaftaran SKPI. Selanjutnya sistem akan mengarahkan ke halaman formulir SKPI. Lengkapi semua kolom isian yang ada.


  .. figure:: images/form-skpi.png
    :width: 600
    :alt: gambar 1. formulir SKPI


 6. Tekan tombol :code:`Ajukan` untuk mengirim/mensubmit pengajuan SKPI.
 8. Jika data isian tidak sesuai, sistem akan memberikan pemberitahuan pesan error. Ikuti petunjuk pada pesan error tersebut untuk mengatasi permasalahan yang ditemui.

  
  .. figure:: images/skpi-error.png
     :width: 600
     :alt: gambar 1. notifikasi error pada saat pengajuan SKPI


 7. Jika data isian telah sesuai, sistem akan memberikan informasi bahwa pengajuan SKPI berhasil dilakukan. Pengajuan SKPI yang berhasil dibuat akan berubah statusnya menjadi :code:`Menunggu staff jurusan` .

  
  .. figure:: images/skpi-ok.png
     :width: 600
     :alt: gambar 1. notifikasi error pada saat pengajuan SKPI


  Dalam pengajuan SKPI terdapat 4 jenis status pengajuan, yaitu:
  
  **Menunggu staff jurusan.**
  Pengajuan dengan status :code:`Menunggu staff jurusan` berarti pengajuan SKPI masih ada dalam tahap verifikasi data oleh pihak Jurusan masing-masing.

  **Menunggu staff fakultas.**
  Pengajuan dengan status :code:`Menunggu staff fakultas` berarti pengajuan SKPI sudah melewati tahap verifikasi data oleh Staff Jurusan dan diteruskan ke pihak Staff Fakultas untuk melakukan approval dengan mengisikan no.Ijazah.

  **Ditolak.**
  Pengajuan dengan status :code:`Ditolak` berarti pengajuan SKPI tidak disetujui. Setiap penolakan terhadap layanan yang diajukan Mahasiswa harus menyertakan **Alasan Penolakan**. Mahasiswa dapat melihat alasan penolakan pada detail pengajuan SKPI. Selanjutnya jika diperlukan, Mahasiswa dapat merevisi/mengedit ulang pengajuan usulan SKPI untuk kembali diajukan ke pihak Fakultas.

  **Disetujui.**
  Pengajuan dengan status :code:`Disetujui` berarti pengajuan SKPI telah valid dan disetujui.


.. note::
    Setelah pengajuan SKPI disetujui, selanjutnya Mahasiswa dapat mengambil dokumen SKPI dengan datang langsung ke Fakultas.
 


2.SKL
~~~~~~~~~~~~~~


**1. Cara Mengajukan SKL**


 1. Pilih menu :code:`SKL`. Sistem akan mengarahkan ke halaman daftar pengajuan SKL.
  
  .. figure:: images/skl.png
     :width: 600
     :alt: gambar 1. halaman daftar skl


 5. Tekan tombol :code:`Pengajuan SKL` untuk melakukan pendaftaran SKL. Selanjutnya sistem akan mengarahkan ke halaman formulir SKL. Lengkapi semua kolom isian yang ada. 

  .. figure:: images/form-skl.png
     :width: 600
     :alt: gambar 1. halaman formulir skl


 6. Tekan tombol :code:`Ajukan` untuk mengirim/mensubmit pengajuan SKL.
 7. Jika data isian tidak sesuai, sistem akan memberikan pemberitahuan pesan error. Ikuti petunjuk pada pesan error tersebut untuk mengatasi permasalahan yang ditemui.

  
  .. figure:: images/skl-error.png
     :width: 600
     :alt: gambar 1. halaman login

 8. Jika data isian telah sesuai, sistem akan memberikan informasi bahwa pengajuan SKL berhasil dilakukan. Pengajuan SKL yang berhasil dikirimkan akan berganti status menjadi :code:`Menunggu`.

 
 .. figure:: images/akun-ok.png
    :width: 600
    :alt: gambar 1. halaman login


  Dalam pengajuan SKL terdapat 3 jenis status pengajuan, yaitu:

  **Menunggu.**
  Pengajuan dengan status :code:`Menunggu` berarti pengajuan SKL masih ada dalam tahap verifikasi data oleh pihak Fakultas (Wakil Dekan Bidang Akademik.


  **Ditolak.**
  Pengajuan dengan status :code:`Ditolak` berarti pengajuan SKL tidak disetujui. Setiap penolakan terhadap layanan yang diajukan Mahasiswa harus menyertakan **Alasan Penolakan**. Mahasiswa dapat melihat alasan penolakan pada detail pengajuan SKL. Selanjutnya jika diperlukan, Mahasiswa dapat merevisi/mengedit ulang pengajuan SKL untuk kembali diajukan ke pihak Fakultas.


  **Diterima.**
  Pengajuan dengan status :code:`Diterima` berarti pengajuan SKL telah disetujui. Selanjutnya Mahasiswa dapat mendownload dan mencetak secara mandiri dokumen SKL melalui halaman detail.


.. note::
    Sebagai salah satu syarat diterimanya pengajuan SKL adalah Mahasiswa harus sudah mendapa persetujuan untuk pengajuan SKPI dan juga bukti yudisium.
 


Layanan akademik tingkat jurusan
---------------------------------

Layanan akademik tingkat jurusan terdiri atas beberapa kategori yaitu, pengajuan Judul Skripsi, Ujian Proposal,  Ujian Pendadaran, dan Surat Keterangan Pendamping Ijazah (SKPI). Berikut cara pengajuan layanan akademik di tingkat jurusan

**1. Mengajukan judul skripsi**

 1. Pada panel menu di sebelah kiri, pilih :code:`Judul Skripsi` untuk membuat pengajuan tentang Judul Skripsi. Pada halaman daftar Judul Skripsi klik tombol :code:`Pengajuan Judul Skripsi` untuk membuat pengajuan baru.

  
  .. figure:: images/judul-list.png
     :width: 600
     :alt: gambar 1. halaman login


 2. Pada halaman formulir pengajuan Judul Skripsi, isikan data pada kolom isian yang ada.
 3. Tekan tombol :code:`Ajukan` untuk mensubmit pengajuan Judul Skripsi.

  
  .. figure:: images/judul-form.png
     :width: 600
     :alt: gambar 1. halaman login


 4. Jika data isian telah sesuai, sistem akan memberikan informasi pemberitahuan bahwa pengajuan berhasil disubmit. Pengajuan yang berhasil disubmit selanjutnya akan diteruskan ke pihak Staff Jurusan untuk direview.
 5. Jika data isian tidak sesuai, sistem akan memberikan pemberitahuan pesan error. Ikuti petunjuk pada pesan error tersebut untuk mengatasi permasalahan yang ditemui.
 6. Pengajuan Judul Skripsi yang berhasil disubmit akan berstatus  :code:`Menunggu` sampai proses review oleh pihak Jurusan selesai. Status pengajuan Judul Skripsi dapat dilihat dalam Daftar Judul Skripsi pada kolom status. Terdapat 3 status sesuai kondisi masing-masing yaitu menunggu, disetujui dan ditolak. 

  * :code:`Menunggu` berarti pengajuan Judul Skripsi masih dalam proses review dan menunggu hasil review dari pihak Jurusan.

  * :code:`Disetujui` berarti pengajuan Judul Skripsi telah disetujui oleh pihak Jurusan. Nantinya Mahasiswa akan mendapatkan surat persetujuan yang dapat di unduh dan dicetak secara mandiri.

  * :code:`Ditolak` berarti pengajuan Judul Skripsi tidak disetujui. Mahasiswa dapat melihat alasan penolakan pada detail pengajuan Judul Skripsi. Selanjutnya jika diperlukan, Mahasiswa dapat merevisi pengajuan Judul Skripsi untuk kembali diajukan ke pihak Jurusan.


.. note::
    Layanan akdemik tingkat Jurusan bersifat sequential (berurutan), dimana antara layanan satu dengan yang lainnya memiliki kesinambungan. Untuk dapat mengajukan Ujian Proposal kita harus terlebih dahulu mendapat persetujuan dari pengajuan Judul Skripsi yang kita buat. Demikian halnya dengan pengajuan Ujian Pendadaran, fitur pengajuan Ujian Pendadaran akan bisa diakses ketika pengajuan Ujian Proposal telah disetujui.  


**2. Mengajukan ujian proposal**

 1. Pada panel menu di sebelah kiri, pilih :code:`Ujian Proposal`. Pada halaman daftar Ujian Proposal klik tombol :code:`Pendaftaran Ujian Proposal`.

  
  .. figure:: images/proposal-list.png
     :width: 600
     :alt: gambar 1. halaman login


 2. Pada halaman formulir pendaftaran Ujian Proposal, isikan data pada kolom isian yang ada. Cermati pada bagian kolom pilih Judul Skripsi. Jika kita belum mengajukan usulan Judul Skripsi atau usulan Judul Skripsi kita belum disetujui, maka kolom pilih Judul Skripsi datanya akan kosong dan kita tidak dapat melakukan pengajuan Ujian Proposal.
 3. Jika kolom Judul Skripsi ada datanya, pilih Judul Skripsi pada kolom tersebut. Secara otomatis kolom Ringkasan Proposal akan terisi sesuai dengan Ringkasan Proposal pada Judul Skripsi yang dipilih.  
 4. Tekan tombol :code:`Ajukan` untuk mensubmit pengajuan Judul Skripsi.

  
  .. figure:: images/proposal-form.png
     :width: 600
     :alt: gambar 1. halaman login


 5. Jika data isian telah sesuai, sistem akan memberikan informasi pemberitahuan bahwa pengajuan berhasil disubmit. Pengajuan yang berhasil disubmit selanjutnya akan diteruskan ke pihak Staff Jurusan untuk direview.
 6. Jika data isian tidak sesuai, sistem akan memberikan pemberitahuan pesan error. Ikuti petunjuk pada pesan error tersebut untuk mengatasi permasalahan yang ditemui.

.. note::
    Ketika pengajuan Ujian proposal telah disetujui, nantinya pihak Staff Jurusan akan menentukan tanggal ujian dan dosen penguji untuk kita. Data tentang dosen penguji ini dapat kita lihat pada halaman detail pada pengajuan Ujian Proposal dengan status :code:`Disetujui`.


  
  .. figure:: images/proposal-detail.png
     :width: 600
     :alt: gambar 1. halaman login


**3. Mengajukan ujian skripsi**

 1. Pada panel menu di sebelah kiri, pilih :code:`Ujian Pendadaran`. Pada halaman daftar Ujian Skripsi klik tombol :code:`Pendaftaran Ujian Skripsi`.

  
  .. figure:: images/skripsi-list.png
     :width: 600
     :alt: gambar 1. halaman login


 2. Pada halaman formulir pendaftaran Ujian Skripsi, isikan data pada kolom isian yang ada. Cermati pada bagian kolom pilih Judul Skripsi. Jika kita belum mengajukan usulan Ujian Proposal atau usulan Ujian Proposal kita belum disetujui, maka kolom pilih Judul Skripsi datanya akan kosong dan kita tidak dapat melakukan pengajuan Ujian Skripsi.
 3. Jika kolom Judul Skripsi ada datanya, pilih Judul Skripsi pada kolom tersebut. Secara otomatis kolom Ringkasan Proposal dan Dosen Pembimbing akan terisi secara otomatis, sesuai dengan Ringkasan Proposal dan Dosen Pembimbing pada Judul Skripsi yang dipilih.  
 4. Tekan tombol :code:`Ajukan` untuk mensubmit pengajuan Judul Skripsi.

  
  .. figure:: images/skripsi-form.png
     :width: 600
     :alt: gambar 1. halaman login


 5. Jika data isian telah sesuai, sistem akan memberikan informasi pemberitahuan bahwa pengajuan berhasil disubmit. Pengajuan yang berhasil disubmit selanjutnya akan diteruskan ke pihak Staff Jurusan untuk direview.
 6. Jika data isian tidak sesuai, sistem akan memberikan pemberitahuan pesan error. Ikuti petunjuk pada pesan error tersebut untuk mengatasi permasalahan yang ditemui.

.. note::
    Ketika pengajuan Ujian Skripsi telah disetujui, nantinya pihak Staff Jurusan akan menentukan tanggal ujian dan dosen penguji untuk kita. Data tentang dosen penguji ini dapat kita lihat pada halaman detail pada pengajuan Ujian Skripsi dengan status :code:`Disetujui`.


**4. Mengajukan SKPI**

 1. Pada panel menu di sebelah kiri, pilih :code:`SKPI`. Pada halaman daftar pengajuan SKPI klik tombol :code:`Pengajuan SKPI`.

  
  .. figure:: images/skpi-list.png
     :width: 600
     :alt: gambar 1. halaman login


 2. Pada halaman formulir pengajuan SKPI, isikan data pada kolom isian yang ada. 
 3. Tekan tombol :code:`Ajukan` untuk mensubmit pengajuan SKPI.

  
  .. figure:: images/skpi-form.png
     :width: 600
     :alt: gambar 1. halaman login


 4. Jika data isian telah sesuai, sistem akan memberikan informasi pemberitahuan bahwa pengajuan berhasil disubmit. Pengajuan yang berhasil disubmit selanjutnya akan diteruskan ke pihak Staff Jurusan untuk direview.
 5. Jika data isian tidak sesuai, sistem akan memberikan pemberitahuan pesan error. Ikuti petunjuk pada pesan error tersebut untuk mengatasi permasalahan yang ditemui.
