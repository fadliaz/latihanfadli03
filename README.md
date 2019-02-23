Latihan03

# MENCARI NILAI RANDOM #

1.( inport random ) Fungsi ini akan mengembalikan bilangan float random , dimana fungsi random tidak memiliki parameter masukan.
 
2. ( int(input("Masukan Nilai N :")) ) menangkap variabel dengan huruf N,dan mendata untuk integer

3. ( Fungsi range() ) berfungsi untuk mengembalikan deret integer berurut pada range yang ditentukan dari start sampai stop.
 
4. ( b = random.uniform(0.0,0.5) ) membuat bilangan random yang menghasilkan 0.0 s/d 0.5
 
5. print ("Data ke : ",a,"==>",b) ,, print data ke : a = index looping b = angka random yang sudah di buat varibelnya

6. ( print("Selesai") )  membuat kata akhir setelah dikerjakan yang akan muncul " Hasil"
 
7. ( while jawab == "lanjutkan" ) itu menandakan bahwa perulangan terjadi  ( Hitung +=1 ) itu mengubah atau menambahkan dari bilangan hitung = 0
 
8. ( if jawab == "lanjuttkan" : ) hanya jika menjawab bilangan
 
9. ( Finish ) untuk berrhenti jika ada syntax yang ia berikan.
 
 beriku ini kodingan nya
 ```
import random

jumlah = int(input("Masukan Nilai N :"))
for i in range(jumlah):
        i=random.uniform(0.0,0.5)
        print("masukan data : 1 =>" , i)

jawab  ="betul"
hitung = 0
while(jawab) :
    hitung +=1
    jawab =input("-----Fhinis-----") 
 ```
 
 
 # MENCAR BILANGAN RANDOM #
 
 1. ( print("Masukan Bilangan Random,dan berhenti dalam angka 0")  ) untuk mencetak bilangan random dan berakhir di bilangna random 0
 
 2. ( b=0 ) variabel akhir random 0 
  
 3. ( While True : ) perulangan jika benar 
 
 4. ( a = int(input("Masukan bilangan")) )  untuk mengambil data dari integer dalam input yang akan dirandom

 5. ( b = angka ) jika b=max  memanggil angka maka akan muncul sebagai angka max 
 
 6. ( break ) jika sudah dipanggil ia akan berhenti
 
 7. ( if b == 0: ) jika if b==0: maka angka akan berhenti 
 
 8. ( break ) syntax untuk berhenti 
 
 9. ( print('-----selesai-----')  )untuk variasi untuk mempercantik
 
 
 berikut ini kodingan nya
 
 ```
 print("Masukan Bilangan Random,dan berhenti dalam angka 0")

b= 0
while True:
        angka = int(input("Masukan Bilangan : "))
        b = angka
        if b == 0:
                break
print('-----selesai-----')
 ```
 
 
 
 # Menghitung laba Perusahaan dengan modal Rp 100.000.000
 
 Algoritma
 
1.  ( a = 100.000.000 )  variabel awalnya adalah 100000000

2.  ( for i in range(1,9) ) untuk membuat huruf i dengan jarak (1,9)

3.  ( if(x>=1 and x<=2):- ) jika x lebih besar = 1 dan kecil dari 2 ia akan menghasilkan bilangan seperti b=a*0

4.  ( total=a+b+c+c+d+d+d+e ) ini adalah hasilnya

5.  ( print("\nTotal :",total) ) untuk mengetahui hasil

 
 berikut ini kodingan nya 
 
 ```
 print("Menghitung laba perusahaan dengan modal awal RP 100.000.000")
print("")
print('note')
print('Bulan pertama dan ke 2 = 0%')
print('pada bulan ke 3 = 1%')
print('pada bulan ke 5 = 5%')
print('pada bulan ke 8 = 8%')
print("")

a = 100000000
for x in range(1,9):
    if(x>=1 and x<=2):
        b=a*0
        print("laba bulan ke - ",x," : " ,b)
    if (x>=3 and x<=4):
        c=a*0.1
        print("laba bulan  -",x," : " ,c)
    if(x>=5 and x<=7):
        d=a*0.5
        print("laba bulan  -",x," : ",d)
    if(x==8):
        e=a*0.2
        print("laba bulan  -",x," : ",c)
total=a+b+c+c+d+d+d+e
print("\ntotal :",total)
 ```
 
 
