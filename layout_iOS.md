# Jenis-jenis Layout di xCode

## ViewController

Layout ini merupakan layout standar dari applikasi iOS. Didalamnya kita dapat membuat layout sesuai dengan model yang diinginkan. Beberapa Layout juga dapat di gunakan dalam layout ini, seperti tableview dan collectionView.

## NavigationController

Layout ini berfungsi sebagai layout navigasi, dimana isi dari layout ini adalah ViewController. Kita membuat hirarki navigasi di layout ini. Bukan hanya ViewController saja yang dapat digunakan, namun Layout yang lain dapat juga digunakan.

## TableViewController

Layout ini berbentuk table satu kolom, didalamnya terdiri dari beberapa tableViewCell. Biasa digunakan untuk menampilkan list data dalam jumlah tertentu. Dalam beberapa aplikasi kita pun dapat menggunakan pagination disini (dengan beberapa trik untuk menggunakan fitur ini).

## CollectionViewController

Layout ini sama seperti tableViewController, namun disini kita dapat membuat beberapa kolom sesuai dengan kebutuhan. 

## TabBarViewController

layout ini digunakan jika ingin menampilkan layout dalam bentuk Tab, secara default tab yang bisa ditampilkan maksimum 5 tab. Isi dari layout ini secara umum itu ViewController, namun bisa juga digunakan layout yang lain.

## SplitViewController

Layout ini digunakan kebanyakan di iPad, dikarenakan layar iPad yang lebar. Biasanya digunakan di modul setting, dan view pertamanya biasa tableViewController dan view kedua merupakan detail dari pilihan di view pertama.

## PageViewController

Layout ini berfungsi untuk mengubah ViewController misalnya menjadi page. Hampir mirip dengan TabBarViewController, bedanya terletak di UX saja.
