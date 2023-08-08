# Tugas1FGABDPython
Title : Tingkat stress di beberapa bidang pekerjaan.</br>
Tujuan dari projek ini adalah untuk mengetahui tingkat stress yang terjadi di beberapa bidang pekerjaan dan mengetahui variabel yang berkorelasi dengan terjadinya tingkat stress.</br>
Seperti yang kita ketahui, terdapat banyak bidang pekerjaan dimana tingkat stress pada setiap bidang pekerjaan tersebut tentu bervariasi dan memiliki parameter latar belakang tertentu yang menjadi penyebabnya. Jika kita lihat sekilas bidang pekerjaan mana yang mengalami stress paling tinggi maka jawaban yang terkait dengan asumsi pasti akan bervariasi. Sebagai contoh, mungkin orang akan lebih menilai bidang programmer memiliki tingkat stress tertinggi karena kebanyakan orang melihat mereka hanya duduk dan fokus menatap laptop untuk ngoding. Namun opini tersebut bisa jadi terbantahkan berdasarkan data yang kita miliki. Perlu diketahui juga, faktor kondisi biologis seseorang juga dapat berpengaruh terhadap tingkat stress yang akan dialami seperti indeks masa tubuh, waktu tidur, tekanan darah, dan lain sebagainya.</br>
Berikut adalah data-data yang digunakan pada projek ini :</br>
Person ID: An identifier for each individual.</br>
Gender: The gender of the person (Male/Female).</br>
Age: The age of the person in years.</br>
Occupation: The occupation or profession of the person.</br>
Sleep Duration (hours): The number of hours the person sleeps per day.</br>
Quality of Sleep (scale: 1-10): A subjective rating of the quality of sleep, ranging from 1 to 10.</br>
Physical Activity Level (minutes/day): The number of minutes the person engages in physical activity daily.</br>
Stress Level (scale: 1-10): A subjective rating of the stress level experienced by the person, ranging from 1 to 10.</br>
BMI Category: The BMI category of the person (e.g., Underweight, Normal, Overweight).</br>
Blood Pressure (systolic/diastolic): The blood pressure measurement of the person, indicated as systolic pressure over diastolic pressure.</br>
Heart Rate (bpm): The resting heart rate of the person in beats per minute.</br>
Daily Steps: The number of steps the person takes per day.</br>
Sleep Disorder: The presence or absence of a sleep disorder in the person (None, Insomnia, Sleep Apnea).</br>

Details about Sleep Disorder Column:</br>

None: The individual does not exhibit any specific sleep disorder.</br>
Insomnia: The individual experiences difficulty falling asleep or staying asleep, leading to inadequate or poor-quality sleep.</br>
Sleep Apnea: The individual suffers from pauses in breathing during sleep, resulting in disrupted sleep patterns and potential health risks.</br>

Blood pressure category didefinisikan ulang dalam nilai numerik yakni atau dengan istilah lain disebut sebagai normalisasi untuk mengubah data label menjadi numerik :</br>
1->Normal</br>
2->Elevated</br>
3->Hypertensive Stage 1</br>
4->Hypertensive Stage 2</br>
5->Hypertensive Critis.</br>

Pada project ini digunakan beberapa library yang umum pada python yakni pandas, numpy, dan matplotlib.pyplot untuk membantu dalam proses analisis.</br>Untuk dapat menggunakan library-library tersebut kita bisa menggunakan syntax import.</br>

Dalam memulai analisis ini kita berangkat dari descriptive analytics dengan bantuan grafik untuk mengetahui apa yang terjadi berangkat dari pertanyaan "stress level tertinggi di bidang pekerjaan apa?", "bagaimana kondisi kesehatan (BMI, tensi, sleep quality, dll) setiap pekerja dari tiap bidang pekerjaan tersebut?"</br>
Kemudian kita bisa mengetahui apa saja faktor yang mungkin bisa menjadi pemicu stress level di setiap bidang pekerjaan, dengan menemukan korelasi antara parameter seperti menggunakan heatmap dan juga scatter plot untuk melihat korelasi antara kategori tekanan darah terhadap usia. </br>

<h3>Kesimpulan</h3><br>
Berdasarkan data dan grafik yang telah disajikan beserta dengan pemaparannya, dapat menjadi pertimbangan atau knowledge bagi kita untuk mendorong employee di bidang Nurse memiliki berat badan ideal agar memenuhi standar BMI normal. Selain itu juga stress level yang dialami oleh employee di bidang Nurse harus diperhatikan dan dievaluasi. Salah satu solusinya dapat berupa pemerataan atau penambahan tenaga kesehatan, pelayanan konseling psikis, dan kegiatan kebugaran/olahraga rutin yang perlu diterapkan bagi tiap Nurse untuk menjaga kondisi berat badan yang ideal.
