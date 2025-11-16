==================================================
PROYEK N8N: SISTEM ANALISIS SURVEI MAKRAB DENGAN AI
==================================================

## Tautan Video
1. Video Demonstrasi (3-5 Menit):
 https://drive.google.com/file/d/1Q9zguYRCAYFXY2A0mK4k9INs2EG1p_o4/view?usp=sharing

2. Video Presentasi Final (8-15 Menit):
   https://drive.google.com/file/d/1VEP1KvDry-p_1u7tpvSr-USoZXLRvTLV/view?usp=sharing

## Kredensial untuk Pengujian
*PERINGATAN:* Kredensial ini bersifat sementara dan akan dinonaktifkan setelah penilaian.

1. Kredensial n8n:
   - URL n8n Cloud: [MASUKKAN_URL_N8N_CLOUD_ANDA, contoh: https://app.n8n.cloud/abc123]
   - Email/Username: [MASUKKAN_EMAIL_ANDA]
   - Password: [BUAT_DAN_MASUKKAN_PASSWORD_SEMENTARA]

2. API Key untuk Layanan AI (Google Gemini):
   - API Key: [MASUKKAN_API_KEY_GEMINI_ANDA_YANG_SUDAH_DIBUAT]
   - Cara Membuat API Key Gemini: 
     1. Kunjungi: https://aistudio.google.com/app/apikey
     2. Buat API Key baru (Create API Key)
     3. Salin dan tempel di sini.

3. Akses ke Spreadsheet Contoh (Opsional tapi sangat disarankan):
   - URL Spreadsheet: [TAUTAN_KE_GOOGLE_SHEETS_CONTOH]
   - (Pastikan Anda telah memberikan hak akses 'edit' atau 'view' ke email penguji)

## Instruksi Singkat Menjalankan Demo

LANGKAH 1: IMPORT WORKFLOW
1. Login ke akun n8n yang disediakan di atas.
2. Di halaman utama, klik "Import from file".
3. Unggah file Workflow_Analisis_Makrab_AI.json.
4. Workflow Anda akan muncul di canvas.

LANGKAH 2: KONFIGURASI KREDENSIAL
1. Di workflow yang telah diimpor, klik node "Kumpulkan Data" (atau node AI lainnya).
2. Di panel setup node, akan ada bagian untuk memasukkan "Google Gemini API Key".
3. Klik tombol "Add New Credential" dan pilih "Google Gemini".
4. Masukkan API Key Gemini yang telah disediakan di bagian atas file ini.
5. Klik "Save" untuk menyimpan kredensial.

LANGKAH 3: JALANKAN WORKFLOW (MANUAL TEST)
1. Klik tombol "Execute Workflow" di pojok kanan atas.
2. Workflow akan berjalan. Anda dapat memantau prosesnya di panel "Execution".
3. Setelah selesai, periksa node "Simpan ke Spreadsheet".
   - Klik pada node tersebut.
   - Di panel kanan, pilih tab "Output".
   - Di sana Anda dapat melihat data yang akan ditulis ke spreadsheet, termasuk hasil analisis AI.

LANGKAH 4: VERIFIKASI DI SPREADSHEET (Langsung)
1. Buka link Google Sheets yang telah disediakan.
2. Anda akan melihat ada baris baru yang ditambahkan, yang berisi hasil analisis AI dari data input terbaru.

CATATAN TROUBLESHOOTING:
- Jika workflow gagal, periksa "Logs" di n8n untuk melihat pesan error detailnya.
- Pastikan koneksi antara n8n dan Google Sheets berjalan baik (kredensial Google sudah dikonfigurasi di node Sheets).
- Pastikan API Key Gemini masih aktif dan memiliki kuota.

---
Untuk pertanyaan lebih lanjut, silakan hubungi: foris.hulu25@gmail.com
