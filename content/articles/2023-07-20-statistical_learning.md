---
title: Intro to Statistical Learning
tags: Machine Learning, Statistical learning
date: 2023-07-20
description: Cupcake ipsum dolor. Sit amet pastry cake toffee carrot cake. Cheesecake candy I love dragée cake jelly-o pie. Cheesecake sesame snaps danish lemon drops sesame snaps sugar plum cupcake powder. Cookie sweet wafer. Jelly chocolate cake dragée candy canes halvah.
image: /images/slearning.png
draft: true
---

### Tentang statistical learning.

Machine learning memiliki cakupan yang sagat luas. Banyak metode, pendekatan, dan konsep mengenai machine learning yang beririsan dengan statistic. Statistical learning sangat terkait dengan dasar-dasar statistic as a "white-box" method dalam menyelesaikan masalah-masalah machine learning. Pada dasarnya tidak ada satu metode machine learning bisa kita gunakan untuk menyelesaikan semua masalah yang ada dengan baik. Jadi perlunya medeskripsikan model, memiliki intuisi, asumsi, dan trade-off dari metode yang kita gunakan menjadi sangat penting.

Melalui pendekatan statistical learning, kita akan belajar bagaimana metode yang akan kita gunakan bekerja, the mathematics behind. Jadi kita tidak hanya bisa mengaplikasikan metode tahu tanpa tahu apa yang sebenarnya terjadi. Bukan karena metode yang kita gunakan bisa bekerja, tetapi karena berdasarkan pendekatan konseptual kenapa metode kita bisa bekerja. Dari data yang ada, lalu mengasumsikan metode yang kita gunakan mampu menghasilkan luaran tertentu yang sesuai dengan hipotesis kita. Mudahnya, kita bisa memprediksi hasilya seperti apa.

### Machine learning overview.

Definisi Machine Learning sangat susah didefinisikan secara pasti. Karena di dalamnya banyak metode dan pendekatan dari berbagai macam disiplin pengetahuan, dari statistics, computer science, pattern recognition, knowledge discovery. Jadi, machine learning lebih cocok masuk sebagai sebuah permasalahan daripada sebuah disiplin ilmu pengetahuan. Yakni masalah tentang data, pattern, dan prediksi.

Tetapi kita bisa berangkat dari definisi Tom Mitchell - 1997 tentang machine learning:

> A computer program is said to learn from experience E with respect
> to some class of task T and a performance measure P, if its 
> performance at tasks in T, as measured by P, improves because of
> experience E.

Dimana T: Regression/Classification/Clustering, E: Data, P: Errors/Loss. 

Kita akan membedakan machine learning berdasarkan kategori learning paradigm-nya. Asumsikan kita memiliki E, misal kita memiliki data $input=x_{1},x_{2},x_{3},\dots,x_{N}$. $x$ bisa berbentuk skalar ataupun vektor. i.e. $x_{1} = umur$ atau $x_{1} = \begin{bmatrix} tinggi\\ berat \end{bmatrix}$ dan data $target=y_{1},y_{2},y_{3},\dots,x_{N}$. i.e. Gaji dalam juta IDR $t_{1}=3.0$ atau dalam bentuk kategori $t_{1}=kaya$. Dimana tugas kita adalah untuk memprediksi $t_{k}$ berdasarkan input baru $x_{k}$ dengan benar maka kita sebut ini sebagai **Supervised Learning**


Lift($L$) can be determined by Lift Coefficient ($C_L$) like the following equation.

$$
L = \frac{1}{2} \rho v^2 S C_L
$$
