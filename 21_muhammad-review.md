
# REVIEW
## laravel
- penggunaan mvc, migrate dan seeder sudah bagus dan dapat di coba tanpa kesalahan
- hanya mengimplementasikan basic middleware grouping (harusnya ada roles)
- **review : 8/10**

## validasi
- input notes tidak tervalidasi
- **review : 7/10**

## responses
- tidak ada api hanya web app
- error handling masih di biarin saja. usahakan untuk menggunaka try/catch dan menampilkan message sederhana pada web app
- **review : 7/10**

## flow 
(saya ngk tau soal)
- code nya rapih.
- flow MVC sudah terimplementasi
- biasakan untuk menambahkan error handling di setiap controller atau menambahkan middleware untuk handling unintended/intended error
- **review : 5/10**


## crud
- fitur delete user tidak bisa dilakukan (kalau mau bikin fitur delete terhadap tabel yg punya relationship. pastikan saat create db siapkan cascade on delete atau buat soft delete by code atau status)
- **review : 7/10**

## OVERAL
- program terlalu sederhana, feature yang diimplementasikan hanya untuk role user {
    CRUD user,
    CRUD notes,
}
- seharusnya ada implementasi roles untuk user dan notes management
- untuk program yang sederhana sebaiknya error handling dapat lebih diperhatikan.
- **review : 6/10**
