+++
title = "Control Structures Chapter 1"
date = "2020-09-18"
aliases = ["about-us","about-hugo","contact"]
type = "dart"
[ author ]
  name = "erwin aris prayogo"
+++

**Struktur Kontrol** adalah suatu perintah, pernyataan, kondisi, blok program ( blok kode ) yang berguna untuk mengendalikan jalannya alur program.

Secara umum struktur kontrol terbagi menjadi 3 : 

1. struktur pemilihan **(kondisi)**.
    > struktur pemilihan artinya blok program atau perintah yang berfungsi untuk memilih suatu kondisi yang telah didefinisikan.

2. struktur pengulangan **(looping)**.
    > struktur pengulangan berarti blok program atau perintah yang dieksekusi untuk mengulang pernyataan yang telah didefinisikan sampai kondisi tertentu.

3. struk eksepsi **(exception)**.
    > struktur eksepsi merupakan mekanisme yang paling populer yang paling populer dalam menangani _error_ yang terjadi pada saat _runtime_ (program berjalan) atau yang lebih dikenal dengan _runtime error_.

###### 1. sebagai contoh **struktur pemilihan** dibawah ini, menggunakan _if_ dan _else_.

{{< highlight dart "linenos=table,hl_lines=4 6,linenostart=1" >}}

void main(List<String> args) {
  dynamic name = 'Erwin';

  if (name == name){
    print(name);
  }else{
    print('no name');
  }
}

{{< / highlight >}}

**keterangan** :

1. _dynamic_ adalah tipe yang didefinisikan dan dapat di isi dengan tipe apapun(boolean, integer, double, atau String).

2. _if_ jika kondisi benar maka akan di eksekusi.

3. opsi _else_ jika kondisi salah.


###### 2. menggunakan _if - else if - else_

{{< highlight dart "linenos=table,hl_lines=8 10 12,linenostart=1" >}}

import 'dart:io';
import 'dart:core';

void main(List<String> args) {
  stdout.write('Input a number : ');
  var number = int.tryParse(stdin.readLineSync());

  if (number > 0) {
    print('$number is Positive');
  }else if (number < 0){
    print('$number is Negative');
  }else{
    print('$number is Null');
  }

}

{{< / highlight >}}

