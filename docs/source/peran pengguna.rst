.. Sistem Informasi Layanan Akademik Mahasiswa documentation master file, created by
   sphinx-quickstart on Wed Jan  8 08:28:11 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

***************
Peran Pengguna
***************

Untuk mempermudah penggunaan SIYANMA, sistem ini terbagi atas beberapa peran pengguna yaitu: 

1. Admin
=========
	
	Peran utama :code:`Admin` dalam SIYANMA adalah mengelola semua pengguna yang terlibat dalam pemakaian sistem ini. Admin dapat  membuat akun untuk pengguna lain, mengedit akun serta menghapus akun pengguna. Admin juga mempunyai hak akses untuk dapat memonitor semua jalannya proses pengajuan layanan akademik oleh mahasiswa.  
 

	.. note::
	    Pengguna dengan peran sebagai Admin, secara otomatis akan mempunyai hak akses sebagai Admin disemua sistem informasi yang ada (SILOMA, SIPRESMA dan SIYANMA). Jadi ketika kita membuat pengguna dengan peran sebagai Admin melalui SIYANMA, maka secara otomatis pengguna yang baru saja dibuat tersebut dapat mengakses SILOMA dan SIPRESMA dengan hak akses sebagai Admin. 

	 
2. Wakil Dekan Bidang Akademik
==================================
	
	:code:`Wakil Dekan Bidang Akademik` mempunyai peran untuk melakukan verifikasi layanan SKL, Permohonan Cuti dan Pemulihan Status. Selanjutnya jika pengajuan diangap valid maka Wakil Dekan Bidang Akademik dapat menyetujui pengajuan-pengajuan tersebut.


3. Staff Fakultas
==================
	
	:code:`Staff Fakultas` mempunyai peran untuk memverifikasi pengajuan layanan SKPI. Selanjutnya jika pengajuan diangap valid maka Staff Fakultas dapat menyetujui pengajuan tersebut.


4. Staff Jurusan
=================

	:code:`Staff Jurusan` mempunyai peran untuk memverifikasi pengajuan layanan SKPI, Izin Magang, Izin Penelitian, Pengajuan MBKM, Pengajuan Judul Skripsi, serta Pengajuan Ujian Skripsi. Selanjutnya jika pengajuan diangap valid maka Staff Jurusan dapat menyetujui pengajuan layanan tersebut.



5. Dosen
=================

	:code:`Dosen` mempunyai peran untuk memberikan feedback terhadap pengajuan layanan Bimbingan Skripsi dan MBKM. Selain itu, Dosen yang ditunjuk sebagai Dosen Pembimbing 1 mempunyai peran untuk memverifikasi pengajuan Ujian/Seminar Proposal. Selanjutnya jika pengajuan diangap valid maka Dosen Pembimbing 1 dapat menyetujui pengajuan tersebut dengan menentukan tanggal Ujian/Seminar Proposal.



6. Mahasiswa
=============
	
	:code:`Mahasiswa` mempunyai peran untuk mengajukan layanan akademik baik ditingkat jurusan ataupun ditingkat fakultas. 


	.. note::
	    Untuk dapat mengakses layanan SIYANMA dan SIPRESMA pastikan setiap Mahasiswa sudah mempunyai akses ke CBIS. Gunakan NPM dan PIN CBIS tersebut untuk login ke layanan SIYANMA dan SIPRESMA.

