# Identitas Mahasiswa

**Nama :** Afdhal Agislam  
**NIM :** 312410445  
**Kelas :** TI.24.A5  

---

## HASIL OUTPUT

<img width="959" height="539" alt="image" src=Tampilan akhir.png />


# Praktikum 2 - CSS Dasar

##  Deskripsi
Praktikum ini membahas dasar-dasar penggunaan **CSS (Cascading Style Sheets)** pada dokumen HTML.  
Tujuannya adalah memahami tiga cara penggunaan CSS (**inline, internal, eksternal**) serta mengenal selector (**tag, id, class**).  

##  Struktur Folder


##  Langkah Praktikum
1. **Membuat file `lab2_css_dasar.html`**  
   - Menambahkan CSS **internal** dalam tag `<style>`.  
   - Menambahkan contoh CSS **inline** langsung pada elemen `<p>`.  
   - Melatih penggunaan selector: elemen (`h1`), id (`#intro`), dan class (`.button`).  

2. **Membuat file `style_eksternal.css`**  
   - Memisahkan aturan styling dari file HTML.  
   - Berisi deklarasi CSS untuk body, header, nav, id selector, class selector, dan footer.  

3. **Membuat file `lab2_css_eksternal.html`**  
   - Menghubungkan HTML dengan CSS eksternal menggunakan tag `<link>`.  
   - Menampilkan hasil styling yang sama seperti internal CSS tetapi lebih rapi dan terpisah.  

4. **Menguji Cascade & Prioritas CSS**  
   - Inline CSS memiliki prioritas tertinggi dibanding internal dan eksternal.  
   - Selector `id` lebih kuat dibanding selector `class`.  
   - Jika semua aturan ada, maka urutan prioritas: **inline > id > class > elemen** (kecuali ada `!important`).  

5. **Validasi CSS**  
   - CSS divalidasi menggunakan [W3C CSS Validator](https://jigsaw.w3.org/css-validator/).

##  Jawaban Pertanyaan
**1. Perbedaan selector `h1` dan `#intro h1`**  
- `h1 { ... }` → berlaku untuk semua elemen `<h1>`.  
- `#intro h1 { ... }` → hanya berlaku untuk `<h1>` yang ada di dalam elemen dengan id `intro`.  

**2. Urutan prioritas jika ada inline, internal, dan eksternal CSS pada elemen yang sama**  
- Inline CSS memiliki prioritas paling tinggi.  
- Internal CSS lebih tinggi daripada eksternal CSS.  
- External CSS digunakan jika tidak ada aturan inline maupun internal.  

**3. Jika sebuah elemen punya `id` dan `class`, mana yang dipakai?**  
- ID (`#id`) lebih spesifik dan lebih kuat dibanding class (`.class`).  
- Jadi, aturan CSS dengan id akan dipakai jika ada konflik dengan aturan class.  

##  Screenshot

### Tampilan CSS Internal
![Tampilan CSS Internal](screenshots/internal.png)

### Tampilan CSS Eksternal
![Tampilan CSS Eksternal](screenshots/eksternal.png)


##  Kesimpulan
- CSS dapat ditulis dalam 3 cara: **inline, internal, dan eksternal**.  
- Penggunaan CSS eksternal lebih direkomendasikan karena memisahkan struktur HTML dan aturan tampilan.  
- Pemahaman cascade & specificity sangat penting agar styling konsisten.  


