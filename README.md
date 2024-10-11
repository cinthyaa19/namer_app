# namer_app

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

    Nama: Cinthya Achwatul Ifnu

    NIM: 2241720051

    Kelas: TI 3H

    No Absen: 07

## Create a project
### Create my frist Flutter project

![alt](/images/01.png)

### Copy & Paste the initial app
- File pubspec.yaml

![alt](/images/02.png)

- File analysis_options.yaml

![alt](/images/03.png)

- File main.dart

![alt](/images/04.png)

## Add a button
This step adds a Next button to generate a new word pairing

### Launch the app

![alt](/images/05.png)

### First Hot Reload

![alt](/images/06.png)

### Adding a button

![alt](/images/07.png)

### A Flutter crash course in 5 minutes
- **Menghubungkan button dengan status dan menambahkan metode getNext**

    ![alt](/images/08.png)

- **Memanggil metode getNext**

     Hasil Output dari running kode program ini adalah terdapat kata-kata random baru yang akan ditampilkan bergantian ketika tombol Next ditekan

    ![alt](/images/09.png)

    ![alt](/images/10.png)

    ![alt](/images/11.png)

- **Ekstrak Widget**

    ![alt](/images/12.png)

- **Memanggil menu Refactor**

    Untuk melakukan Refactor, arahkan kursor ke potongan kode program "Text" kemudian Ctrl+D untuk mengarahkan kursor ke potongan kode program "Text" yang lainnya.

    kemudian klik kanan, pilih Refactor pada menu drop-down dan klik Extract Widget.

    kemudian beri nama BigCard dan klik enter.

    ![alt](/images/13.png)

    maka otomatis membuat class baru yang bernama BigCard, seperti gambar diatas

### Add a Card

![alt](/images/14.png)

### Theme and Style

![alt](/images/15.png)

### Text Theme

![alt](/images/16.png)

### SemanticsLabel

![alt](/images/17.png)

### Center the UI

![alt](/images/18.png)

Verifikasi column agar berada di tengah dalam tampilan browser menggunakan Widget Inspector

![alt](/images/19.png)

Add sizebox

![alt](/images/20.png)

### Add functionality

Add the business logic

![alt](/images/21.png)

### Add the button

Refactor ElevatedButton

![alt](/images/22.png)

Tampilan UI seperti sebelumnya

![alt](/images/23.png)

Menambahkan Like button dan menyambungkannya ke toggleFavorite(). Sehingga button Like bisa di klik

![alt](/images/24.png)

![alt](/images/25.png)

### Add navigation rail

![alt](/images/26.png)

![alt](/images/27.png)

![alt](/images/28.png)

### Stateless versus stateful widgets

![alt](/images/31.png)

### setState

![alt](/images/29.png)

![alt](/images/30.png)

### Use selectedIndex

![alt](/images/32.png)

Aplikasi ini sekarang beralih antara GeneratorPage dan placeholder yang akan segera menjadi halaman Favorit.

![alt](/images/33.png)

![alt](/images/34.png)

### Responsiveness

![alt](/images/37.png)

Sekarang, aplikasi Anda merespons lingkungannya, seperti ukuran layar, orientasi, dan platform! Dengan kata lain, aplikasi ini responsif!.

![alt](/images/35.png)

![alt](/images/36.png)

### Add a new page

Home Pgae

![alt](/images/38.png)

Favourite Page, pada page ini akan menampilkan text yang disukai

![alt](/images/39.png)

Menyukai beberapa kata yang akan disimpan pada Favourite Page

![alt](/images/40.png)

![alt](/images/41.png)

![alt](/images/42.png)

List data kata yang telah dilike pada Favourite Page

![alt](/images/43.png)

