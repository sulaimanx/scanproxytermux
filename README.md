# Scan Proxy di termux
- Tools Scan Proxy
### Note
- **Password:** `Tanggal Di Hp Kalian Dan Ditambahkan 00 Dibelakangnya`
- **Contoh:** `Tanggal Di Hp Saya Sekarang 25,Maka Password Yang Ditulis 2500`
### Cara Menginstall
- **Pertama-tama Kalian Harus Menjalankan Kode Berikut**
```
pkg update && pkg upgrade
pkg install python
pkg install python2
pip2 install --upgrade pip
apt install git
pip2 install http.client
pip2 install requests
```
- **Jika Sudah,Jalankan Kode Berikut Untuk Menjalankan Tools `ScanProxy`**
```
git clone https://github.com/sulaimanx/scanproxytermux
cd scanproxytermux
python -m pip install -r requirements.txt
python2 proxy.py
```
