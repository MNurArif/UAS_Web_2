# UAS_Web_2
Project E_inventory Menggunakan CodeIgniter 4
## Database
```text
Database e_inventory
User
Kategori
Supplier
Barang
```

<img width="1920" height="838" alt="image" src="https://github.com/user-attachments/assets/c3e548b1-8c53-4e5e-a67e-bc9e635589a9" />

## API
ini adalah Error (401) jika tidak memasukan token

<img width="975" height="511" alt="image" src="https://github.com/user-attachments/assets/c31d16a3-1624-4ee9-88d0-f862647c3a2b" />

Cara mendapatkan tokennya itu bisa melalui login

<img width="975" height="511" alt="image" src="https://github.com/user-attachments/assets/4f77463b-f0cb-4a90-980c-06b531d1232e" />

## Halaman Login
Harus memasukan username dan password yang sudah di input di database (MySQL)
```text
username : admin
password : admin123
```

<img width="975" height="426" alt="image" src="https://github.com/user-attachments/assets/809fea1f-82ea-46c8-bdf4-5915b361da93" />

## Halaman Dashboard
Disini Terdapat Kategori, Supplier, Barang dan Logout

<img width="975" height="426" alt="image" src="https://github.com/user-attachments/assets/69044383-1fa9-4996-be9d-ad39cded3870" />

## Halaman Kategori
Bisa menambah kategori lagi sesuai yang di inginkan dan untuk aksinya bisa di edit atau pun di hapus

<img width="1920" height="838" alt="image" src="https://github.com/user-attachments/assets/95449062-381a-494e-a154-da32c8cb446e" />

## Halaman Supplier
Berbeda dengan kategori ketika menambahkan supplier terdapat nama supplier, alamat dan no.telp

<img width="1920" height="838" alt="image" src="https://github.com/user-attachments/assets/9acb9700-9352-4227-889d-8d93acc806ac" />

## Halaman Barang
Semua data yang ada di halaman kategori dan supplier di satukan di halaman ini

<img width="1920" height="838" alt="image" src="https://github.com/user-attachments/assets/205c3200-585c-4ce3-8852-31ce2dc1da5a" />

## Instal CodeIgniter
Pastikan sudah menginstal xampp lanjut start apache dan mySQL sampai status berwarna hijau
```bash
https://www.apachefriends.org/download.html
```

<img width="671" height="376" alt="image" src="https://github.com/user-attachments/assets/310b5187-5412-477c-b164-3aa48a451da9" />

dan juga composer
```bash
https://getcomposer.org/
```

buka CMD
```bash
cd C:\xampp\htdocs
```
```bash
composer create-project codeigniter4/appstarter nama-project
```

## Server
Pastikan server di cmd harus berjalan terlebih dahulu
```bash
php spark serve
```

<img width="1280" height="166" alt="image" src="https://github.com/user-attachments/assets/4f2b8cda-eeb3-4fcc-906f-1c1c825980c6" />
