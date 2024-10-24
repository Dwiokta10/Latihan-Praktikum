# Program Mencari Bilangan Terbesar
Program sederhana untuk mencari nilai terbesar dari sekumpulan bilangan yang dimasukkan oleh pengguna menggunakan loop while True dan break statement.
## Deskripsi Program
Program ini dibuat menggunakan bahasa Python dengan fitur:

- Menggunakan while True untuk perulangan tak terbatas
- Menggunakan break statement untuk menghentikan program
- Membandingkan setiap input dengan nilai maksimum yang tersimpan
- Menampilkan bilangan terbesar yang ditemukan

## Flowchart Programan
![Flowchart](Flowchat.png)

## Kode Program
```python
max = 0
bilangan = int(input("masukan bilangan :"))
while bilangan != 0 :
    if bilangan > max :
        max = bilangan 
    bilangan = int(input("masukan bilangan :"))
    
print (f"bilangan terbesar= {max}")
```

## Output Program
````
PS C:\Users\acer> python -u "c:\Users\acer\Documents\KULIAH\PEMROGRAMAN\Latihan 3\code program.py"
masukan bilangan :75
masukan bilangan :120
masukan bilangan :230
masukan bilangan :460
masukan bilangan :600
masukan bilangan :0
bilangan terbesar= 600
````

## Cara kerja program
Pada tahap awal PYTHON meminta pengguna memasukkan bilangan berulang kali. Jika bilangan lebih besar dari nilai sebelumnya, bilangan tersebut disimpan sebagai yang terbesar. Proses berhenti saat pengguna memasukkan 0, dan program mencetak bilangan terbesar yang telah dimasukkan.
