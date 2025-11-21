# API-Testing-Postman-Collection

Ini adalah portofolio yang berfokus pada pengujian *backend* menggunakan **Postman** untuk memverifikasi fungsionalitas dan integritas data API. Proyek ini menguji *flow* dasar transaksi data yang vital dalam sistem modern.

---

## 🛠️ Technology & Tools Used

| Kategori | Tool/Teknologi | Fungsi dalam Proyek |
| :--- | :--- | :--- |
| **API Client** | Postman | Digunakan untuk mengirim *request* dan memvisualisasikan respons. |
| **Scripting** | JavaScript (di Postman) | Digunakan untuk membuat *Test Assertions* dan *pre-request scripts*. |
| **Testing Type** | Functional Testing, Integration Testing | Memastikan setiap *endpoint* API berfungsi sesuai spesifikasi. |
| **Tested API** | [DummyJSON API] | Digunakan untuk simulasi data user dan produk |

---

## Key Achievements & Concepts Tested

Proyek ini membuktikan kemampuan saya dalam memahami dan mengimplementasikan konsep penting dalam API Testing:

1.  **CRUD Assertion:**
    * Membuat *test script* untuk memverifikasi fungsionalitas **Create, Read, Update, dan Delete (CRUD)**.
    * Memastikan kode status (**Status Code**) dan struktur respons (**Response Body**) sesuai harapan.

2.  **Request Chaining (Flow Testing):**
    * Mengimplementasikan teknik **Request Chaining** (menggunakan variabel lingkungan) untuk mengalirkan data dari satu *request* ke *request* berikutnya.
    * *Contoh:* Mengambil `user_ID` dari *response* **POST** (Create User) dan menggunakannya di *request* **GET** berikutnya (Get User Detail).

3.  **Basic JavaScript Scripting:**
    * Menggunakan `pm.test` dan `pm.expect` untuk menulis *assertion* yang memastikan validasi data yang ketat.

4.  **Collection Runner & Report:**
    * Menjalankan seluruh *test case* secara otomatis menggunakan **Collection Runner** Postman.

---

## ⚙️ How to Run This Collection

Anda dapat menjalankan seluruh *test suite* ini dengan mudah di Postman:

1.  **Download:** Unduh file **API Test (Dummy API)** yang ada di *repository* ini.
2.  **Import:** Buka Postman, klik **Import**, dan unggah file JSON tersebut.
3.  **Run:** Pilih *Collection* yang sudah di-*import*, klik **Run** atau **Collection Runner**, dan jalankan seluruh *request* untuk melihat *test assertion* bekerja.
