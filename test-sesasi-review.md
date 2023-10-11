
# REVIEW
## laravel
- tidak menggunakan model migration ( kalau tidak harusnya menyediakan sql atau command script untuk pemasukan tabel pada basis data)
- struktur belum teratur, usahakan untuk code **html** tetap di taruh di view. back end khusus nya API tidak digunakan hanya untuk web aplikasi atau html *relatet* tampilan
- disini diminta untuk backend dan membuat sebuah API tidak perlu tampilan (tampilan bisa jadi nilai tambah klo seandainya di eksekusi dengan baik. contoh mana tampilan untuk registernya ?
- **review : 1/10 : sesuai keinginan**

## validasi
- input login tervalidasi
- tidak ada user, tidak bisa register. input yang lainnya tidak bisa di test
- **review : 3/10 : sesuai keinginan**

## responses
- tidak ada user tidak bisa login harusnya ada register, response success tidak bisa di dapat.
- response failure tidak terhandle, error tertera jelas seakan" masih dalam mode developer
- **review : 2/10 : kurang bagus**

## flow 
(saya ngk tau soal)
- dilihat dari code kelihatannya setiap fungsi yang diinginkan ada (tidak bisa di test)
- di biasakan untuk memisahkan database berasarak model (struktur MVC). jangan bikin general"-an model untuk object internal.
- authentikasi kelihatannya berjalan cuman ngk bisa login (ngk ada user, ngk ada register)
- **review : 3/10 : sesuai keinginan (mungkin)**


## crud
- tidak ada yang bisa di test tanpa campur tangan
- **review : 0/10 : sesuai keinginan**

## OVERAL
- bisa coba memahami kembali MVC
- bisa coba memahami dalam kegunaan model (terlebih terhadap database optional/ di tentukan sendiri oleh anda)
- pelajari untuk ngehandle error untuk menjaga response balikan dari backend pada frontend (client app)
- **review : 3/10** good effort
