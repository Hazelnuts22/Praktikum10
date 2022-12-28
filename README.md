**Python String**

 ◉ String adalah jenis yang paling populer di Python.

 ◉ Untuk membuatnya hanya dengan melampirkan karakter dalam tanda kutip.

 ◉ Python memperlakukan tanda kutip tunggal (' ') sama dengan tanda kutip ganda (" ").

 ◉ Membuat string semudah memberi nilai pada sebuah variabel.
 
 **Latihan 1**
 ![209658422-4a63289e-1c2d-4b9a-972f-6362ccb0b952](https://user-images.githubusercontent.com/115677959/209827718-be1aa1df-edce-4e20-b0e2-30719132569d.png)
 
 **Penjelasan latihan**
 
 ◉ Untuk menghitung jumlah karakter, gunakan fungsi len().

    # Menghitung jumlah karakternya
    print(len(txt))

◉ Cara mengambil satu karakter pada string yaitu dengan menggunakan kurung siku [ ] dan deklarasi nomor di dalam kurung siku dengan urutan ARRAY dan menggunakan titik dua lalu masukan nomor ARRAY selanjutnya. Untuk mengambil karakter terakhir, gunakan index [-1]. Sedangkan untuk mengambil karakter index ke-2 sampai ke-4, gunakan index [2:5].

    # Mengambil karakter terakhir
    print(txt[-1])
    # Mengambil karakter index ke-2 sampai index ke-4 (llo)
    print(txt[2:5])

◉ Jika ingin menghilangkan spasi pada string, gunakan method replace(). Method replace() mengganti semua kemunculan string lama dengan yang baru atau paling banyak kemunculan.

◉ Di dalam method replace, kita dapat menggunakan 2 cara, yang pertama bisa menggunakan (txt.replace(" ", "")) dan kedua dengan cara (txt.replace(txt[5], "")).

    # Menghilangkan spasi pada text tersebut (HelloWorld)
    print(txt.replace(" ", ""))

◉ Untuk mengubah huruf menjadi besar, gunakan method upper(). Sedangkan jika ingin mengubah huruf menjadi kecil, gunakan method lower ().

    # Mengubah text menjadi huruf besar
    print(txt.upper())
    # Mengubah text menjadi huruf kecil
    print(txt.lower())

◉ Untuk mengganti karakter 'H' dengan karakter 'J', gunakan method replace().

    # Mengganti karakter H dengan karakter J
    print(txt.replace("H", "J"))
    print()
    
# Output Latihan
![Screenshot_20221228_212422](https://user-images.githubusercontent.com/115677959/209828574-d09220fa-a9bb-4725-90ce-b8f63834502f.png)
    
# Latihan 2
    
◉ Lengkapi Kode Beikut
![209659352-4e6ddc2b-c5b0-4409-ab5c-c3f108ce566d](https://user-images.githubusercontent.com/115677959/209828788-261e8eec-bf4b-4f21-92e4-fbe48c40d2e7.png)
    
    # Penjelasan Latihan 2

Untuk memasukkan variable ke dalam string, tambahkan kurung kurawal {} untuk menempatkan variable sebelumnya.

    umur = 24
    txt = "\nHello, nama saya john, dan umur saya adalah {0} tahun\n"

    print(txt.format(umur))
    
# Output Latihan 2

![Screenshot_20221228_212122](https://user-images.githubusercontent.com/115677959/209829098-6d3192d4-6feb-4920-9a5e-adeadcd02e17.png)


    




 
