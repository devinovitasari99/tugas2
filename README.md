# tugas2
Lab 1
Penggunaan end
Di dalam fungsi "print()" di dalam bahasa python terdapat parameter "end". Parameter "end" adalah parameter yang digunakan untuk memasukan string atau karakter apapun untuk mengakhiri sebuah statement. Secara default jika kita melakukan print dalam python, output akan dicetak dalam baris baru. Tapi jika kita memasukan fungsi "end" maka hasil output tidak akan langsung berada di garis baru. Contoh kode :
![Output end](https://github.com/devinovitasari99/tugas2/blob/master/picture/lab1.PNG)
# Penggunaan Separator
Separator "sep" dalam python digunakan sebagai pembatas antara output yang dihasilkan.

Contoh Kode :
![Output end](https://github.com/devinovitasari99/tugas2/blob/master/picture/lab1%2Cb.PNG)
Penggunaan string format
String format digunakan ketika kita ingin mengatur dan memposiskan print output menjadi sedemikian rupa.
Contoh kode :
![Output end](https://github.com/devinovitasari99/tugas2/blob/master/picture/lab1%2Cc.PNG)
Output:
![Output end](https://github.com/devinovitasari99/tugas2/blob/master/picture/Capture1.PNG)
kita akan membuat Outputnya menjadi seperti berikut:
![Output end](https://github.com/devinovitasari99/tugas2/blob/master/picture/Capture2.PNG)
Lab 2
Lab2 membahas tentang bagaimana memasukan input, menghitung dan mengubah tipe data serta membuat format print yang akan dicetak ke output.
Contoh Kode:
![Output end](https://github.com/devinovitasari99/tugas2/blob/master/picture/ss.PNG)
Output yang didapat:
![Output end](https://github.com/devinovitasari99/tugas2/blob/master/picture/Capture.PNG)
Input dimasukan dengan cara menjalankan program terlebih dahulu, kemudian data dimasukan oleh user (Lihat angka 10 & 6 hijau) dengan diikuti keterangan berupa string "masukan nilai a:". Lalu input di cetak menggunakan fungsi "print()", disertai keterangan "hasil penggabungan" seperti berikut. Kode :
print('hasil penggabungan {1} & {0} =%d'.format(a,b))
Input dicetak kembali disertai dengan format baru menggunakan fungsi "format". Output dari print ini berbentuk tipe data string. Jadi bila kita menjumlahkan input "a" dan "b" dengan operator "+" maka output dari penjumlahan tersebut akan menghasilkan "106" (10 dan 6). Sedangkan "%d" yang seharusnya hanya dilakukan proses dan tidak di cetak ke output, menjadi tercetak kedalam bentuk string atau text (lihat hasil output di atas). Tetapi jika kita menggunakan tipe data, misalnya "/" maka akan terjadi error. Ini disebabkan karena tipe data yang berbentuk string atau text tidak bisa di jumlahkan dengan operator tersebut. Maka dari itu kita perlu mengkonversikan atau mengubah tipe data tersebut menjadi tipe data bersifat bilangan atau angka, misalnya integer atau float.
a = int(a)
b = int(b)
Perintah di atas akan mengkonversikan tipe data sebelumnya ke bentuk tipe data integer. Dengan ini kita bisa menjumlahkan input sebagai angka.
print('hasil penjumlahan {1} & {0} =%d'.format(a,b)%(a+b))
Perintah di atas digunakan untuk mencetak, menghitung dan memformat kembali output yang akan dihasilkan. "{1}" dan "{0}" adalah placeholder dan "%d" adalah perintah untuk mencetak output ke dalam bentuk desimal. Kita bisa mengubah "%d" menjadi, misalnya "%f", dan output yang akan di hasilkan akan dicetak dalam bentuk float.
