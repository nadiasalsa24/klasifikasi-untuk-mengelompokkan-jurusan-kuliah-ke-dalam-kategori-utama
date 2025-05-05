# 🎓 Eksperimen Data Mining: Klasifikasi Jurusan Kuliah

Proyek ini merupakan eksperimen sederhana dalam bidang **data mining** dan **machine learning** menggunakan dataset jurusan kuliah. Tujuannya adalah untuk mengklasifikasikan **nama jurusan (`Major`)** ke dalam **kategori utama (`Major_Category`)** menggunakan dua algoritma klasifikasi populer:

- Naive Bayes (GaussianNB)
- Decision Tree

---

## 🧠 Tema Proyek

**Tema utama:** _Klasifikasi jurusan kuliah berdasarkan kategori bidang ilmu utama._

Model akan mempelajari hubungan antara nama jurusan dan kategori utamanya, lalu memprediksi kategori tersebut untuk data baru.

Contoh:
- Jurusan: `Mechanical Engineering` → Kategori: `Engineering`
- Jurusan: `Nursing` → Kategori: `Health`

---

## 📁 Struktur Dataset

Dataset yang digunakan memiliki format CSV dan berisi kolom berikut:

| Kolom           | Deskripsi                                      |
|------------------|-------------------------------------------------|
| `index`          | Nomor baris (tidak digunakan dalam pemodelan)   |
| `FOD1P`          | Kode jurusan (tidak digunakan dalam pemodelan)  |
| `Major`          | Nama jurusan (fitur yang diklasifikasikan)      |
| `Major_Category` | Kategori jurusan (target klasifikasi)           |

🔍 **Contoh isi dataset (majors-list.csv):**

```csv
index,FOD1P,Major,Major_Category
1,1100,GENERAL AGRICULTURE,Agriculture & Natural Resources
2,1101,AGRICULTURE PRODUCTION AND MANAGEMENT,Agriculture & Natural Resources
3,1102,AGRICULTURAL ECONOMICS,Agriculture & Natural Resources
4,1301,ANIMAL SCIENCES,Agriculture & Natural Resources
5,2401,FOOD SCIENCE,Agriculture & Natural Resources
...
