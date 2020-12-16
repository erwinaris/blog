+++
title = "Halo Dunia"
date = "2020-09-02"
aliases = ["about-us","about-hugo","contact"]
type = "dart"
[ author ]
  name = "erwin aris prayogo"
+++

 [_Bahasa Dart_](https://dart.dev/) adalah bahasa pemrograman berorientasi objek (PBO), bahasa untuk kebutuhan umum (_general-purpose programming language_), bahasa yang digunakan untuk membuat aplikasi (_Mobile_ {IOS dan Android}, _Web_, _Desktop_, aplikasi _server_, bahkan **IoT** (_Internet of Things_), menggunakan apa yang disebut _dart virtual machine_ {aplikasi tidak perlu di _compile_ terlebih dahulu}, **Open Source** ber-Lisensi **BSD**, dan bahasa dart merupakan produksi Google yang dirancang oleh **Lars Bak** dan **Kasper Lund** pada tahun 2011.

Menulis program pertama di Dart : 

{{< highlight dart "linenos=table,hl_lines=0 1-3,linenostart=1" >}}

void main(List<String> arguments) {
  print('Halo Dunia');
}

// shorthand code
/* void main(List<String> args) => print('Halo Dunia !!'); */

{{< / highlight >}}

**Keterangan :** 
1. _void_ sebagai opsi (boleh dipakai / boleh juga tidak).
2. _print_ digunakan untuk mencetak data ke layar komputer.
3. _=>_ digunakan untuk shorthand (menyingkat kode yang tidak mengembalikan nilai).

> fungsi **void** artinya tidak mengembalikan nilai apapun, sedangkan fungsi _main( )_ sebagai **entry point** (titik masuknya program) dan fungsi _main( )_ wajib ada di setiap program Dart.
