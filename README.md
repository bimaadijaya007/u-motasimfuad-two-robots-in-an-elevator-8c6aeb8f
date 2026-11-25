# Two Robots in an Elevator — README

## Konsep

Baris entry ini adalah satu kalimat percakapan canggung di dalam lift,
diucapkan satu robot kepada robot lain. Premisnya sederhana: sebuah mesin
yang secara teori bisa menghitung segalanya justru gagal total pada hal
paling manusiawi — basa-basi di ruang sempit.

## Kenapa lucu

1. **Logika mesin yang berlebihan.** Robot ini tidak sekadar gugup; ia
   menjalankan lebih dari seribu simulasi hanya untuk memutuskan apakah
   pantas mengomentari cuaca. Usaha komputasi yang sangat besar untuk
   keputusan yang sangat kecil adalah inti leluconnya — mesin yang
   over-engineering hal sepele.
2. **Kecanggungan lift yang universal.** Lift memaksa dua makhluk asing
   berdiri berdekatan dalam diam. Situasi itu sudah canggung bagi manusia;
   bagi robot, kecanggungan itu berubah menjadi kegagalan sistem: kipas
   pendinginnya "memilih diam", seolah-olah diam adalah hasil komputasi,
   bukan sekadar tidak ada yang dikatakan.
3. **Punchline sebagai pengalihan.** Setelah pengakuan memalukan itu,
   robot buru-buru menyebut nomor lantai dan menyindir sensor lawan yang
   mungkin sedang "buffering". Itu pola klasik percakapan canggung:
   mengakui keanehan, lalu kabur ke topik aman yang sangat literal.
   Sindiran balik ke robot kedua juga menjaga keseimbangan — bukan satu
   robot yang aneh, melainkan dua-duanya.

## Kesesuaian dengan brief

- **Dua robot, satu lift:** setting dan kedua karakternya jelas dari
  situasinya — dua mesin yang terjebak bersama di ruang kecil.
- **Satu baris, satu momen:** tidak ada setup panjang; seluruh lelucon
  (simulasi, diam, pengalihan) terjadi dalam satu kalimat yang dibaca
  sekali jalan.
- **Nada robot yang khas:** angka simulasi yang spesifik, kipas
  pendingin, dan sensor yang buffering memberi suara mesin yang
  konsisten tanpa perlu menjelaskan bahwa pembicaranya robot.

## Kepatuhan batas karakter

Baris entry berjumlah 143 karakter, di bawah batas 200 karakter yang
ditetapkan brief. Program mencetak tepat satu baris itu sebagai output
utama (lihat `main.ts`), tanpa teks tambahan yang bisa melanggar batas.

## Struktur entry

- `main.ts` — mencetak baris entry sebagai output utama.
- `README.md` — dokumen ini: konsep, analisis humor, dan kepatuhan batas.
- `VARIANTS.md` — dua baris alternatif orisinal dan alasan keduanya
  kurang kuat dibanding baris utama.
