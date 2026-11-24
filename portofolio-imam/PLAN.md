# Rencana Portofolio Imam Prasetiyo

Target: portofolio pribadi yang tayang di Vercel dan bisa dikirim ke dosen, teman, atau perusahaan saat melamar magang.

## 1. Siapkan alat

- [ ] Install **VS Code** (sudah ada)
- [ ] Install **Git** (git-scm.com)
- [ ] Punya akun **GitHub** dan akun **Vercel** (login Vercel pakai GitHub)
- [ ] Di VS Code, pasang ekstensi **Live Server** (Ritwick Dey) untuk preview

## 2. Buka proyek di VS Code

1. Ekstrak `portofolio-imam.zip`
2. Di VS Code: **File > Open Folder**, pilih folder `portofolio-imam`
3. Klik kanan `index.html` > **Open with Live Server**
4. Halaman terbuka di browser dan otomatis refresh tiap kamu simpan file

## 3. Isi data sendiri

Cari bagian berlatar kuning (kelas `fill`) dengan `Ctrl + F` lalu ketik `fill`.

- [ ] Email, WhatsApp, GitHub di bagian Kontak
- [ ] Pengalaman: tahun, organisasi/magang, tugas yang dikerjakan
- [ ] Tambah foto atau ganti kartu identitas kalau mau
- [ ] Tambah link "Lihat proyek" untuk tiap proyek yang sudah online atau ada di GitHub
- [ ] Tambah proyek baru: salin satu blok `<article class="box proj">` lalu ubah isinya

## 4. Cek sebelum diunggah

- [ ] Tidak ada tulisan latar kuning yang tertinggal
- [ ] Buka di HP (atau perkecil jendela browser), pastikan tidak ada yang terpotong
- [ ] Semua menu di atas bisa diklik dan menuju bagian yang benar
- [ ] Ejaan nama kampus dan proyek sudah benar

## 5. Unggah ke GitHub

Di terminal VS Code (**Terminal > New Terminal**):

```
git init
git add .
git commit -m "portofolio pertama"
git branch -M main
git remote add origin https://github.com/USERNAME/portofolio.git
git push -u origin main
```

Ganti `USERNAME` dengan username GitHub-mu. Buat dulu repo kosong bernama `portofolio` di github.com.

## 6. Tayang di Vercel

1. Buka vercel.com, login dengan GitHub
2. **Add New > Project**, pilih repo `portofolio`, klik **Import**
3. Biarkan pengaturan bawaan, klik **Deploy**
4. Situs aktif di `namaproyek.vercel.app`

Setelah itu, tiap kamu `git push`, Vercel otomatis memperbarui situs.

## 7. Setelah tayang

- [ ] Pasang link situs di profil GitHub dan LinkedIn
- [ ] Ganti nama proyek di Vercel (Settings) kalau alamatnya kurang enak, misalnya `imam-prasetiyo.vercel.app`
- [ ] Perbarui isi tiap selesai tugas atau proyek baru

## Catatan

- Data diri yang sensitif (NPM, alamat rumah, nomor KTP) sebaiknya tidak dipasang di situs publik.
- Ilustrasi, foto, dan teks dari portofolio orang lain jangan disalin. Pakai milikmu sendiri.
