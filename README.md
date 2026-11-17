# RHYS Talent Profile

| URL | Versi |
| --- | --- |
| `/` | Onboarding leads umum: 25 soal, 13 tema, tanpa konteks asuransi |
| `/agen` | Agen Internal: 32 soal, 20 tema, tafsiran industri asuransi, rencana 30 hari, catatan leader, kode hasil |

Tes onboarding singkat (25 pertanyaan, ±8 menit) untuk leads: gaya perilaku DISC + Top 5 kekuatan dari 13 tema.

- Satu file statis: `index.html` (tanpa build step, tanpa server, tanpa database).
- Hasil hanya tersimpan sementara di browser peserta (localStorage). Tidak ada data yang dikirim ke server.
- Laporan PDF A4 dibuat di browser (html2canvas + jsPDF dari cdnjs), satu segmen per halaman.
- Contoh hasil: tambahkan `#contoh` di ujung URL.

Deploy: Vercel, preset "Other", tanpa build command, output directory `.` (root).

Catatan: item dan nama tema disusun khusus oleh RHYS; bukan instrumen resmi Gallup CliftonStrengths® maupun Everything DiSC®.
