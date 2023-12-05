# **Praktikum 3 Jaringan Komputer**
<div align=justify>

Berikut adalah Repository dari Kelompok A17 untuk pengerjaan Praktikum Modul 4 Jaringan Komputer. Dalam Repository ini terdapat Anggota Kelompok, Dokumentasi serta Penjelasan tiap soal, Screenshot Output, dan Kendala yang dialami.

# **Anggota Kelompok**

| Nama                      | NRP        | Kelas                |
| ------------------------- | ---------- | ----------------     |
| Andrian                   | 5025211079 | Jaringan Komputer A  |
| Akmal Ariq Romadhon       | 5025211188 | Jaringan Komputer A  |


# **Dokumentasi dan Penjelasan Soal**
<div align=justify>

Berikut adalah dokumentasi yang berisi source code dari tiap soal dan penjelasan terkait perintah atau _syntax_ yang digunakan. 

## **Soal Praktikum 4**
![Soal0](https://cdn.discordapp.com/attachments/1150687865420906517/1181509244529418290/Topologi.png?ex=6581513b&is=656edc3b&hm=23262ede4149f6491024fa4393a380e3e10058ed49b1202febf2e6e1feba7cb3&)

- Soal shift dikerjakan pada Cisco Packet Tracer dan GNS3 menggunakan metode perhitungan CLASSLESS yang berbeda.
Keterangan: Bila di CPT menggunakan VLSM, maka di GNS3 menggunakan CIDR atau sebaliknya

- Jika tidak ada pemberitahuan revisi soal dari asisten, berarti semua soal BERSIFAT BENAR dan DAPAT DIKERJAKAN.

- Untuk di GNS3 CLOUD merupakan NAT1 jangan sampai salah agar bisa terkoneksi internet.

- Pembagian IP menggunakan Prefix IP yang telah ditentukan pada modul pengenalan.

- Pembagian IP dan routing harus SE-EFISIEN MUNGKIN.
Gambar topologi yang lebih jelas dapat diakses pada link [berikut](https://drive.google.com/file/d/1VmJXOyEoWru1tfXISOgoJiPfE1hpbptM/view)


# **VLSM**
Berikut adalah langkah-langkah pengerjaan untuk pengerjaan praktikum dengan metode VLSM.

## **_Subnetting_**
_Subnetting_ merupakan cara untuk mengelola jaringan dari jaringan yang lebih besar. Dengan adanya subnet, kita dapat melakukan manajemen suatu jaringan dengan lebih baik. Berikut adalah hasil _subnetting_ dari kelompok kami:

![Subnet-1](https://cdn.discordapp.com/attachments/1150687865420906517/1181513452473290762/image.png?ex=65815526&is=656ee026&hm=84670f7a73067080ff13edffbad28d58d4f4be25208a1c35f7ae34ca4fc6dd77&) 

![Subnet-2](https://cdn.discordapp.com/attachments/1150687865420906517/1181513534224474142/image.png?ex=6581553a&is=656ee03a&hm=9bf959c5e9dfd3fb7352dae1b56a9c327376c39f48a30bf942c0ff7558d0cd92&)

Untuk detail terkait _subnetting_ dapat diakses  [disini](https://docs.google.com/spreadsheets/d/1g9e3pyLJarNEssHcELBahROomv_jLfQm5B9F5-5FD4Q/edit?usp=sharing) atau melalui link berikut: https://its.id/m/SubnettingA17

## **Pembuatan _Tree_**
Setelah melakukan _subnetting_, langkah yang digunakan adalah membuat _tree_. _Tree_ tersebut akan digunakan sebagai dasar _routing_. Berikut adalah tree hasil pengerjaan dari kelompok kami:

![Tree](https://cdn.discordapp.com/attachments/1150687865420906517/1181510982762246144/VLSM_Tree_A17.jpg?ex=658152d9&is=656eddd9&hm=209de434d004bd80b13ac914d938c0a9ff6c6c53312966cf2ac550e485c074f1&)

## **_Routing_**
Langkah terakhir untuk menyelesaikan soal dengan metode VLSM adalah melakukan _routing_. Secara singkat, _routing_ adalah cara untuk menghubungkan setiap router sehingga setiap _client_ dapat terhubung dengan _client_ yang lain. Berikut adalah _config_ dari seluruh node untuk _routing_ dengan GNS3:

# **CIDR**
Coming Soon.

# **Kendala Saat Pengerjaan**

- Banyaknya _final project_ dan ujian lain sehingga mengakibatkan waktu untuk mengerjakan praktikum lebih sedikit. 

- Kurangnya pemahaman terkait _subnetting_ dan _routing_ sehingga membutuhkan waktu lebih untuk mengerjakan praktikum.

- Kurang teliti saat proses _routing_ sehingga terjadi banyak error (konflik antara IP dan Subnet).

# **End of The Line**

```c
#include <stdio.h>

int main(){
    printf("Thank you!");
}
```
