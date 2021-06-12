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


SKPI
----------------------------------



Berikut adalah alur pengajuan SKPI

  
  .. figure:: images/skpi-alur.png
     :width: 600
     :alt: gambar 1. halaman daftar skl




Cara mengajukan SKPI
~~~~~~~~~~~~~~~~~~~~~~~~~~~~


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


 6. Tekan tombol :code:`Ajukan` untuk mengirim/mensubmit pengajuan SKPI. Tunggu sampai proses loading pengiriman selesai.
 7. Jika data isian tidak sesuai, sistem akan memberikan pemberitahuan pesan error. Ikuti petunjuk pada pesan error tersebut untuk mengatasi permasalahan yang ditemui.

  
  .. figure:: images/skpi-error.png
     :width: 600
     :alt: gambar 1. notifikasi error pada saat pengajuan SKPI


 8. Jika data isian telah sesuai, sistem akan memberikan informasi bahwa pengajuan SKPI berhasil dilakukan. Pengajuan SKPI yang berhasil dibuat akan berubah statusnya menjadi :code:`Menunggu staff jurusan`. Status pengajuan SKPI dapat dilihat pada kolom status pengajuan.


  
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
 

Merevisi pengajuan SKPI
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


 1. Klik tanda :code:`...` pada kolom opsi pada baris pengajuan SKPI yang ingin direvisi. Selanjutnya akan muncul 3 pilihan sub menu yaitu Details, Edit dan Hapus.   

  
  .. figure:: images/skpi-opsi.png
     :width: 600
     :alt: gambar 1. Opsi menu pada pengajuan SKPI


 2. Jika status pengajuan masih :code:`Menunggu` , pilih :code:`Edit` untuk langsung mengedit data pengajuan SKPI. 
 3. Jika status pengajuan :code:`Ditolak`, tekan :code:`Details` untuk melihat details data. Perhatikan pada bagian **alasan penolakan**. Alasan penolakan biasanya berisi petunjuk mengapa pengajuan SKPI Anda ditolak. Selanjutnya pada halaman details ini tekan tombol Edit untuk mengedit data.

  
  .. figure:: images/skpi-details.png
     :width: 600
     :alt: gambar 1. halaman details SKPI


 4. Perbarui data pada kolom isian yang ingin direvisi.  
 5. Tekan tombol menu :code:`Ajukan` untuk kembali mengirimkan pengajaun SKPI yang sudah direvisi.




Surat Keterangan Lulus (SKL)
----------------------------------

Berikut adalah alur pengajuan SKL

  
  .. figure:: images/skl-alur.png
     :width: 600
     :alt: gambar 1. halaman daftar skl




