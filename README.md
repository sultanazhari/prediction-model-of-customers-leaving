# prediction-model-of-customers-leaving

# Deskripsi Proyek
Nasabah Bank Beta pergi meninggalkan perusahaan: sedikit demi sedikit, jumlah mereka berkurang setiap bulannya. Para pegawai bank menyadari bahwa akan lebih menghemat biaya jika perusahaan fokus untuk mempertahankan nasabah lama mereka yang setia daripada menarik nasabah baru.

Pada kasus ini, tugas kita adalah untuk memprediksi apakah seorang nasabah akan segera meninggalkan bank atau tidak. Kamu memiliki data terkait perilaku para klien di masa lalu dan riwayat pemutusan kontrak mereka dengan bank.

Buat sebuah model dengan skor F1 semaksimal mungkin. Untuk bisa dinyatakan lulus dari peninjauan, kamu memerlukan skor F1 minimal 0,59 untuk test dataset.

Setelah itu, kamu akan membuat perubahan yang diperlukan pada pekerjaanmu dan mengirimkannya kembali untuk tinjauan kedua.

Selain itu, ukur metrik AUC-ROC dan bandingkan metrik tersebut dengan skor F1.


# Deskripsi data
Fitur-fitur

RowNumber — indeks string data<br>
CustomerId — ID pelanggan<br>
Surname — nama belakang<br>
CreditScore — skor kredit<br>
Geography — negara domisili<br>
Gender — gender<br>
Age — umur<br>
Tenure — jangka waktu jatuh tempo untuk deposito tetap nasabah (tahun)<br>
Balance — saldo rekening<br>
NumOfProducts — jumlah produk bank yang digunakan oleh nasabah<br>
HasCrCard — apakah nasabah memiliki kartu kredit (1 - jika ya; 0 - jika tidak)<br>
IsActiveMember — tingkat keaktifan nasabah (1 - jika ya; 0 - jika tidak)<br>
EstimatedSalary — estimasi gaji<br>
Target<br>

Exited — apakah nasabah telah berhenti (1 - jika ya; 0 - jika tidak)
