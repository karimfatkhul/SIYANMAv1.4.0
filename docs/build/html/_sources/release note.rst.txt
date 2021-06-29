.. Sistem Informasi Layanan Akademik Mahasiswa documentation master file, created by
   sphinx-quickstart on Wed Jan  8 08:28:11 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

***************
Release Note
***************

Berikut adalah beberapa catatan update atau perubahan untuk SIYANMA versi 1.4.0

1. Penambahan menu Mata Kuliah dan Jadwal Kuliah
=================================================
	
 Pada SIYANMA versi 1.4.0 terdapat penambahan menu untuk manajemen daftara mata kuliah dan jadwal kuliah. Menu ini dapat diakses oleh Staff Fakultas dan Admin dengan hak akses full access.  
 
 .. figure:: images/matkul.png
     :width: 600
     :alt: gambar 1. halaman mata kuliah


 .. note::
	 Admin dan Staf Fakultas dapat menginputkan data mata kuliah dan jadwal mata kuliah pada menu Mata Kuliah dan Jadwal Kuliah

	 
2. Perubahan input berkas persyaratan pengajuan Judul Skripsi
===============================================================
	
 Pada versi sebelumnya, dokumen persyaratan pengajuan Judul Skripsi dibuat dalam satu dokumen .zip. Pada update versi 1.4.0 , upload berkas persyaratan dibagi menjadi 3 input terpisah yaitu, upload berkas Transkrip Nilai, KTM dan KRP.

 .. figure:: images/judul-2.png
     :width: 600
     :alt: gambar 1. update pengauan judul skripsi


3. Perbuahan skema approval pengajuan Judul Skripsi
============================================================
	
 Jika pada versi sebelumnya proses approval pengajuan Judul Skripsi dilakukan dengan menentukan Dosen Pembimbing 1 dan Dosen Pembimbing 2, maka pada SIYANMA versi 1.4.0 terdapat penambahan untuk menentukan Dosen Penguji 1. Proses approval dilakukan oleh Staff Jurusan masing-masing.


 .. figure:: images/judul-skripsi-3.png
     :width: 600
     :alt: gambar 1. halaman aproval judul


 .. note::
	Untuk Mahasiswa yang pada versi SIYANMA sebelumnya sudah mendapatkan approval Judul Skripsi, tetapi belum mengajukan Ujian/Seminar Proposal atau pengajuan Ujian/Seminar Proposalnya belum disetujui maka kolom Dosen Penguji 1 masih kosong. Staff Jurusan dapat menginputkan atau menentukan Dosen Penguji 1 untuk Mahasiswa dengan kasus di atas pada halaman detail pengajuan Judul. Berikut adalah langkah-langkah untuk menambahkan Dosen Penguji 1 berdasarkan kasus di atas.

	1. Tekan menu Judul Skripsi, tekan tombol detail pada baris pengajuan Judul Skripsi yang inging ditambahkan Dosen Penguji 1 nya
	2. Pada halama detail tekan pada baris Edit Dosen Penguji, pilih Dosen Penguji 1 lalu tekan tombol Simpan

    .. figure:: images/edit-penguji.png
      :width: 600
      :alt: gambar 1. halaman edit dosen penguji


4. Perbuahan skema approval pengajuan Ujian Proposal
=======================================================

	Jika pada versi sebelumnya proses approval pengajuan Ujian Proposal dilakukan oleh Staff Jurusan, maka pada versi 1.4.0 proses approval dilakukan oleh Dosen Pembimbing 1. Dosen Pembimbing 1 melakukan approval dengan menentukan kapan tanggal Ujian/Seminar Proposal akan dilaksanakan. Nantinya Dosen Pembimbing 1, Dosen Pembimbing 2 serta Dosen Penguji 1 akan mendapatkan notifikasi tentang kapan waktu Ujian/Seminar proposal tersebut akan dilaksanakan.


 .. figure:: images/prop.png
     :width: 600
     :alt: gambar 1. halaman formulir skripsi



5. Perubahan input berkas persyaratan pengajuan Ujian Skripsi
=============================================================

	Pada versi sebelumnya, dokumen persyaratan pengajuan Ujian Skripsi dibuat dalam satu dokumen .zip. Pada update versi 1.4.0 , upload berkas persyaratan dibagi menjadi 8 input terpisah yaitu, upload berkas Transkrip Nilai, KRP terakhir, Sertifikat TOEFL, Persetujuan revisi proposal yang sudah ditandatangani, Ijazah SLTA (legalisir), Akta Kelahiran serta Pas foto terbaru berwarna dan memakai jas.

 .. figure:: images/skripsi-2.png
     :width: 600
     :alt: gambar 1. halaman formulir skripsi



