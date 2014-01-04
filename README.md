imsakiyah.sh
============

Very simple bash script to display praying time (Sholat). Made for my conky.

####HOWTO?
   *  Give permission and run
      1. `$ chmod +x imsakiyah.sh`
      2. `$ ./imsakiyah.sh`

Output
   * `Sb 03:52 ~ Tb 05:14 ~ Dh 11:35 ~ As 15:02 ~ Mg 17:53 ~ Is 19:09`

####NOTICE
   All praying time are set to Malang, East Jawa, Indonesia local time.
   You can get your local praying time here: [http://www.jadwalsholat.org/adzan/monthly.php?id=141](http://www.jadwalsholat.org/adzan/monthly.php?id=141) (**Indonesia Only**) and then paste it to this script yourself.

Because this script does is only read its contents itself and then displays the corresponding praying times by comparing the combination of the date and month in each row, you might have to format your local praying times to match the example provided in this script. Like this:

```bash
# 0101 Sb 03:51 ~ Tb 05:13 ~ Dh 11:34 ~ As 15:01 ~ Mg 17:52 ~ Is 19:08
# 0201 Sb 03:51 ~ Tb 05:13 ~ Dh 11:35 ~ As 15:01 ~ Mg 17:52 ~ Is 19:09
# 0301 Sb 03:52 ~ Tb 05:14 ~ Dh 11:35 ~ As 15:02 ~ Mg 17:52 ~ Is 19:09
```

Those lines are praying times for January 1st - 3st, if you want to change to your local time, then it should be like this:

```bash
# 0101 [your local praying time]
# 0201 [your local praying time]
# 0301 [your local praying time]
```

Or `# ddmm[space][your local praying time]`

###BAHASA INDONESIA

Script bash sederhana untuk menampilkan waktu Sholat.

####HOWTO?
   *  Beri hak akses dan jalankan

Output
   * `Sb 03:52 ~ Tb 05:14 ~ Dh 11:35 ~ As 15:02 ~ Mg 17:53 ~ Is 19:09`

####NOTICE
   Semua waktu Sholat disesuaikan untuk wilayah Malang Jawa Timur.
   Anda bisa mendapatkan waktu Sholat lokal Anda di sini: [http://www.jadwalsholat.org/adzan/monthly.php?id=141](http://www.jadwalsholat.org/adzan/monthly.php?id=141) dan kemudian memasukkannya ke ke dalam script.

Karena cara kerja script ini hanya membaca isinya sendiri dan menampilkan waktu Sholat yang sesuai dengan cara membandingkan kombinasi tanggal dan bulan pada masing-masing baris, maka Anda harus menyesuaikan cara penulisan waktu lokal Anda seperti yang telah dicontohkan di script. Seperti ini:

```bash
# 0101 Sb 03:51 ~ Tb 05:13 ~ Dh 11:34 ~ As 15:01 ~ Mg 17:52 ~ Is 19:08
# 0201 Sb 03:51 ~ Tb 05:13 ~ Dh 11:35 ~ As 15:01 ~ Mg 17:52 ~ Is 19:09
# 0301 Sb 03:52 ~ Tb 05:14 ~ Dh 11:35 ~ As 15:02 ~ Mg 17:52 ~ Is 19:09
```

Baris tersebut adalah waktu sholat untuk tanggal 1 - 3 Januari, untuk mengganti dengan waktu lokal Anda, maka formatnya adalah seperti ini:

```bash
# 0101 [waktu lokal Anda]
# 0201 [waktu lokal Anda]
# 0301 [waktu lokal Anda]
```

Atau `# ddmm[spasi][waktu lokal Anda]`
