# Kupon Sembako

Kupon sembako ber-QR untuk pembagian di gereja. Satu HP petugas, jalan offline setelah dibuka sekali.

Alamat: https://jonathanadr111-sudo.github.io/kupon-sembako/

## Pakai

1. Buka halaman ini di Chrome HP, lalu menu Chrome > **Tambahkan ke layar utama**.
2. Tab **Atur**, masuk PIN `1234`, ganti PIN dan isi judul kupon.
3. Tab **Daftar**, tempel nama jemaat satu per baris, tekan **Buat kupon**.
4. Bagikan: **Cetak semua**, tombol **QR** per nama (Bagikan ke WhatsApp), atau **Salin teks**.
5. Hari H: tab **Scan**, arahkan kamera ke QR. Hijau VALID, kuning SUDAH DIAMBIL, merah TIDAK ADA.
6. Setelah acara: **Rekap CSV** dan **Cadangkan (JSON)**.

## Catatan

- Data tersimpan di HP petugas (penyimpanan Chrome), tidak dikirim ke mana pun. Setiap perubahan ditulis dua kali, kunci utama dan cermin, dan dipulihkan otomatis kalau kunci utama rusak.
- Data terikat alamat halaman ini. Kalau alamatnya berubah, data lama tidak ikut, jadi ekspor JSON dulu.
- Membersihkan data situs di Chrome akan menghapus kupon. Simpan cadangan JSON sebelum dan sesudah acara.
- PIN hanya penghalang salah tekan, bukan pengamanan.
