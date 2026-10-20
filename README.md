# Tugas Sistem Rekomendasi

## Identitas Mahasiswa

- **Nama:** Faiz Azmin Ahmad
- **NIM:** 24031554175
- **Kelas:** 2024A
- **Program Studi:** S1 Sains Data
- **Universitas:** Universitas Negeri Surabaya (UNESA)

## Deskripsi

UTS Graf Sains Data

## Teknologi yang Digunakan

- Python
- Neo4j
- Pandas
- NumPy
- SciPy
- Scikit-learn
- NetworkX

## Metode

1. Pengambilan data interaksi pengguna dan item dari Neo4j.
2. Pembobotan interaksi pengguna.
3. Pembentukan matriks User-Item menggunakan VSM.
4. Perhitungan kemiripan menggunakan Cosine Similarity.
5. Pencarian 5 tetangga terdekat menggunakan KNN.
6. Pembuatan Top 3 rekomendasi item.
7. Evaluasi rekomendasi menggunakan Hit@5 dan NDCG@5.

## Cara Menjalankan

1. Pastikan Python dan Neo4j sudah terpasang.
2. Instal pustaka yang diperlukan:

   ```bash
   pip install neo4j pandas numpy scipy scikit-learn networkx
   ```

3. Jalankan Neo4j dan sesuaikan konfigurasi koneksi database pada kode Python.
4. Jalankan notebook atau script Python proyek.
5. Periksa hasil rekomendasi dan evaluasi yang dihasilkan.

---

**Mata Kuliah:** Graf Sains Data
**Tahun Akademik:** 2026
