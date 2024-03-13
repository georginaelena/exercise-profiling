
# Performa Aplikasi: Panduan Pengujian dan Profiling

**Nama**    : Georgina Elena Shinta Dewi Achti
<br>
**NPM**     : 2206810995
<br>
**Kelas**   : ADPRO-C
<br>
## REFLEKSI 3

**Apa perbedaan antara pendekatan pengujian kinerja dengan JMeter dan profil dengan IntelliJ Profiler dalam konteks mengoptimalkan kinerja aplikasi?**

- **Pendekatan Pengujian Kinerja dengan JMeter**: Fokus pada pengujian beban dan skenario penggunaan yang berbeda untuk mengukur kinerja aplikasi di bawah tekanan.

- **Profil dengan IntelliJ Profiler**: Berfokus pada analisis detail dari kinerja aplikasi di tingkat kode, memungkinkan identifikasi titik-titik lemah dan penyebab utama masalah kinerja.

**Bagaimana proses profil membantu Anda dalam mengidentifikasi dan memahami titik-titik lemah dalam aplikasi Anda?**

- Proses profil membantu dalam memahami bagaimana aplikasi berperilaku dan memungkinkan untuk melihat metrik kinerja penting seperti penggunaan memori, waktu eksekusi, dan panggilan fungsi yang paling sering terjadi. Dengan demikian, dapat mengidentifikasi bagian-bagian aplikasi yang membutuhkan perbaikan atau pengoptimalan.

**Apakah Anda pikir IntelliJ Profiler efektif dalam membantu Anda menganalisis dan mengidentifikasi bottleneck dalam kode aplikasi Anda?**

- Ya, IntelliJ Profiler sangat efektif dalam membantu menganalisis dan mengidentifikasi bottleneck dalam kode aplikasi. Ini menyediakan visualisasi yang jelas tentang bagaimana aplikasi berperilaku di tingkat kode, memungkinkan untuk melacak dan memahami dengan tepat di mana masalah kinerja mungkin terjadi.

**Apa tantangan utama yang Anda hadapi saat melakukan pengujian kinerja dan profil, dan bagaimana Anda mengatasi tantangan tersebut?**

- Tantangan utama termasuk memastikan pengujian kinerja mencakup skenario penggunaan yang realistis, memperoleh data yang akurat dari profil, dan menerjemahkan temuan menjadi perbaikan praktis dalam kode. Tantangan ini dapat diatasi dengan merencanakan pengujian yang baik, menggunakan alat bantu yang tepat, dan melibatkan tim pengembangan dalam proses analisis dan perbaikan.

**Apa manfaat utama yang Anda dapatkan dari menggunakan IntelliJ Profiler untuk memprofil kode aplikasi Anda?**

- Manfaat utamanya termasuk kemampuan untuk melihat metrik kinerja secara detail di tingkat kode, mendeteksi bottleneck dengan cepat, dan menyediakan visualisasi yang memudahkan untuk memahami perilaku aplikasi. Ini memungkinkan pengembang untuk membuat keputusan yang terinformasi dalam memperbaiki dan mengoptimalkan kode.

**Bagaimana Anda menangani situasi di mana hasil dari profil dengan IntelliJ Profiler tidak sepenuhnya konsisten dengan temuan dari pengujian kinerja menggunakan JMeter?**

- Dalam situasi seperti itu, penting untuk melakukan analisis tambahan untuk memahami penyebab perbedaan. Mungkin ada faktor lain yang mempengaruhi kinerja aplikasi yang tidak terdeteksi dalam satu metode pengujian, dan perlu dilakukan pengujian tambahan atau profiling untuk memverifikasi temuan. Selain itu, diskusi dan kolaborasi dengan tim pengembangan dapat membantu dalam memahami dan menyelesaikan perbedaan tersebut.

**Apa strategi yang Anda implementasikan dalam mengoptimalkan kode aplikasi setelah menganalisis hasil dari pengujian kinerja dan profil? Bagaimana Anda memastikan perubahan yang Anda buat tidak mempengaruhi fungsionalitas aplikasi?**

- Strategi optimalisasi melibatkan identifikasi area yang membutuhkan perbaikan berdasarkan temuan dari pengujian dan profil, melakukan perubahan dengan hati-hati, dan menguji kembali aplikasi untuk memastikan tidak ada dampak negatif terhadap fungsionalitas. Proses pengembangan yang terorganisir dan penggunaan sistem kontrol versi juga membantu memantau perubahan dan memastikan kualitas kode tetap terjaga.

### JMeter Report and Test Results

***Endpoint /all-student***
_____________________

[Before] Optimization JMeter
<br>
![](https://i.imgur.com/lly2g0X.png)
<br>
[After] Optimization JMeter
<br>
![](https://i.imgur.com/lly2g0X.png)
<br>
[Before] Test Result JMeter
![](https://i.imgur.com/Dtf9jCg.png)
<br>
[After] Test Result JMeter
![](https://i.imgur.com/qT1IyKn.png)

***Endpoint /all-student-name***
_____________________

[Before] Optimization JMeter
<br>
![](https://i.imgur.com/Y0aPind.jpeg)
<br>
[After] Optimization JMeter
<br>
![](https://i.imgur.com/9Po3v19.jpeg)
<br>
[Before] Test Result JMeter
<br>
![](https://i.imgur.com/2DN7zpk.png)
<br>
[After] Test Result JMeter
<br>
![](https://i.imgur.com/VsRfvzN.png)

***Endpoint /highest-gpa***
_____________________

[Before] Optimization JMeter
<br>
![](https://i.imgur.com/xH2Ybsp.jpeg)
<br>
[After] Optimization JMeter
<br>
![](https://i.imgur.com/4Pe4nvV.jpeg)
<br>
[Before] Test Result JMeter
<br>
![](https://i.imgur.com/EOC5KBe.png)
<br>
[After] Test Result JMeter
<br>
![](https://i.imgur.com/sRK8b5J.png)
<br>
### Kesimpulan
- Setelah melakukan optimalisasi pada kode, terlihat penurunan waktu eksekusi yang cukup signifikan pada ketiga endpoint. Perbaikan ini terlihat jelas baik dari hasil pengujian menggunakan JMeter maupun analisis profil dengan IntelliJ, menunjukkan kemajuan yang konsisten dalam meningkatkan kinerja aplikasi.
