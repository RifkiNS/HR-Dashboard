### Proyek Akhir: Menyelesaikan Permasalahan Perusahaan Edutech ###
### Business Understanding ###
Jaya Jaya Maju merupakan salah satu perusahaan multinasional yang telah berdiri sejak tahun 2000. Ia memiliki lebih dari 1000 karyawan yang tersebar di seluruh penjuru negeri. 

Walaupun telah menjadi menjadi perusahaan yang cukup besar, Jaya Jaya Maju masih cukup kesulitan dalam mengelola karyawan. Hal ini berimbas tingginya attrition rate (rasio jumlah karyawan yang keluar dengan total karyawan keseluruhan) hingga lebih dari 10%.

## Permasalahan Bisnis ##
Departement HR Kesulitan dalam mengawasi dan melakukan identikasi faktor penyebab attrition sehingga tingkat attrition mancapai 10$. Sehingga menjadi masalah untuk perusahaan karena menggangu produktivitas perusahaan.

## Cakupan Proyek ##
- Membuat visualisasi dashboard HR yang berfokus pada:
    1. Employee count, attrition rate dan profil demografis.
    2. Analisis departemen dan bidang pendidikan terkait tingkat attrition.
    3. Distribusi employee attrition berdasarkan waktu lembur dan umur.
    4. Rating kepuasan karyawan berdasarkan peran pekerjaan.
- Membuat model machine learning untuk melakukan prediksi dan melihat faktor penyebab attrition.
- Memberikan rekomendasi pada HR untuk mengurangi tingkat attrition.

## Persiapan ##
Sumber data: [Employee Data](https://github.com/dicodingacademy/dicoding_dataset/blob/main/employee/employee_data.csv)

## Setup environment: ##
Proyek ini menggunakan google colab sehingga menggunakan enviroment default dari google colab

### Business Dashboard ###
Link Dashboard HR : [Dashboard HR](https://public.tableau.com/app/profile/rifki.nova.suryo/viz/DasbordHR/Dashboard1?publish=yes) 

![Dashboard 1](https://github.com/user-attachments/assets/0a35fa6f-97f0-48f5-83bc-272422d10d6d)

Pada dashboard di atas berisikan berbagai visualisasi yang mencakup attrition rate, distribusi attrition disetiap departemen, rata-rata usia karyawan, jumlah karyawan, distribusi attrition akibat over time, distribusi attrition berdasarkan umur, rating kepuasan karyawan disetiap departemen terhadap lingkungan kerja dan latar belakang pendidikan karyawan. Dashboard ini berfungsi sebagai alat bagi manajemen untuk memahami lebih dalam kondisi tenaga kerja mereka.

### Conclusion ###
Setelah melakukan pembuatan dashboard dan membuat model machine learning dapat disimpulkan:
- Berdasarkan dashboard yang dibuat departement Research & Development memiliki tingkat attrition tertinggi sebesar 59.78% dari semua departemen yang ada pada perusahaan ini sejalan dengan tabel rating kepuasan karyawan terhadap lingkungan kerja di mana karyawan di departemen Research & Development cenderung memiliki kepuasaan yang cukup rendah. Selain itu, jam kerja karyawan pun mempengaruhi tingkat attrition di mana karyawan yang bekerja lembur memiliki tingkat attrition cukup tinggi. 
- Karyawan yang berusia 25-34 memiliki tingkat attrition tinggi sebesar 28.49%. Kelompok ini kemungkinan besar terdiri dari profesional muda yang mencari peluang karir atau keseimbangan kehidupan kerja yang lebih baik. 
- Bidang pendidikan Life Sciences paling terdampak attrition, menunjukkan adanya keterbatasan dalam pengembangan karir atau kesesuaian peran pekerjaan dengan latar belakang pendidikan tersebut.
- Berdasarkan hasil model machine learning yang dibantu dengan analisis SHAP summary plot menunjukkan bahwa OverTime, MonthlyIncome, MartialStatus, dan Age adalah fitur terpenting dalam memprediksi attrition. Karyawan dengan jam lembur tinggi dan pendapatan rendah cenderung memiliki attrition rate yang tinggi. Analisis SHAP summary plot dapat dilihat pada gambar di bawah:
![image](https://github.com/user-attachments/assets/1b35b0c6-0037-4495-9eaa-095b7d93b0bc)


### Rekomendasi Action Items (Optional) ###
Berikan beberapa rekomendasi action items yang harus dilakukan perusahaan guna menyelesaikan permasalahan atau mencapai target mereka.

action item 1
action item 2
