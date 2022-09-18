1. Buka jenkin
2. Pilih manage jenkin
3. Pilih manage plugin
4. setelah itu klik avaliable
5. Check Pipeline

- Pipeline ada;ah definisi kode continous delivery
- Sebuah pipeline berisikan seluruh intruksi untuk melakukan proses continous delivery, misal seperti compile, testing , deploy dan lain lain
- Kode pipeline menggunakan kata kunci pipeline


- Agent adalah machine/server bagian dari jenkins yang digunakan untuk mengeksekusi pipeline
- Kode agent mengandung kata kunci agent
- Agent disebutkan di dalam kode pipeline yang kita buat

- Stage adlaah blok definisi tugas atau tahapan dalam pipeline, misalnya "Build", "Test", "Deploy", dan lain lain
- Stage biasanya ditampilkan di jenkin seperti tahapan progres dari pipeline
- Dalam pipeline biasanya terdapat banyak stage
- Stage dibuat mengguankan keyword stage


- Step adalah sebuah instruksi atau perintah
- Step pada dasarnya adalah perintah yang harus dilakukan oleh jenkins
- Step dilakukan di dalam Stage
- Step dibuat menggunakan keyword steps


