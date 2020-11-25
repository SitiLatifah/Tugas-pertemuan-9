# Tugas-pertemuan-9
# labs04andLabs05
**Nama	   	: Siti Latifah** <br>
**Nim	  	  : 312010321** <br>
**Kelas	  	: TI.20.A2** <br>
**Matkul	  : Bahasa Pemrograman** <br>

# Praktikum 4
## Latihan 4
![Screenshot (51)](https://user-images.githubusercontent.com/73010098/100236679-8fbfa700-2f60-11eb-8d48-7044da88b716.png)

## Syntax

```python

print(45*'=')
nilai = [2, 4, 6, 8, 10 ]

#Akses List
#print semua elemen
print('print semua elemen :', nilai)
#print elemen ke 3
print('Tampilkan elemen ke 3 :', nilai[3])
#print elemen ke 2 sampai elemen ke 4
print('Tampilkan elemen ke 2 sampai ke 4 :', nilai[1:4])
#print elemen teraksir
print('Tampilkan elemen Terakhir :',nilai[4] )  
print(45*'=')
#Ubah elemen list
#ubah elemen ke 4 dengan nilai lain
nilai[3]=14
print('ubah elemen ke 4:',nilai)
#ubah elemen ke 4 sampai terakhir
nilai[3:5]=[16, 18]
print('ubah elemen ke 4 sampai terakhir:',nilai)
print(45*'=')
#Menambah Elemen List
ListA = [10, 20, 30, 40, 50]
ListB =[100, 150, 200,]
print("ListA :",ListA)
print("ListB :",ListB)
print('Menambahkan ListB dengan data string : ',ListB)
ListC = ListA + ListB
print("Menggabungkan ListA dan ListB : ",ListC)
```
## OUTPUT
![Screenshot (39)](https://user-images.githubusercontent.com/73010098/100231492-ac0c1580-2f59-11eb-8cab-2baee2b94d6e.png)

## Tugas Praktikum 4
![Screenshot (40)](https://user-images.githubusercontent.com/73010098/100231831-2046b900-2f5a-11eb-8cc4-2d6e0b8e2670.png)

## Syntax
```python
data = []
while True :
	nama	= input	("Nama 		:")
	nim		= input ("NIM 		:")
	tugas	= int(input("Nilai Tugas        :"))
	uts 	= int(input("Nilai UTS 	:"))
	uas 	= int(input("Nilai UAS 	:"))
	nilaiakhir = float(tugas)*30/100+(uts)*35/100+(uas)*35/100
	data.append ([nama,nim,tugas,uts,uas,nilaiakhir])
	lagi = input ("Tambah lagi (y/t)?")
	if lagi.lower() =="t":
		break
#prosess hasil dari lopping
print ("========================|=======DATA MAHASISWA==========|==============================")
print ("=======================================================================================")
print ("| No |	 Nama 	| NIM 	| TUGAS | UTS 	|	 UAS 	|	 NILAI AKHIR 	|")
print ("=======================================================================================")
i=0
for x in data:
	i+=1
	print ("|{6:2d}| {0:9s}| {1:6s}| {2:6d}|{3:4d} |	 {4:5d}	 | 	{5:13.2f} 	|"\
		.format (x[0][:9],x[1][:6],x[2],x[3],x[4],x[5],i))
```

## Flowchart
<img width="408" alt="100194684-b8c44580-2f28-11eb-85c2-8195000946e1" src="https://user-images.githubusercontent.com/73010098/100236384-2d66a680-2f60-11eb-9814-e26312a116f1.png">

## Berikut Hasil Output Data Mahasiswa
![Screenshot (43)](https://user-images.githubusercontent.com/73010098/100233100-d363e200-2f5b-11eb-9a62-fcc5c64f72b5.png)
![Screenshot (41)](https://user-images.githubusercontent.com/73010098/100233116-db238680-2f5b-11eb-9fb0-2b1ccc7c1cef.png)

## Praktikum 5
# Latihan 5
![Screenshot (45)](https://user-images.githubusercontent.com/73010098/100233819-d3181680-2f5c-11eb-8a73-e31c0dff2564.png)

## Syntax
```python
#Dictionary
daftarKontak = {"Nama":"Nomer Telpon"}
kontak       = {'Ari':'081267888', 'Dina' : '087677776'}

#print
print(30*"═")
print("    Nama    |  Nomor Telepon  ") #prinr daftarkontak
print(30*"-")
print("   # Ari    | ", kontak['Ari']) #print kontak Ari
print("   # Dina   | ", kontak['Dina']) #print kontak Dina
print(30*"═")

#Tampilkan kontaknya Ari
print("Tampilkan kontaknya Ari")
print("    Ari     | ", kontak['Ari']) #print kontak Ari
print(30*"═")
#Tambah kontak baru dengan nama Riko, nomor 087654544
print("Tambah kontak baru dengan nama Riko, nomor 087654544")
kontak['Riko'] = '087654544'
print("    Riko    | ", kontak['Riko'])
print(30*"═")

#Ubah kontak Dina dengan nomor baru 088999776
print("Ubah kontak Dina dengan nomor baru 088999776")
kontak['Dina'] = '088999776'
print("    Dina    | ", kontak['Dina'])
print(30*"═")

#Tampilkan semua Nama
print("Tampilkan semua Nama")
print(kontak.keys())
print(30*"═")

#Tampilkan semua Nomor
print("Tampilkan semua Nomor")
print(kontak.values())
print(30*"═")

#Tampilkan daftar Nama dan nomornya
print("Tampilkan daftar Nama dan nomornya")
print(kontak.items())
print(30*"═")

#MengHapus kontak Dina
print("Hapus kontak Dina")
kontak.pop('Dina')
print(kontak.items())
print(30*"═")
```
## Output
![Screenshot (46)](https://user-images.githubusercontent.com/73010098/100234388-9862ae00-2f5d-11eb-8319-1c14af500e22.png)
![Screenshot (47)](https://user-images.githubusercontent.com/73010098/100234393-9a2c7180-2f5d-11eb-8424-a0af7a652043.png)

## Tugas Praktikum 5
![Screenshot (44)](https://user-images.githubusercontent.com/73010098/100234473-b9c39a00-2f5d-11eb-9c20-e730b588d273.png)
## Penjelasan Praktikum 5
1) Penggunaan if c.lower()

if c.lower() fungsinya apabila user menginputkan denga huruf besar, maka otomatis akan menjadi huruf kecil sehingga kondisi yang digunakan tercapai. Contoh :

if c.lower() == `q`

2) Penggunaan while True

while True berfungsi untuk mendeteksi jika format yang diinputkan bukan berupa type maka akan muncul error

3) Penggunaan else

Fungsi else jika tidak error dan type yang dimasukan sesuai maka proses while True

4) Penggunaan valuveError

   Fungsinya apabila diinputkan bukan berupa type maka hasil nya error (valueError) 
   
## Syntax


```python
P = print
print("Masukan data mahasiswa")
print("~~~~~~~~~~~~~~~~~~~~~~")
nama = input("Masukan Nama Anda :")
nim = int(input("Masukan NIM Anda :"))
nilai_tugas = int(input("Masukan nilai tugas :"))
nilai_uts = int(input("Masukan nilai uts :"))
nilai_uas = int(input("Masukan nilai uas :"))
while True:
    P("")
    P("")
    c = input("L)ihat, T)ambah, U)bah, H)apus, C)ari, K)eluar: ")
    if c.lower() == 'q':
        break
    elif c.lower() == 'l':
        i = open('database.txt','r').read().splitlines()
        P(" ╔═════════════════════════════════════════════════════════════════════╗")
        P(" ╠════════════════════════════ DAFTAR KONTAK ══════════════════════════╣")
        P(" ╠══════════════════╦══════════════════╦═══════╦═══════╦═══════╦═══════╣")
        P(" ║      NAMA        ║       NIM        ║ TUGAS ║  UTS  ║  UAS  ║ AKHIR ║")
        P(" ╠══════════════════╬══════════════════╬═══════╬═══════╬═══════╬═══════╣")
        for l in i:
            if l == '':
                pass
            else:
                l1 = l.replace('Nama : ','').replace('Nim : ','').replace('Tugas : ','').replace('UTS : ','').replace('UAS : ','').replace('Akhir : ','')
                na,ni,tu,uts,uas,akhir = l1.strip().split('|')
                P((' ║ ')+(na[:15]).ljust(17,'.')+('║ ')+(ni).ljust(17)+('║ ')+(tu).ljust(6)+('║ ')+(uts).ljust(6)+('║ ')+(uas).ljust(6)+('║ ')+(akhir).ljust(6)+('║'))
        P(" ╚══════════════════╩══════════════════╩═══════╩═══════╩═══════╩═══════╝")
    elif c.lower() == 'c':
        cari = input(' Mencari : ')
        i = open('database.txt','r').read().splitlines()
        P(" ╔═════════════════════════════════════════════════════════════════════╗")
        P(" ╠════════════════════════════ DAFTAR KONTAK ══════════════════════════╣")
        P(" ╠══════════════════╦══════════════════╦═══════╦═══════╦═══════╦═══════╣")
        P(" ║      NAMA        ║       NIM        ║ TUGAS ║  UTS  ║  UAS  ║ AKHIR ║")
        P(" ╠══════════════════╬══════════════════╬═══════╬═══════╬═══════╬═══════╣")
        for l in i:
            if l == '':
                pass
            elif cari in l:
                l1 = l.replace('Nama : ','').replace('Nim : ','').replace('Tugas : ','').replace('UTS : ','').replace('UAS : ','').replace('Akhir : ','')
                na,ni,tu,uts,uas,akhir = l1.strip().split('|')
                P((' ║ ')+(na).ljust(17)+('║ ')+(ni).ljust(17)+('║ ')+(tu).ljust(6)+('║ ')+(uts).ljust(6)+('║ ')+(uas).ljust(6)+('║ ')+(akhir).ljust(6)+('║'))
        P(" ╚══════════════════╩══════════════════╩═══════╩═══════╩═══════╩═══════╝")
    elif c.lower() == 'h':
        u = open('database.txt','r').read().splitlines()
        target = input(' Masukan Nama : ')
        nm = []
        for l in u:
            if l == '':
                pass
            else:
                l1 = l.replace('Nama : ','').replace('Nim : ','').replace('Tugas : ','').replace('UTS : ','').replace('UAS : ','').replace('Akhir : ','')
                na,ni,tu,uts,uas,akhir = l1.strip().split('|')
                if str(na) == str(target):
                    P('BERHASIL MENGHAPUS Data %s'%(target))
                    pass
                else:
                    nm.append(str(l)+'\n')
        new = open('database.txt','w')
        new.write(str(nm))
        new.close()
        new = open('database.txt','r').read().splitlines()
        new1 = open('database.txt','w')
        new1.close()
        new2 = open('database.txt','a')
        for i in new:
            i2 = i.replace("['","").replace("\\n', '", "\n").replace("']","").replace("\\n",'')
            new2.write(i2)
        new2.close()
    elif c.lower() == 'u':
        u = open('database.txt','r').read().splitlines()
        target = input(' Masukan Nama : ')
        nm = []
        for l in u:
            if l == '':
                pass
            else:
                l1 = l.replace('Nama : ','').replace('Nim : ','').replace('Tugas : ','').replace('UTS : ','').replace('UAS : ','').replace('Akhir : ','')
                na,ni,tu,uts,uas,akhir = l1.strip().split('|')
                if na == target:
                    P(' Mengedit Data %s'%(target))
                    while (True):
                        nama = input(" Nama : ")
                        if nama == '':
                            P(' Masukan dengan Nama Dengan Benar')
                        else:
                            break
                    while (True):
                        try:
                            nim  = int(input(" NIM  : "))
                            if nim == '':
                                P(' Masukan Nim dengan Angka')
                        except ValueError:
                            P(' Masukan Nim dengan Angka')
                        else:
                            break
                    while (True):
                        try:
                            tugas  = int(input(" TUGAS  : "))
                            if tugas == '':
                                P(' Masukan TUGAS dengan Angka')
                        except ValueError:
                            P(' Masukan TUGAS dengan Angka')
                        else:
                            break
                    while (True):
                        try:
                            uts  = int(input(" UTS  : "))
                            if uts == '':
                                P(' Masukan UTS dengan Angka')
                        except ValueError:
                            P(' Masukan UTS dengan Angka')
                        else:
                            break
                    while (True):
                        try:
                            uas  = int(input(" UAS  : "))
                            if uas == '':
                                P(' Masukan UAS dengan Angka')
                        except ValueError:
                            P(' Masukan UAS dengan Angka')
                        else:
                            break
                    akhir = round((float(tugas) * 0.3)+(float(uts) * 0.35)+(float(uas) * 0.35),2)
                    edit  =('Nama : '+nama+'|Nim : '+str(nim)+'|Tugas : '+str(tugas)+'|UTS : '+str(uts)+'|UAS : '+str(uas)+"|Akhir : "+str(akhir)+'\n')
                    nm.append(edit+'\n')
                else:
                    nm.append(str(l)+'\n')
        new = open('database.txt','w')
        new.write(str(nm))
        new.close()
        new = open('database.txt','r').read().splitlines()
        new1 = open('database.txt','w')
        new1.close()
        new2 = open('database.txt','a')
        for i in new:
            i2 = i.replace("['","").replace("\\n', '", "\n").replace("']","").replace("\\n","\n")
            new2.write(i2+'\n')
        new2.close()
    elif c.lower() == 't':
        i = open('database.txt','a')
        P(" Tambah Kontak")
        while (True):
            nama = input(" Nama : ")
            if nama == '':
                P(' Masukan dengan Nama Dengan Benar')
            else:
                break
        while (True):
            try:
                nim  = int(input(" NIM  : "))
                if nim == '':
                    P(' Masukan Nim dengan Angka')
            except ValueError:
                P(' Masukan Nim dengan Angka')
            else:
                break
        while (True):
            try:
                tugas  = int(input(" TUGAS  : "))
                if tugas == '':
                    P(' Masukan TUGAS dengan Angka')
            except ValueError:
                P(' Masukan TUGAS dengan Angka')
            else:
                break
        while (True):
            try:
                uts  = int(input(" UTS  : "))
                if uts == '':
                    P(' Masukan UTS dengan Angka')
            except ValueError:
                P(' Masukan UTS dengan Angka')
            else:
                break
        while (True):
            try:
                uas  = int(input(" UAS  : "))
                if uas == '':
                    P(' Masukan UAS dengan Angka')
            except ValueError:
                P(' Masukan UAS dengan Angka')
            else:
                break
        akhir = round((float(tugas) * 0.3)+(float(uts) * 0.35)+(float(uas) * 0.35),2)
        i.write('\nNama : '+nama+'|Nim : '+str(nim)+'|Tugas : '+str(tugas)+'|UTS : '+str(uts)+'|UAS : '+str(uas)+"|Akhir : "+str(akhir)+'\n')
        i.close()
    else:
        P("Silahkan pilih menu yang tersedia...")
```
## Ouput
![Screenshot (48)](https://user-images.githubusercontent.com/73010098/100236228-f42e3680-2f5f-11eb-9973-7ff908c0ad4c.png)

## Author Siti Latifah-312010321







