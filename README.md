# Content Upload Management — Static Policy Pages

Repositori ini berisi halaman statis publik untuk **Privacy Policy** (Kebijakan Privasi) dan **Terms of Service** (Ketentuan Layanan) yang dibutuhkan dalam verifikasi aplikasi/integrasi **TikTok Developer App (Login Kit / Content Posting API)** untuk proyek otomatisasi pribadi *Content Upload Management* berbasis Google Apps Script.

---

## 📄 Halaman yang Tersedia

- **`privacy.html`** : Halaman Kebijakan Privasi yang menjelaskan batasan izin data TikTok (hanya profil dasar & posting video), enkripsi token melalui *Google Apps Script Properties*, serta jaminan tanpa pembagian data pihak ketiga.
- **`term.html`** : Halaman Ketentuan Layanan yang menegaskan bahwa aplikasi ini adalah *personal internal automation tool* untuk penjadwalan konten TikTok via Google Sheets.

---

## 🎨 Teknologi & Desain

- **HTML5 & Vanilla CSS**
- **[Tailwind CSS v4](https://tailwindcss.com)** via Browser Script (`@tailwindcss/browser@4`)
- **Google Fonts** (*Plus Jakarta Sans*)
- Tampilan modern bertema *dark-mode* dengan efek ambient glow, responsive layout, dan navigasi switcher antar dokumen.

---

## 🚀 Cara Menghosting (GitHub Pages)

Halaman ini siap di-host langsung secara gratis via **GitHub Pages**:

1. Push repositori ini ke GitHub:
   ```bash
   git remote add origin https://github.com/<username>/<repo-name>.git
   git branch -M main
   git push -u origin main
   ```
2. Buka repositori di GitHub lalu pilih menu **Settings** > **Pages**.
3. Di bagian **Build and deployment**:
   - **Source**: Pilih `Deploy from a branch`
   - **Branch**: Pilih `main` (atau `master`) dan folder `/ (root)`
   - Klik **Save**.
4. URL publik Anda akan aktif di format:
   - **Privacy Policy**: `https://<username>.github.io/<repo-name>/privacy.html`
   - **Terms of Service**: `https://<username>.github.io/<repo-name>/term.html`
5. Salin kedua link tersebut ke form pendaftaran **TikTok Developer Portal** pada kolom *Privacy Policy URL* dan *Terms of Service URL*.

---

## 🔒 Catatan Keamanan
Repositori ini murni halaman statis publik dan **tidak mengandung secret key, client secret, maupun token otorisasi**. Seluruh logika dan kredensial aman tersimpan di Google Apps Script pemilik.
