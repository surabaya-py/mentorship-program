# Surabaya.py Mentorship Program #1
## Topik: Web API dengan Flask, development hingga production

* Mentor: 
* Batas Pendaftaran:
* Jadwal Kegiatan:

## Kisi-Kisi Materi

* A
* B
* C
* D

## Cara Pendaftaran

1. Buatlah sebuah ide yang berhubungan dengan topik bersama tim atau sendiri.
1. Buat repository kosong di github dengan isi dari `readme.md` merupakan penjelasan ide yang mau di buat.
1. Jika bekerja bersama tim, maka jadikan anggota tim menjadi kolaborator pada repository tersebut.
1. Kirim HTTP request ke `http://surabayapy.heroku.com/daftar/mentorship/1` dengan header `Content-Type: application/json` dan method POST. Body sebagai berikut:

```json
{
	"peserta":[
		{
		"nama":"NAMA PESERTA PERTAMA",
		"email":"NAMA@gmail.com",
		"hp":"",
		"telegram":"idtelegram",
		"github":"idgithub"
		},
		{
		"nama":"NAMA PESERTA KEDUA",
		"email":"NAMA@gmail.com",
		"hp":"",
		"telegram":"idtelegram",
		"github":"idgithub"
		}
	],
	"ide":"LINK REPO IDE DI GITHUB"
}
```

