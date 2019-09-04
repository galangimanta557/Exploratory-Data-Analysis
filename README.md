# Exploratory-Data-Analysis
In the EDA section this is part of one of the requirements to be accepted to work
# **Interpretasi EDA Inflasi**
###  Plot Data Inflasi
![Data Inflasi](https://github.com/galangimanta557/Exploratory-Data-Analysis/blob/master/Inflasi/Inflasi%20Bulan%20Tahun.png)

Pada gambar tersebut dapat diketahui bahwa pada sumbu x dari kanan merupakan data inflasi dari Juni 2019 sampai ke kanan yaitu pada Desember 2002. Seperti kita ketahui terdapat bar menjulang tinggi ke atas berkisar antara 2005-2006, dikarenakan terjadinya peningkatan inflasi di tahun 2005 yang disebabkan oleh rencana kenaikan BBM pada masa itu, serta dampak bencana di NAD & Sumut (Sumber: Bank Indonesia). Namun, setelah tahun berikutnya mengalami penurunan, di karenakan penyebab penurunan inflasi adalah pemerintah telah berusaha menjaga stabilitas harga komoditas serta terjaganya target inflasi pada sasaran yang tepat.

### Statistika Deskriptif
![Descriptive](https://github.com/galangimanta557/Exploratory-Data-Analysis/blob/master/Inflasi/Descriptive.PNG)

Berdasarkan hasil deskriptif pada variabel inflasi, dapat diketahui bahwa jumlah data sebesar 199 dan rata-rata dari data inflasi sebesar 0.0631 atau 6.3 %. Kemudian pada variabel inflasi memiliki nilai standar deviasi sebesar 0.033 dan nilai minimum dan maximum sebesar 0.00 dan 0.183. Pada nilai Q1, Q2 dan Q3 yaitu sebesar 0.038, 0.060 dan 0.072. Serta tipe data pada inflasi merupakan tipe data float atau tipe data bilangan real.
***
# **Interpretasi EDA mtcars**
### Frequency mpg level
![Freq MPG Level](https://github.com/galangimanta557/Exploratory-Data-Analysis/blob/master/mtcars/freq%20mpg%20level.PNG)

Sesuai dengan petunjuk pada variabel **mpg_level**, yaitu jika **mpg** < 20 maka mpg_level = low, **mpg** berkisar 20-30 maka mpg_level = medium dan **mpg** > 30 maka mpg_level = hard. Maka dari itu saya menggunakan fungsi _if...else_ dan memvisualisasikannya dalam bentuk bar plot. Dari bar plot tersebut dapat diketahui bahwa mpg dengan level low sebesar 18, pada level medium sebesar 10 dan level high sebesar 4.
### Correlation
![](https://github.com/galangimanta557/Exploratory-Data-Analysis/blob/master/mtcars/plot.png)
![](https://github.com/galangimanta557/Exploratory-Data-Analysis/blob/master/mtcars/plot%20(2).png)
![](https://github.com/galangimanta557/Exploratory-Data-Analysis/blob/master/mtcars/plot%20(3).png)


![](https://github.com/galangimanta557/Exploratory-Data-Analysis/blob/master/mtcars/Correlation.PNG)

Korelasi digunakan untuk mengetahui hubungan antara 2 variabel. Pada lembaran kerja ini menggunakan variabel **mpg** untuk diuji apakah ada hubungan dengan variabel yang lain. Besarnya ataupun kuatnya hubungan ditentukan oleh besarnya koefisien antara **-1...0...+1** . Pada output tersebut dapat di ketahui bahwa **mpg** memiliki hubungan yang kuat (positif) pada variabel **drat, vs, am**. Serta **mpg** memiliki hubungan yang lemah (-negatif) terhadap variabel **hp, disp, cyl dan wt**.

![](https://github.com/galangimanta557/Exploratory-Data-Analysis/blob/master/mtcars/Graph%20correlation.png)
