# Portofolio Imam Prasetiyo

Situs statis satu halaman (`index.html`), tanpa build. Bisa langsung di-hosting di Vercel.

## Yang perlu kamu isi dulu

Cari bagian yang berlatar kuning (kelas `fill`) di `index.html`, lalu ganti dengan datamu:

- Kontak: email, WhatsApp, GitHub
- Pengalaman: tahun, organisasi/magang, dan apa yang dikerjakan
- Proyek dan skill: tambah atau ubah sesuai kebutuhan

## Hosting lewat Vercel (lewat GitHub)

1. Buat repo baru di GitHub, misalnya `portofolio`.
2. Upload `index.html` dan `README.md` ke repo itu.
3. Buka vercel.com, login dengan akun GitHub, klik **Add New > Project**.
4. Pilih repo `portofolio`, klik **Import**.
5. Biarkan pengaturan bawaan (Framework Preset: Other), klik **Deploy**.
6. Tunggu sebentar, lalu situsmu aktif di alamat `namaproyek.vercel.app`.

Setiap kali kamu mengubah file di GitHub, Vercel otomatis memperbarui situsnya.

## Hosting lewat Vercel CLI (alternatif)

```
npm i -g vercel
cd folder-portofolio
vercel --prod
```
