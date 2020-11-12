# DataMiningTugas3
Proses:

Tool yang dipakai pada proses ini mengunakan Jupyter Notebook untuk script dan WEKA untuk mengubah file csv menjadi Arff.
1.	Proses Data WBDC.
Hal pertama yang dilakukan untuk data ini adalah memberikan nama atribut pada table.
Saya menggunkan Bahasa Python untuk memberikan Nama atribut dan merubah data.

![image](https://user-images.githubusercontent.com/50357969/95885109-1486a500-0da7-11eb-8c0b-612fb9361d79.png)

Diatas menampilkan file yang telah dibuat nama columns nya.
Selanjutnya menghapus columns ID.

![image](https://user-images.githubusercontent.com/50357969/95885204-341dcd80-0da7-11eb-9641-681a1af5dde4.png)

Setelah itu kita akan memindahkan columns Diagnosis di akhir tabel

![image](https://user-images.githubusercontent.com/50357969/95885277-47309d80-0da7-11eb-90df-dc3cdf3b7733.png)

Maka hasilnya akan mencetak sebuah file yang bernama “WBDC.csv”.
Selanjutnya kita akan mengubah file csv menjadi arff menggunakan WEKA.
Hal pertama buka WEKA lalu masuk ke Tools > ArffViewer > Open file csv yang telah dibuat.
Maka nantinya akan seperti ini:
 
 ![image](https://user-images.githubusercontent.com/50357969/95885341-59124080-0da7-11eb-8e44-3a97dd8b72fe.png)
 
Selanjutnya Save as file tersebut menjadi file .arff.
Maka hasilnya akan seperti ini:
 
 ![image](https://user-images.githubusercontent.com/50357969/95885406-69c2b680-0da7-11eb-8991-34e3b7aea7cd.png)
 
Dengan demikian file arff untuk data wbdc telah terbuat.


2.	Proses data abalone
Hal pertama yang dilakukan adalah membaca file dan menuliskan atribut pada table.
 
 ![image](https://user-images.githubusercontent.com/50357969/95885477-79da9600-0da7-11eb-9c3d-945d64b46951.png)
 
Maka hasilnya akan menampilkan data table yang telah diberikan nama atribut.
Selanjutnya adalah memindahkan columns Jenis kelamin ke akhir tabel.
 
 ![image](https://user-images.githubusercontent.com/50357969/95885533-8a8b0c00-0da7-11eb-9e65-47c18b4fd24a.png)

 
Setelah itu data akan tersimpan ke file “abaloneData.csv” yang akan dibuat oleh program.

Selanjutnya kita akan mengubah file csv menjadi arff menggunakan WEKA.
Hal pertama buka WEKA lalu masuk ke Tools > ArffViewer > Open file csv yang telah dibuat.
Maka nantinya akan seperti ini:
 
 ![image](https://user-images.githubusercontent.com/50357969/95885587-9bd41880-0da7-11eb-8f95-9dfd243a98bb.png)
 
Selanjutnya Save as file tersebut menjadi file “DataAbalone.arff”.
Maka hasilnya akan seperti ini:

 ![image](https://user-images.githubusercontent.com/50357969/95885614-a68ead80-0da7-11eb-85e1-999e8112eb05.png)

Dengan demikian file data DataAbalone.arff telah terbuat.
