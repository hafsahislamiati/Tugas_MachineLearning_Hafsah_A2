Nama		: Hafsah Islamiati Ayuningtyas
NPM		: 41155050210039
Kelas		: INF-A2
Mata Kuliah	: Machine Learning
Tugas Pertemuan 5

K-Nearest Neighbours (KNN)
1.1.	Persiapan sample dataset
 ![image](https://github.com/user-attachments/assets/5666f425-bdb7-44ed-9e13-e37d46333870)

1.2.	Visualisasi dataset
 ![image](https://github.com/user-attachments/assets/09ec0ae6-51d4-45a8-9411-671ae22275c8)
 ![image](https://github.com/user-attachments/assets/19236970-7ea1-4067-acd7-94638989cbd5)

1.3.	Pengantar classification dengan K-Nearest Neighbours | KNN

1.4. Preprocessing dataset dengan Label Binarizer
 ![image](https://github.com/user-attachments/assets/800afc88-1a58-42c1-b617-76babba0844b)
 ![image](https://github.com/user-attachments/assets/cb5fb0b4-d3e3-46bd-b2ef-f9539a2661e1)

1.5.	Training KNN Classification Model
 ![image](https://github.com/user-attachments/assets/a74c8568-1e60-476d-9152-8b2a4a7d86d8)

1.6.	Prediksi dengan KNN Classification Model
 ![image](https://github.com/user-attachments/assets/572eaef6-5488-442d-ae2c-7d70be99e9e5)

1.7.	Visualisasi Nearest Neighbours
 ![image](https://github.com/user-attachments/assets/10d5a910-2b40-47f4-a6db-c826c6221cec)
 ![image](https://github.com/user-attachments/assets/30da7ca4-d11c-4475-8644-bb4026c82df2)

1.8.	Kalkulasi jarak dengan Euclidean Distance
 ![image](https://github.com/user-attachments/assets/478cad90-b262-474d-9937-c6473c33cf22)
 ![image](https://github.com/user-attachments/assets/352c3e71-697e-481e-8d4f-2d3d114d155e)

1.9.	Evaluasi KNN Classification Model | Persiapan testing set
 ![image](https://github.com/user-attachments/assets/130c0c33-2bd0-4a06-b51a-61f54fc39d4b)

1.10.	Evaluasi model dengan accuracy score
 ![image](https://github.com/user-attachments/assets/8c2a3d7f-e33c-421d-baab-0e5fb47ba006)

1.11.	Evaluasi model dengan precision score
 ![image](https://github.com/user-attachments/assets/75b9b9b7-1449-48de-a707-034f20be1437)

1.12.	Evaluasi model dengan recall score
 ![image](https://github.com/user-attachments/assets/ec57168a-d593-4391-b814-acbc6dd77db9)

1.13.	Evaluasi model dengan F1 score
 
1.14.	Evaluasi model dengan classification report
 
1.15.	Evaluasi model dengan Mathews Correlation Coefficient
 
















Support Vector Machine (SVM)
2.1. Pengenalan Decision Boundary & Hyperplane
 
Decision Boundary adalah batas yang memisahkan kelas-kelas dalam data. Ini bisa berupa garis atau permukaan yang membantu model klasifikasi menentukan di mana setiap data baru harus diklasifikasikan.
Hyperplane adalah pemisah linear dalam dimensi tinggi, seperti yang digunakan pada Support Vector Machine (SVM). Di dua dimensi, ini berupa garis; di tiga dimensi, berupa bidang. Hyperplane bertujuan untuk memisahkan kelas dengan margin maksimal. 
Keduanya berfungsi untuk memisahkan data, tetapi hyperplane khusus untuk pemisahan linear.

2.2. Pengenalan Support Vector & Maximum Margin
  
Support Vector adalah titik data yang berada paling dekat dengan hyperplane dalam algoritma Support Vector Machine (SVM). Titik-titik ini sangat penting karena mereka menentukan posisi dan orientasi hyperplane yang memisahkan kelas-kelas dalam data. Bahkan jika hanya support vector yang diubah, posisi hyperplane juga akan berubah.
Maximum Margin adalah jarak terbesar yang dapat dibuat antara hyperplane dan titik data terdekat dari setiap kelas. Tujuan SVM adalah menemukan hyperplane yang memaksimalkan margin ini, sehingga model memiliki pemisahan paling optimal antara kelas-kelas, yang membuatnya lebih kuat dalam mengklasifikasi data baru.

2.3. Pengenalan kondisi Linearly Inseparable dan Kernel Tricks
 
Linearly Inseparable adalah kondisi ketika data dari berbagai kelas tidak bisa dipisahkan dengan garis atau hyperplane lurus karena pola data yang kompleks. Dalam kasus ini, data dari kelas yang berbeda saling tumpang tindih atau berdekatan dalam ruang fitur sehingga pemisahan linear tidak cukup efektif.
Kernel Trick adalah teknik dalam Support Vector Machine (SVM) untuk mengatasi masalah linearly inseparable dengan memetakan data ke dalam ruang berdimensi lebih tinggi, di mana data tersebut bisa dipisahkan secara linear. Dengan kernel trick, SVM tidak perlu benar-benar menghitung koordinat di ruang yang lebih tinggi, sehingga pemrosesan menjadi lebih efisien. Kernel yang umum digunakan termasuk polynomial, Gaussian (RBF), dan sigmoid.


2.4. Pengenalan MNIST Handwritten Digits Dataset
 
 
 
2.5. Klasifikasi dengan Support Vector Classifier | SVC
 
2.6. Hyperparameter Tuning dengan Grid Search
 
 
 
2.7. Evaluasi Model
 
