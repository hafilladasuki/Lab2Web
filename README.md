# Lab2Web

# 1. Membuat dokumen HTML
<p>Langkah awal kita mulai dari bikin file HTML dulu. Ini file dasar yang nanti bakal jadi tempat kita nyambungin CSS.</p>
<li>Membuka Viusal code Studio</li>
<li>Buat file baru dengan nama lab2_css_dasar.html</li>
<li>Buat kode seperti ini</li>
<p><img width="2250" height="1318" alt="poto 1 2" src="https://github.com/user-attachments/assets/fa0561d0-34bc-4c92-adbf-6d578b7da7ab" />
</p>
<p>Hasil tampilan di choreme </p>
<p><img width="1916" height="557" alt="poto 1" src="https://github.com/user-attachments/assets/afdfb02f-63f9-4f03-9df1-13d71ed48fbd" />
</p>

# 2. Mendeklarasikan CSS Internal
<p>Setelah file HTML dasar jadi, sekarang tambahin CSS internal. CSS internal ini ditulis langsung di dalam file HTML, tepatnya di bagian <head> pake tag <style>. Jadi tidak bikin file terpisah dulu.</p>
<li>Buka file lab2_css_dasar.html yang tadi</li>
<li>Tambahin kode CSS di bagian <head> kayak gini:</li>
<p><img width="2250" height="1964" alt="poto 2 2" src="https://github.com/user-attachments/assets/813f018e-a274-4f77-ac46-e20e85fe0e7a" />
</p>
<p>Hasil Tampilan di choreme: </p>
<p><img width="1917" height="652" alt="poto 2" src="https://github.com/user-attachments/assets/eade8407-4671-49b0-ab64-d4aa7d6e8919" /> </p>

# 3. Menambahkan Inline CSS
<p>Kalau CSS internal ditulis di <head>, nah kalau inline CSS itu langsung ditempel di elemen HTML pake atribut style. Jadi efeknya cuma berlaku di elemen itu aja, tidak ngaruh ke elemen lain.</p>
<p>Misalnya kita mau ngatur paragraf biar posisinya di tengah, warnanya agak abu-abu muda. Tinggal tambahin atribut style di tag <p> </p>
<p>Contoh kode nya</p>
<img width="2926" height="1964" alt="poto 3 2" src="https://github.com/user-attachments/assets/dd00fbc7-d872-4aa8-aabe-69ab98643db4" />
<p>Contoh di Choreme nya:</p>
<p><img width="1917" height="467" alt="poto 3 " src="https://github.com/user-attachments/assets/16256565-78b6-4c8b-b402-a997407e38bf" />
</p>

# 4. Membuat CSS Eksternal
<p>Kalau internal CSS ditulis di dalam file HTML, Eksternal CSS dipisahin jadi file khusus dengan ekstensi .css. Jadi HTML sama CSS tidak bercampur, lebih mudah kalo nanti mau edit tampilan.</p>
<li>Bikin file baru di folder project, kasih nama style_eksternal.css</li>
<li>Kemudian buat kode seperti yang ada di contoh pratikum</li>
<p><img width="710" height="938" alt="poto 4 2 2" src="https://github.com/user-attachments/assets/9e6a09dd-1a0e-485c-92d4-553e8ae1719c" />
</p>
<li>Sekarang buka file lab2_css_dasar.html tadi</li>
<li>Tambahin tag <link> di dalam <head> buat nyambungin ke file CSS eksternal</li>
<p><img width="1374" height="444" alt="poto 4 2" src="https://github.com/user-attachments/assets/5a9d4f82-5793-440e-8e52-fcc4fa2a8be9" />
</p>
<p>Tampilan hasil di chorem:</p>
<p><img width="1917" height="481" alt="poto 4" src="https://github.com/user-attachments/assets/c450aa0e-3d80-4ec6-8a05-4c122467dc97" />
</p>

# 5. Menambahkan CSS selector
<p>Di agian ini kita belajar selector. Fungsinya simpel: biar CSS tau mau ngatur style buat elemen yang mana. Jadi kita gak asal kasih warna atau ukuran font, tapi lebih spesifik</p>
<li>ID (#) = buat sesuatu yang unik</li>
<li>Class (.) = bisa dipake berulang-ulang.</li>
<p>Contoh code yang ada di pratikum:</p>
<p> <img width="772" height="1242" alt="poto 5" src="https://github.com/user-attachments/assets/c25378e8-bb36-49b2-8805-256025f45db7" />
</p>
<p>Hasil dari code tersebut di chorem:</p>
<p><img width="950" height="586" alt="Screenshot 2025-09-30 210954" src="https://github.com/user-attachments/assets/d5409c6c-922e-4813-bfb3-1f79b6ea105d" />
</p>

# TUGAS PRATIKUM! FINISH



# Selanjutnya pernyataan dan tugas!

<p><img width="845" height="305" alt="Screenshot 2025-09-30 211220" src="https://github.com/user-attachments/assets/751862b2-fcc0-410d-a26a-0dfe0b8a367a" />
</p>

<b>1. Eksperimen Properti CSS</b>
<p>Kita bisa mengubah atau menambahkan properti CSS biar tampilan halaman berubah.</p>
<p>Contohnya:</p>
<p><img width="804" height="634" alt="tugas 1" src="https://github.com/user-attachments/assets/db76d970-92f2-4a85-a9b6-17c72b0d47a2" />
</p>
<p>Hasilnya:</p>
<p><img width="967" height="557" alt="tugas 1 2" src="https://github.com/user-attachments/assets/18b11440-8273-4426-824f-312317585680" />
</p>
<b>2. Perbedaan h1 {…} dengan #intro h1 {…}</b>
<p>h1 {…} → berlaku ke semua elemen <h1> di halaman.</p>
<p>#intro h1 {…} → hanya berlaku untuk <h1> yang ada di dalam elemen dengan ID intro</p>
<b>3. Prioritas CSS (Internal, Eksternal, Inline)</b>
<p>Contoh code:</p>
<p><img width="1248" height="672" alt="tugas 3" src="https://github.com/user-attachments/assets/9dc945cf-50c2-45d5-868f-4f62f75837ce" />
</p>
<p>Hasil Code: </p>
<p><img width="736" height="511" alt="tugas 3 2" src="https://github.com/user-attachments/assets/9b5fd55d-fa64-4ba3-80db-68bcf2868f3b" />
</p>
<b>4. Jika Elemen Punya ID dan Class</b>
<p>Kalau elemen punya ID dan Class sekaligus, ID lebih kuat daripada Class.</p>
<p>Contoh kode di HTML:</p>
<p><img width="558" height="596" alt="tugas 4 2" src="https://github.com/user-attachments/assets/f1018597-41dd-4a16-a807-2f92d4e4ed67" />
</p>
<p>Contoh code di CSS</p>
<p><img width="1050" height="520" alt="tugas 4 3" src="https://github.com/user-attachments/assets/af77a896-05ca-4e4c-90ae-2bc29ccaaead" />
</p>
<p>Hasil dari Chorom:</p>
<p><img width="965" height="672" alt="Tugas 4" src="https://github.com/user-attachments/assets/3e4348a2-7752-459d-8115-66968674a3ed" />
</p>
<p>Hasil: teks merah, karena aturan ID mengalahkan Class.</p>

# SELESAI
















