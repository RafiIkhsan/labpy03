**labpy03**
**latihan1**
```python
import random
n=str(input("masukan nilai N: "))
for x in range (1,6):
 print("data ke:",x,"=>",random.uniform(0.0,0.5))
print('selesai')
````

# penjelasan algoritma
- [x] PERULANGAN Perulangan dalam dalam bahasa pemrograman merupakan suatu pernyataan untuk menginstruksi komputer agar melakukan sesuatu secara berulang. Terdapat dua jenis perulangan dalam bahasa pemrograman python, yaitu perulangan dengan for dan while.
- [x] Perulangan for
Perulangan for disebut juga sebagai counted loop (perulangan yang terhitung), yaitu perintah yang dieksekusi secara berulang berdasarkan jumlah perulangan tertentu.
- [x] Perulangan while
Perulangan while disebut uncounted loop (perulangan yang tak terhitung), yaitu perulangan yang dilakukan berdasarkan kondisi tertentu selama nilai kondisi bernilai TRUE.
- [x] random() Pengacakan, pembangkit bilangan acak, atau random dapat digunakan untuk berbagai macam hal. Nilai random kadang dibutuhkan juga untuk menentukan suatu pilihan.
# output :
![image](https://user-images.githubusercontent.com/46708621/52990980-2468ad00-343d-11e9-9c98-ef481f34b7b3.png)

**latihan2**
```python
max=0
while True:
	a=int(input("masukan bilangan:"))
	if a ==0:
		break
	if a>max:
		max=a
print("bilangan terbesar:",max)
```

# penjelasan algoritma
- [x] Fungsi max di pemrograman python Fungsi max() adalah fungsi bulid-in untuk mencari nilai tertinggi. Fungsi ini dapat diberikan sebuah parameter berupa angka.
- [x] Perulangan while
Perulangan while disebut uncounted loop (perulangan yang tak terhitung), yaitu perulangan yang dilakukan berdasarkan kondisi tertentu selama nilai kondisi bernilai TRUE.
- [x] Break, pernyataan break digunakan untuk menghentikan proses perulangan pada kondisi tertentu.
# output :
