# TugasPratikum06

assalamuallaikum ....sahabat kali ini kita akan membuat sebuah program tentang nilai data mahsiswa dengan menggunakan dectionary ...berikut disini adalah code atau rumus membuatnya

print("PROGRAM INPUT NILAI") print("===================")

while True: print("") c = input("L)ihat, T)ambah, U)bah, H)apus, C)ari, K)eluar: ") if c.lower() == 'l': break print("Daftar Nilai") print("========================================================================") print("| No | NIM | NAMA | TUGAS | UTS | UAS | AKHIR |") print("========================================================================") print("| TIDAK ADA DATA |") print("========================================================================") while True: print("") c = input("L)ihat, T)ambah, U)bah, H)apus, C)ari, K)eluar: ") if c.lower() == 't': break print("Tambah Data") nilai = [] nim = input("NIM: ") nama = input("Nama: ") nilaiUts = int(input("Nilai UTS: ")) nilaiUas = int(input("Nilai UAS: ")) nilaiTugas = int(input("Nilai Tugas: ")) nilaiAkhir = (nilaiUts * 35/100) + (nilaiUas * 35/100) + (nilaiTugas * 30/100)

nilai.append([nama, nim, nilaiTugas, nilaiUts, nilaiUas, int(nilaiAkhir)])

while True: print("") c = input("L)ihat, T)ambah, U)bah, H)apus, C)ari, K)eluar: ") if c.lower() == 'l': break print("\n Daftar Nilai ") print("========================================================================") print("| No | NIM | NAMA | TUGAS | UTS | UAS | AKHIR |") print("========================================================================") i = 0 for item in nilai: i += 1 print("| {no:2d} |{nim:12s}| {nama:9s} | {nilaiTugas:5d} | {nilaiUts:5d} | {nilaiUas:5d} | {nilaiAkhir:6.2f} |" .format(no=i, nim=item[0], nama=item[1], nilaiTugas=item[2], nilaiUts=item[3], nilaiUas=item[4], nilaiAkhir=item[5])) print("========================================================================")

-jika kalau sudah memasukan code tersebut di software phycram(phyton) silahkan Di Run silahkan kelik ctrl+shift+F10 atau klik kanan Run Berikut disini adalah gambaran input outputnya.

## Gambar Input
![input end](https://github.com/KikiPanceko05/TugasPratikum06/blob/master/inpu2.PNG)
![input end](https://github.com/KikiPanceko05/TugasPratikum06/blob/master/input3.PNG)
## Gambar output
![input end](https://github.com/KikiPanceko05/TugasPratikum06/blob/master/screenshot%20input.PNG)
![input end](https://github.com/KikiPanceko05/TugasPratikum06/blob/master/input.PNG)
## Gambar Flowchart
![input end](https://github.com/KikiPanceko05/TugasPratikum06/blob/master/tugas6flowchart.png)
