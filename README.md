1. Mulai dari Halaman kosong dengan nama file <img width="1366" height="768" alt="Cuplikan layar 2025-09-29 124632" src="https://github.com/user-attachments/assets/bb9d90ff-bfb5-4318-b5db-876416d7d6bd" />
2. Membuat Dokumen HTML <img width="1366" height="768" alt="Cuplikan layar 2025-09-29 124716" src="https://github.com/user-attachments/assets/22353f67-d4a4-4e4c-8368-a53bf90195fa" />
3. Mendeklarasikan CSS internal pada bagian Head Dokumen <img width="1366" height="768" alt="Cuplikan layar 2025-09-29 124803" src="https://github.com/user-attachments/assets/c5963bd6-6eb6-4a6c-ad5f-a5081f2afd64" />
4. Menambahkan Inline CSS pada tag <p> <img width="1366" height="768" alt="Cuplikan layar 2025-09-29 132754" src="https://github.com/user-attachments/assets/46b28729-41fb-4087-b2b0-ea91d7d50f30" />
5. Membuat File baru dengan nama style_eksternal.css kemudian buat deklarasi <img width="1366" height="768" alt="Cuplikan layar 2025-09-29 132857" src="https://github.com/user-attachments/assets/3db3355e-ce8e-4f3e-87a7-2efb67efce66" />
6. Menambahkan CSS selektor menggunakan ID dan Class Selector. Pada file
style_eksternal.css <img width="1366" height="768" alt="Cuplikan layar 2025-09-29 133049" src="https://github.com/user-attachments/assets/8b4a3acc-ac03-4bfc-a237-31a4c6a8f2ed" />


Jawaban Pertanyaan dan tugas

2. h1 {...}
Ini adalah selector elemen langsung. Artinya, aturan CSS ini berlaku untuk semua elemen <h1> di halaman.

#intro h1 {...}
Ini adalah selector gabungan yang lebih spesifik. Aturan CSS ini hanya berlaku untuk elemen <h1> yang berada di dalam elemen dengan id="intro". Jadi, jika ada elemen <h1> di luar elemen #intro, aturan ini tidak berlaku untuk mereka.

3. - CSS Eksternal: di-link dari file .css terpisah.
- CSS Internal: ditulis di dalam <style> di bagian <head> HTML.
- CSS Inline: ditulis langsung pada elemen HTML menggunakan atribut style.

Prioritasnya (dari yang paling rendah ke paling tinggi):
Eksternal < Internal < Inline

Jadi, apabila ada ketiga deklarasi pada elemen yang sama, yang ditampilkan browser adalah inline CSS karena memiliki prioritas tertinggi.

4. Selector ID (#id) memiliki spesifisitas lebih tinggi dibandingkan selector Class (.class).
Jadi, jika ada aturan untuk ID dan Class yang bertentangan, maka aturan dari ID yang akan diterapkan.

