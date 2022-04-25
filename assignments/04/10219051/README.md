## question 1
Baca penjelasan mengenai kode di atas pada <https://dudung.github.io/bugx/0026/> atau pada pertemuan kuliah terkait.

### answer 1
Apakah penjelasan kode dia atas sudah dibaca atau hadir pada kuliah?
```
sudah, pak
```

## question 2
Modifikasi program yang diberikan sehingga dapat menggambarkan gelombang yang merambat ke kanan dengan panjang gelombang &lambda; = 2 m dan periode T = 2 s. Perolehlah pula berkas gif hasilnya.

### answer 2
Potongan kode yang perlu disisipkan adalah
```
y = np.sin(2 * np.pi * (x - 0.01 * i))
```
dan hasil berkas gifnya adalah \
![gif file from simulation wave to right]()


## question 3
Modifikasi program yang diberikan sehingga dapat menggambarkan gelombang yang merambat ke kiri dengan panjang gelombang &lambda; = 2 m dan periode T = 2 s. Perolehlah pula berkas gif hasilnya.

### answer 3
Potongan kode yang perlu disisipkan adalah
```
y = np.sin(2 * np.pi * (x + 0.01 * i))
```
dan hasil berkas gifnya adalah \
![gif file from simulation wave to left]()


## question 4
Modifikasi program yang diberikan sehingga dapat menggambarkan gelombang stasioner yang tidak merambat dengan panjang gelombang &lambda; = 2 m dan periode T = 2 s. Perolehlah pula berkas gif hasilnya.

### answer 4
Potongan kode yang perlu disisipkan adalah
```
y = np.sin(2 * np.pi * x) * np.cos(2 * np.pi * 0.01 * i)
```
dan hasil berkas gifnya adalah \
![gif file from simulation wave stationary]()
