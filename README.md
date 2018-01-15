# install-nodejs
intall nodejs terminal [ubuntu]
Debian dan Ubuntu berbasis distribusi Linux
Juga termasuk: Linux Mint , Linux Mint Debian Edition (LMDE) , elementaryOS , pesta pada Windows dan lain-lain.

Node.js tersedia dari NodeSource Debian dan Ubuntu distribusi biner repositori (sebelumnya Chris Lea Launchpad PPA). Dukungan untuk repositori ini, bersama dengan script-nya, dapat ditemukan di GitHub di nodesource / distribusi .

CATATAN: Jika Anda menggunakan Ubuntu Precise atau Debian Wheezy, Anda mungkin ingin membaca tentang menjalankan Node.js> = 6.x pada distro yang lebih tua .

curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -

sudo apt-get install -y nodejs

## Atau, untuk Node.js 9:

curl -sL https://deb.nodesource.com/setup_9.x | sudo -E bash -

sudo apt-get install -y nodejs

Opsional : menginstal perangkat membangun

Untuk mengkompilasi dan menginstal addons asli dari NPM Anda juga mungkin perlu menginstal alat membangun:

sudo apt-get install -y build-essential
arsitektur yang tersedia:

yang i386 (32 a bit)
amd64 (64-bit)
armhf (ARM 32-bit hard-float, ARMv7 dan up: arm-linux-gnueabihf )
Didukung versi Ubuntu:

Ubuntu 14.04 LTS (Trusty Tahr)
Ubuntu 16.04 LTS (besar Xerus)
versi Debian didukung:

Debian 7 (mengi)
Debian 8 / stabil (jessie)
Pengujian Debian (peregangan, alias ke jessie)
Debian yang tidak stabil (sid)
Sebuah paket Node.js juga tersedia di repo resmi untuk Debian Sid (tidak stabil), Jessie (pengujian) dan Wheezy (serak-backports) sebagai "nodejs". Hanya menginstal nodejsbiner.

The paket nodejs-warisan menginstal nodesymlink yang sangat dibutuhkan oleh banyak modul untuk membangun dan menjalankan dengan benar. The Node.js modul yang tersedia dalam repositori resmi distribusi tidak membutuhkannya.

Didukung versi Linux Mint:

Linux Mint 17 "Qiana" (via Ubuntu 14.04 LTS)
Linux Mint 17.1 "Rebecca" (via Ubuntu 14.04 LTS)
Linux Mint 17.2 "Rafaela" (via Ubuntu 14.04 LTS)
Linux Mint Debian Edition (LMDE) 2 "Betsy" (via Debian 8)
Didukung SD OS versi:

elementary OS Freya (via Ubuntu 14.04 LTS)
Didukung versi Trisquel:

Trisquel 7 "Belenos" (via Ubuntu 14.04 LTS)
Versi BOSS didukung:

Bos 5.0 "Anok" (Via Debian 7)
