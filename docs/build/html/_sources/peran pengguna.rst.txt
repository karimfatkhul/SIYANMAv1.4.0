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
	    Pengguna dengan peran sebagai Admin, secara otomatis akan mempunyai hak akses sebagai Admin disemua sistem informasi yang ada (SIREBI, SIPRESMA dan SIYANMA). Jadi ketika kita membuat pengguna dengan peran sebagai Admin melalui SIYANMA, maka secara otomatis pengguna yang baru saja dibuat tersebut dapat mengakses SIREBI dan SIPRESMA dengan hak akses sebagai Admin. 

	 
2. Mahasiswa
=============
	
	:code:`Mahasiswa` mempunyai peran untuk mengajukan layanan akademik baik ditingkat jurusan ataupun ditingkat fakultas. Untuk dapat menggunakan layanan SIYANMA, Mahasiswa dapat mendaftar secara mandiri melalui portal SIYANMA.


	.. note::
	    Ketika kita membuat pengguna dengan peran sebagai Mahasiswa di SIYANMA, secara otomatis pengguna tersebut juga mempunyai hak akses ke Sistem Informasi Prestasi Mahasiswa (SIPRESMA) dengan peran sebagai Mahasiswa.


3. Staff Fakultas
==================
	
	Pengguna dengan peran sebagai :code:`Staff Fakultas` mempunyai mempunyai peran untuk merespon pengajuan layanan akademik di tingkat fakultas, yang telah dibuat oleh Mahasiswa. Selanjutnya apabila data yang dimasukkan sudah memenuhi syarat, maka akan disiapkan berkas-berkas sesuai dengan layanan yang diajukan.


4. Staff Jurusan
=================

	Pengguna dengan peran sebagai :code:`Staff Jurusan` mempunyai mempunyai peran untuk merespon pengajuan layanan akademik di tingkat jurusan, yang telah dibuat oleh Mahasiswa. Selanjutnya apabila data yang dimasukkan sudah memenuhi syarat, maka akan disiapkan berkas-berkas sesuai dengan layanan yang diajukan.
