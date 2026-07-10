Berikut isi README.md yang bisa langsung kamu taruh di repo GitHub:

```markdown
# Lua Obfuscator by Paanz Studio

<p align="center">
  <img src="https://z-cdn-media.chatglm.cn/files/337aecdb-af39-44e8-b685-595dabc566a2.png?auth_key=1883685780-46c312760765410f82375d81279197c5-0-8a75792d8d218cbb1569dfb06ca7b893" alt="Paanz Studio" width="200">
</p>

<p align="center">
  <strong>Lua Obfuscator by Paanz Studio</strong><br>
  Proteksi kode Lua multi-layer dengan antarmuka web modern.
</p>

<p align="center">
  <a href="https://alfanrizkyw.github.io/Lua-Obfuscator-By-Paanz-Studio/" target="_blank">
    <img src="https://img.shields.io/badge/Live%20Demo-Kunjungi%20Web-4a90d9?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyMCIgaGVpZ2h0PSIyMCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNkMGQ4ZTgiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIj48cGF0aCBkPSJNMTggMTN2NmEyIDIgMCAwIDEtMiAySDVhMiAyIDAgMCAxLTItMlY4YTIgMiAwIDAgMSAyLTJoNiI+PC9wYXRoPzxwb2x5bGluZSBwb2ludHM9Ix42IDE1IDEyIDkgMTUuNCA1LjYiPjwvcG9seWxpbmU+PC9zdmc+" alt="Live Demo">
  </a>
</p>

---

## Tentang Project

Lua Obfuscator by Paanz Studio adalah alat berbasis web untuk melindungi kode Lua agar tidak dapat dibaca, di-decompile, atau dimodifikasi oleh pihak yang tidak berwenang. Kode Lua yang diobfuscasi tetap berfungsi 100% sama seperti aslinya, namun strukturnya sudah diacak secara total melalui 7 lapisan proteksi.

## Fitur Utama

- **7-Layer Obfuscation** — UTF-8 encoding, shift cipher, hex encoding, chunk splitting, variable mangling, indirect access, dan dead code injection
- **Sistem Folder** — Kelola banyak kode Lua dalam folder terorganisir
- **Auto-Save Permanen** — Semua data tersimpan di perangkat user, tidak hilang meskipun browser ditutup
- **Dua Tampilan** — Tab terpisah untuk kode asli dan kode terobfuscasi
- **Copy ke Clipboard** — Salin kode asli maupun hasil obfuscasi dengan satu klik
- **Responsif 100%** — Berfungsi optimal di desktop, tablet, dan mobile
- **Watermark** — Setiap kode yang diobfuscasi otomatis menyertakan watermark tanpa mengganggu fungsi kode
- **Tanpa Server** — Semua proses berjalan di browser, tidak ada kode yang dikirim ke server manapun

## Teknik Obfuscasi

| Lapisan | Teknik |
|---------|--------|
| 1 | UTF-8 byte encoding |
| 2 | Shift cipher dengan kunci acak |
| 3 | Konversi ke hexadesimal |
| 4 | Pecah data menjadi 2-6 chunk |
| 5 | Pengacakan urutan chunk |
| 6 | Variable name mangling (7-14 karakter acak) |
| 7 | Dead code injection (7 pola berbeda) |

## Cara Pakai

1. Buka [Lua Obfuscator by Paanz Studio](https://alfanrizkyw.github.io/Lua-Obfuscator-By-Paanz-Studio/)
2. Buat folder baru, lalu buat kode baru di dalamnya
3. Tempelkan kode Lua Anda di tab **Kode Asli**
4. Klik tombol **Obfuscasi**
5. Salin hasilnya di tab **Terobfuscasi**

## Keyboard Shortcut

| Shortcut | Fungsi |
|----------|--------|
| `Ctrl + S` | Simpan manual |
| `Ctrl + Shift + O` | Jalankan obfuscasi |
| `Escape` | Tutup modal/sidebar |
| `Tab` | Indent di editor |

## Tech Stack

- HTML5, CSS3, JavaScript (Vanilla)
- localStorage untuk penyimpanan permanen
- TextEncoder API untuk encoding UTF-8
- Tidak memerlukan server atau backend

## Created by

<p align="center">
  <img src="https://z-cdn-media.chatglm.cn/files/337aecdb-af39-44e8-b685-595dabc566a2.png?auth_key=1883685780-46c312760765410f82375d81279197c5-0-8a75792d8d218cbb1569dfb06ca7b893" alt="Paanz Studio" width="120"><br><br>
  <strong>Paanz Studio</strong><br>
  <a href="https://alfanrizkyw.github.io/Lua-Obfuscator-By-Paanz-Studio/" target="_blank">alfanrizkyw.github.io/Lua-Obfuscator-By-Paanz-Studio</a>
</p>

---

<p align="center">
  <sub>Built with precision by Paanz Studio</sub>
</p>
```
