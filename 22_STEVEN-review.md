
# REVIEW
## laravel
- penggunaan mvc, migrate dan seeder sudah bagus dan dapat di coba tanpa kesalahan
- middleware mungkin sudah bagus cuman ada error bawaan database
- **review : 6/10**

## validasi
- input tervalidasi hanya saat login dan register.
- **review : 5/10**

## responses
- tidak ada response success yang berhasil keluar akibat error database (walaupun berhasil register)
- tidak ada error handling. error mentah" di tampilkan
- **review : 3/10**

## flow 
(saya ngk tau soal)
- code sudah bagus perlu menambahkan error handling dan response yang sesuai pada client app.
- **review : 5/10**


## crud
- selain register (error jg sebenarnya) tidak ada crud yang berhasil di lakukan
- **review : 2/10**

## OVERAL
- perhatikan error dan implement error handling dan response yang sesuai
- apa bila ada perubahan pada database mohon migrationnya di buat kembali sesuai kebutuhan
- login, dan CRUD notes tidak bisa diakses karena error terhadap table personal_access_token di database
- **review : 5/10**