Cara Mengajukan SKL
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


 1. Pilih menu :code:`SKL`. Sistem akan mengarahkan ke halaman daftar pengajuan SKL.
  
  .. figure:: images/skl.png
     :width: 600
     :alt: gambar 1. halaman daftar skl


 2. Tekan tombol :code:`Pengajuan SKL` untuk melakukan pendaftaran SKL. Selanjutnya sistem akan mengarahkan ke halaman formulir SKL. Lengkapi semua kolom isian yang ada. 

  .. figure:: images/form-skl.png
     :width: 600
     :alt: gambar 1. halaman formulir skl


 3. Tekan tombol :code:`Ajukan` untuk mengirim/mensubmit pengajuan SKL. Tunggu sampai proses loading pengiriman selesai.
 4. Jika data isian tidak sesuai, sistem akan memberikan pemberitahuan pesan error. Ikuti petunjuk pada pesan error tersebut untuk mengatasi permasalahan yang ditemui.

  
  .. figure:: images/skl-error.png
     :width: 600
     :alt: gambar 1. notifikasi error pada saat pengajuan skl

 5. Jika data isian telah sesuai, sistem akan memberikan informasi bahwa pengajuan SKL berhasil dilakukan. Pengajuan SKL yang berhasil dikirimkan akan berganti status menjadi :code:`Menunggu` sampai proses verifikasi selesai.

 
 .. figure:: images/skl-ok.png
    :width: 600
    :alt: gambar 1. notifikasi sukses pada saat pengajuan skl


 Dalam pengajuan SKL terdapat 3 jenis status pengajuan, yaitu:

 **Menunggu.**
 Pengajuan dengan status :code:`Menunggu` berarti pengajuan SKL masih ada dalam tahap verifikasi data oleh pihak Fakultas (Wakil Dekan Bidang Akademik.


 **Ditolak.**
 Pengajuan dengan status :code:`Ditolak` berarti pengajuan SKL tidak disetujui. Setiap penolakan terhadap layanan yang diajukan Mahasiswa harus menyertakan :code:`Alasan Penolakan` . Mahasiswa dapat melihat alasan penolakan pada detail pengajuan SKL. Selanjutnya jika diperlukan, Mahasiswa dapat merevisi/mengedit ulang pengajuan SKL untuk kembali diajukan ke pihak Fakultas.


 **Diterima.**
 Pengajuan dengan status :code:`Diterima` berarti pengajuan SKL telah disetujui. Selanjutnya Mahasiswa dapat mendownload dan mencetak secara mandiri dokumen SKL melalui halaman detail.


.. note::
    Sebagai salah satu syarat diterimanya pengajuan SKL adalah Mahasiswa harus sudah mendapat persetujuan untuk pengajuan SKPI dan juga bukti yudisium.


Merevisi pengajuan SKL
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


 1. Klik tanda :code:`...` pada kolom opsi pada baris pengajuan SKL yang ingin direvisi. Selanjutnya akan muncul 3 pilihan sub menu yaitu Details, Edit dan Hapus.   

  
  .. figure:: images/skl-opsi.png
     :width: 600
     :alt: gambar 1. Opsi menu pada pengajuan SKL


 2. Jika status pengajuan masih :code:`Menunggu` , pilih :code:`Edit` untuk langsung mengedit data pengajuan SKL. 
 3. Jika status pengajuan :code:`Ditolak`, tekan :code:`Details` untuk melihat details data. Perhatikan pada bagian :code:`alasan penolakan` . Alasan penolakan biasanya berisi petunjuk mengapa pengajuan SKL Anda ditolak. Selanjutnya pada halaman details ini tekan tombol Edit untuk mengedit data.

  
 .. figure:: images/skl-details.png
     :width: 600
     :alt: gambar 1. halaman details SKL


 4. Perbarui data pada kolom isian yang ingin direvisi.  
 5. Tekan tombol menu :code:`Ajukan` untuk kembali mengirimkan pengajaun SKL yang sudah direvisi.



Permohonan Cuti dan Pemulihan Status
--------------------------------------


Secara garis besar, cara mengajukan permohonan cuti dan pemulihan status hampir serupa dengan pengajuan SKL. Mahasiswa mengajukan permohonan layanan dengan mengisi formulir secara online, untuk selanjutnya data pengajuan diverifikasi oleh pihak Fakultas (Wakil Dekan Bidang Akademik). Selanjutnya jika pengajuan layanan disetujui, Mahasiswa dapat mengunduh surat keterangan cuti dan pemulihan status melalui halaman detail pada menu permohonan cuti dan pemulihan status.


Berikut adalah alur pengajuan permohonan cuti 

  
  .. figure:: images/cuti-alur.png
     :width: 600
     :alt: gambar 1. halaman daftar skl



Berikut adalah halaman formulir permohonan cuti 


 .. figure:: images/form-cuti.png
     :width: 600
     :alt: gambar 1. halaman details SKL


Berikut adalah alur pengajuan pemulihan status 

  
  .. figure:: images/pemulihan-alur.png
     :width: 600
     :alt: gambar 1. halaman daftar skl


Berikut adalah halaman formulir pemulihan status 


 .. figure:: images/form-pemulihan.png
     :width: 600
     :alt: gambar 1. halaman details SKL


Izin Magang
--------------------------------------


Berikut adalah bagan alur Permohonan Izin Magang

  
  .. figure:: images/magang-alur.png
     :width: 600
     :alt: gambar 1. halaman daftar skl



Cara Mengajukan Izin Magang
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


 1. Pilih menu :code:`Izin Magang`. Selanjutnya sistem akan mengarahkan ke halaman daftar pengajuan Izin Magang.
  
  .. figure:: images/magang.png
     :width: 600
     :alt: gambar 1. halaman daftar magang


 2. Tekan tombol :code:`Pengajuan Magang` untuk melakukan pengajuan Izin Magang. Selanjutnya sistem akan mengarahkan ke halaman formulir Izin Magang. Lengkapi semua kolom isian yang ada. 

  .. figure:: images/form-magang.png
     :width: 600
     :alt: gambar 1. halaman formulir magang


 3. Tekan tombol :code:`Ajukan` untuk mengirim/mensubmit pengajuan Izin Magang. Tunggu sampai proses loading pengiriman selesai.
 4. Jika data isian tidak sesuai, sistem akan memberikan pemberitahuan pesan error. Ikuti petunjuk pada pesan error tersebut untuk mengatasi permasalahan yang ditemui.

  
  .. figure:: images/magang-error.png
     :width: 600
     :alt: gambar 1. notifikasi error pada saat pengajuan magang


 5. Jika data isian telah sesuai, sistem akan memberikan informasi bahwa pengajuan Izin Magang berhasil dilakukan. Pengajuan Izin Magang yang berhasil dikirimkan akan berganti status menjadi :code:`Menunggu` sampai proses verifikasi pihak Jurusan selesai.

 
 .. figure:: images/magang-ok.png
    :width: 600
    :alt: gambar 1. notifikasi sukses pada saat pengajuan magang


 Dalam pengajuan Izin Magang terdapat 3 jenis status pengajuan, yaitu:

 **Menunggu.**
 Pengajuan dengan status :code:`Menunggu` berarti pengajuan Izin Magang masih ada dalam tahap verifikasi data oleh pihak Jurusan.


 **Ditolak.**
 Pengajuan dengan status :code:`Ditolak` berarti pengajuan Izin Magang tidak disetujui. Setiap penolakan terhadap layanan yang diajukan Mahasiswa harus menyertakan :code:`Alasan Penolakan` . Mahasiswa dapat melihat alasan penolakan pada detail pengajuan Izin Magang. Selanjutnya jika diperlukan, Mahasiswa dapat merevisi/mengedit ulang pengajuan Izin Magang untuk kembali diajukan ke pihak Jurusan.


 **Diterima.**
 Pengajuan dengan status :code:`Diterima` berarti pengajuan Izin Magang telah disetujui. Selanjutnya Mahasiswa dapat mendownload dan mencetak secara mandiri dokumen Izin Magang melalui halaman detail.


.. note::
    Mahasiswa hanya diperbolehkan untuk mengajukan satu Izin Magang dalam satu waktu.


Merevisi pengajuan Izin Magang
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


 1. Klik tanda :code:`...` pada kolom opsi pada baris pengajuan Izin Magang yang ingin direvisi. Selanjutnya akan muncul 3 pilihan sub menu yaitu Details, Edit dan Hapus.   

  
  .. figure:: images/magang-opsi.png
     :width: 600
     :alt: gambar 1. Opsi menu pada pengajuan Izin Magang


 2. Jika status pengajuan masih :code:`Menunggu` , pilih :code:`Edit` untuk langsung mengedit data pengajuan Izin Magang. 
 3. Jika status pengajuan :code:`Ditolak`, tekan :code:`Details` untuk melihat details data. Perhatikan pada bagian :code:`alasan penolakan` . Alasan penolakan biasanya berisi petunjuk mengapa pengajuan Izin Magang Anda ditolak. Selanjutnya pada halaman details ini tekan tombol Edit untuk mengedit data.

  
 .. figure:: images/skl-details.png
     :width: 600
     :alt: gambar 1. halaman details Izin Magang


 4. Perbarui data pada kolom isian yang ingin direvisi. 
 5. Tekan tombol menu :code:`Ajukan` untuk kembali mengirimkan pengajaun Izin Magang yang sudah direvisi.



Izin Penelitian
--------------------------------------


Secara garis besar, proses pengajuan Izin Penelitian serupa dengan pengajaun Izin Magang. Hal yang membedakan hanyalah formulir pengajuan yang harus diisi. Berikut adalah formulir pengajuan Izin Penelitian yang harus diisi.

  
  .. figure:: images/form-penelitian.png
     :width: 600
     :alt: gambar 1. halaman formulir Izin Penelitian



Layanan Skripsi
---------------------------------


Berikut adalah bagan alur pengajuan layanan skripsi mulai dari pengajuan Judul Skripsi sampai pada penagjaun Ujian Skripsi.

  
  .. figure:: images/skripsi-alur.png
     :width: 600
     :alt: gambar 1. halaman alur skripsi



Cara Mengajukan Permohonan Judul Skripsi
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


 1. Pada panel menu di sebelah kiri, pilih :code:`Judul Skripsi` untuk membuat pengajuan tentang Judul Skripsi. Pada halaman daftar Judul Skripsi klik tombol :code:`Pengajuan Judul Skripsi` untuk membuat pengajuan baru.

  
  .. figure:: images/judul.png
     :width: 600
     :alt: gambar 1. halaman daftat pengajuan judul


 2. Pada halaman formulir pengajuan Judul Skripsi, isikan data pada kolom isian yang ada.
 3. Pastikan untuk melengkapi semua dokumen persyaratan yang ada.
 4. Tekan tombol :code:`Ajukan` untuk mensubmit pengajuan Judul Skripsi.

  
  .. figure:: images/judul-form.png
     :width: 600
     :alt: gambar 1. halaman formulir pengajuan judul


 5. Jika data isian telah sesuai, sistem akan memberikan informasi pemberitahuan bahwa pengajuan berhasil disubmit. Pengajuan yang berhasil disubmit selanjutnya akan diteruskan ke pihak Staff Jurusan untuk direview.
 6. Jika data isian tidak sesuai, sistem akan memberikan pemberitahuan pesan error. Ikuti petunjuk pada pesan error tersebut untuk mengatasi permasalahan yang ditemui.
 7. Pengajuan Judul Skripsi yang berhasil disubmit akan berstatus  :code:`Menunggu` sampai proses review oleh pihak Jurusan selesai. Status pengajuan Judul Skripsi dapat dilihat dalam Daftar Judul Skripsi pada kolom status. Terdapat 3 status sesuai kondisi masing-masing yaitu menunggu, disetujui dan ditolak. 

  :code:`Menunggu` berarti pengajuan Judul Skripsi masih dalam proses review dan menunggu hasil review dari pihak Jurusan.

  :code:`Disetujui` berarti pengajuan Judul Skripsi telah disetujui oleh pihak Jurusan. Mahasiswa dapat melihat detail nama Pembimbing 1 dan Pembimbing 2 setelah pengajaun disetujui.

  :code:`Ditolak` berarti pengajuan Judul Skripsi tidak disetujui. Mahasiswa dapat melihat alasan penolakan pada detail pengajuan Judul Skripsi. Selanjutnya jika diperlukan, Mahasiswa dapat merevisi pengajuan Judul Skripsi untuk kembali diajukan ke pihak Jurusan.


.. note::
    Layanan akdemik tingkat Jurusan bersifat sequential (berurutan), dimana antara layanan satu dengan yang lainnya memiliki kesinambungan. Untuk dapat mengajukan Ujian Proposal kita harus terlebih dahulu mendapat persetujuan dari pengajuan Judul Skripsi yang kita buat. Demikian halnya dengan pengajuan Ujian Skripsi baru bisa dilakukan setelah Mahasiswa menyelesaikan Ujian Proposal/Seminar Proposal. 


Cara Mengajukan Bimbingan Skripsi
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


 1. Pada panel menu di sebelah kiri, pilih :code:`Bimbingan`. Pada halaman daftar Bimbingan klik tombol :code:`Pengajuan Bimbingan` untuk membuat bimbingan baru.

  
  .. figure:: images/bimbingan.png
     :width: 600
     :alt: gambar 1. halaman bimbingan


  Pengajuan bimbingan dengan text bold dan memiliki background color menunjukkan bahwa pengajuan tersebut belum mendapat feedback dari Dosen Pembimbing



 2. Pada halaman formulir pengajaun Bimbingan, lengkapi data pada kolom isian yang ada. Cermati pada bagian kolom pilih Judul Skripsi. Jika kita belum mengajukan usulan Judul Skripsi atau usulan Judul Skripsi kita belum disetujui, maka kolom pilih Judul Skripsi datanya akan kosong dan kita tidak dapat melakukan pengajuan Bimbingan.
 3. Jika kolom Judul Skripsi ada datanya, pilih Judul Skripsi pada kolom tersebut. Secara otomatis kolom Ringkasan Proposal akan terisi sesuai dengan Ringkasan Proposal pada Judul Skripsi yang dipilih.  
 4. Tekan tombol :code:`Ajukan` untuk mensubmit pengajuan Bimbingan.

  
  .. figure:: images/form-bimbingan.png
     :width: 600
     :alt: gambar 1. halaman login


 5. Jika data isian telah sesuai, sistem akan memberikan informasi pemberitahuan bahwa pengajuan berhasil disubmit. Pengajuan yang berhasil disubmit selanjutnya akan diteruskan ke Dosen Pembimbing untuk direview.
 6. Jika data isian tidak sesuai, sistem akan memberikan pemberitahuan pesan error. Ikuti petunjuk pada pesan error tersebut untuk mengatasi permasalahan yang ditemui.

  Feedback bimbingan dari Dosen Pembimbing dapat dilihat pada halaman detail Bimbingan seperti gambar di bawah ini. Tekan tombol :code:`Unduh Dokumen` untuk melihat dokumen feedback yang dilampirkan Dosen Pembimbing. 


  .. figure:: images/bimbingan-details.png
     :width: 600
     :alt: gambar 1. halaman details bimbingan



Cara Mengajukan Ujian/Seminar Proposal
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~



 1. Pada panel menu di sebelah kiri, pilih :code:`Ujian Proposal`. Pada halaman daftar Ujian Proposal klik tombol :code:`Pendaftaran Ujian Proposal`.

  
  .. figure:: images/proposal.png
     :width: 600
     :alt: gambar 1. halaman proposal


 2. Pada halaman formulir pendaftaran Ujian Proposal, lengkapi data pada kolom isian yang ada. 
 3. Tekan tombol :code:`Ajukan` untuk mensubmit pengajuan Ujian Proposal.

  
  .. figure:: images/form-proposal.png
     :width: 600
     :alt: gambar 1. halaman formulir proposal


 4. Jika data isian telah sesuai, sistem akan memberikan informasi pemberitahuan bahwa pengajuan berhasil disubmit. Pengajuan yang berhasil disubmit selanjutnya akan diteruskan ke pihak Staff Jurusan untuk diverifikasi.
 5. Jika data isian tidak sesuai, sistem akan memberikan pemberitahuan pesan error. Ikuti petunjuk pada pesan error tersebut untuk mengatasi permasalahan yang ditemui.


.. note::
    Ketika pengajuan Ujian proposal telah disetujui, nantinya pihak Staff Jurusan akan menentukan tanggal ujian dan Dosen Penguji 1 untuk Mahasiswa. Detail tentang data ini dapat dilihat pada halaman detail pada pengajuan Ujian Proposal dengan status :code:`Disetujui`. Setelah proses Ujian/Seminar Proposal selesai, Mahasiswa juga dapat melihat daftar penilaian Ujian Proposalnya pada halaman detail ini.
  

  
    .. figure:: images/proposal-detail.png
       :width: 600
       :alt: gambar 1. halaman proposal detail



Cara Mengajukan Ujian Skripsi
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~



 1. Pada panel menu di sebelah kiri, pilih :code:`Ujian Skripsi`. Pada halaman daftar Ujian Skripsi klik tombol :code:`Pendaftaran Ujian Skripsi`.

  
  .. figure:: images/skripsi.png
     :width: 600
     :alt: gambar 1. halaman skripsi


 2. Pada halaman formulir pendaftaran Ujian Skripsi, lengkapi data pada kolom isian yang ada. Pastikan anda mengupload semua dokumen persyaratan.  
 3. Tekan tombol :code:`Ajukan` untuk mensubmit pengajuan Ujian Skripsi.

  
  .. figure:: images/form-skripsi.png
     :width: 600
     :alt: gambar 1. halaman formulir skripsi


 4. Jika data isian telah sesuai, sistem akan memberikan informasi pemberitahuan bahwa pengajuan berhasil disubmit. Pengajuan yang berhasil disubmit selanjutnya akan diteruskan ke pihak Staff Jurusan untuk diverifikasi.
 5. Jika data isian tidak sesuai, sistem akan memberikan pemberitahuan pesan error. Ikuti petunjuk pada pesan error tersebut untuk mengatasi permasalahan yang ditemui.


.. note::
    Ketika pengajuan Ujian Skripsi telah disetujui, nantinya pihak Staff Jurusan akan menentukan tanggal ujian dan Dosen Penguji 2 untuk Mahasiswa. Detail tentang data ini dapat dilihat pada halaman detail pada pengajuan Ujian Skripsi dengan status :code:`Disetujui`. Setelah proses Ujian Skripsi selesai, Mahasiswa juga dapat melihat daftar penilaian Ujian Proposalnya pada halaman detail ini.
  
  
    .. figure:: images/skripsi-detail.png
       :width: 600
       :alt: gambar 1. halaman proposal detail

 

Merevisi pengajuan Layanan Skripsi
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


 1. Pilih menu layanan sesuai dengan jenis layanan yang ingin direvisi.
 2. Tekan tanda :code:`...` pada kolom opsi pada baris daftar layanan yang ingin direvisi. Selanjutnya akan muncul 3 pilihan sub menu yaitu Details, Edit dan Hapus.   
 3. Jika status pengajuan layanan masih :code:`Menunggu` , pilih :code:`Edit` untuk langsung mengedit data pengajuan. 
 4. Jika status pengajuan :code:`Ditolak`, tekan :code:`Details` untuk melihat details data. Perhatikan pada bagian :code:`alasan penolakan` . Alasan penolakan biasanya berisi petunjuk mengapa pengajuan layanan Anda ditolak. Selanjutnya pada halaman details ini tekan tombol Edit untuk mengedit data.
 5. Perbarui data pada kolom isian yang ingin direvisi. 
 6. Tekan tombol menu :code:`Ajukan` untuk kembali mengirimkan pengajaun layanan yang sudah direvisi.


