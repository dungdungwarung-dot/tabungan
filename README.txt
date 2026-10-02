CARA MEMASANG (PWA Tabungan Siswa)

1. Ganti Code.gs di Apps Script dengan Code.gs baru (hanya fungsi doGet yang berubah:
   ditambah setXFrameOptionsMode ALLOWALL). Lalu Deploy > Manage deployments >
   Edit > Version: New version > Deploy. Salin URL Web App (berakhiran /exec).

2. Buka index.html di folder ini, ganti APP_URL dengan URL /exec tadi.

3. Upload SELURUH isi folder ini ke hosting HTTPS (wajib HTTPS), pilih salah satu:
   - Netlify Drop: app.netlify.com/drop (seret folder, selesai)
   - GitHub Pages / Cloudflare Pages / Firebase Hosting

4. Buka alamat situs tersebut di Chrome Android. Tunggu beberapa detik, akan muncul
   "Instal aplikasi" (atau menu titik tiga > Instal aplikasi).
   Ikon aplikasi akan muncul di layar utama dan terbuka layar penuh.
