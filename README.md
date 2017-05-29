
TKPPL-bespoke-Dubasata
======================

*************************************
mohon di-edit bila terdapat kesalahan
*************************************

Presentasi Virtual-Reality dengan bespoke.

Quick notes bagi anggota kelompok [MOHON DIBACA!!!] :

1. Pastikan sudah menginstall  Node.js, Git, Github for Windows.

2. Lakukan fork pada project ini.

3. Lakukan Clone project ini ke Komputer masing - masing melalui Github anda sendiri.

4. Arahkan console pada folder proyek anda dan ketikkan 'npm install' && 'bower install' tanpa tanda "'". 

5. Merging(Penggabungan) perubahan setiap anggota hanya boleh dilakukan pada repository Scrum Master.

6. Setiap perubahan yang telah dilakukan oleh anggota wajib MEMBERITAHUKAN kepada Scrum Master agar perubahan dapat di Merge.

7. Scrum Master wajib memeriksa dengan baik perubahan - perubahan yang diberitahukan oleh anggota dan melakukan pull dengan bijak.

8. Untuk mengambil perubahan dari github utama/ github master lakukan:

	a. Untuk pertama kali ketikkan:

		cd into/cloned/fork-repo

		git remote add upstream git://github.com/ORIGINAL-DEV-USERNAME/REPO-YOU-FORKED-FROM.git

	b. Untuk selanjutnya cukup ketikkan command di bawah ini untuk mengambil perubahan terbaru:

		git fetch upstream

		git pull upstream master

9. Bila command npm install bermasalah, ketikkan npm cache clean terlebih dahulu lalu ketikkan npm install kembali

### View slides locally

First, ensure you have the following installed:

1. [Node.js](http://nodejs.org)
2. [Bower](http://bower.io): `$ npm install -g bower`
3. [Gulp](http://gulpjs.com): `$ npm install -g gulp`

Then, install dependencies and run the preview server:

```bash
$ npm install && bower install
$ gulp serve
```

