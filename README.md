# Latihan

##Tugas1
n = int(input("Choose ur number: "))

from random import random
a = random()

jumlah = n +1
start = 1
stop = jumlah
step = 1
for i in range(start,stop,step):
    print("Data Ke: ", i,"=>",(a))
print("Done")

###Tugas2
x = int()
y = 0
while x >= 0:
    x = int(input("Masukan Bilangan: "))
    if x > y:
     y = int(x)
    if x == 0:
     break
print("\n Angka Terbesar Adalah ",y)


####Tugas3
modal = 100000000
laba = 0
untung = 0
for i in range(1,9,1):
    if(i<3):
        laba = 0
        untung = untung + laba
    elif(i<5):
        laba = modal*1/100
        untung = untung + laba
    elif(i<8):
        laba = modal*5/100
        untung = untung + laba
    else:
        laba = modal*2/100
        untung = untung + laba
    print("Laba Bulan Ke- ",i,"Sebesar ",laba)
print("Total Laba: ", untung)
