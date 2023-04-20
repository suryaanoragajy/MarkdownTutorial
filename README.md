# Tutorial Markdown

<p align="center">
  <img src="https://www.nicepng.com/png/detail/187-1870373_44191585-markdown-logo.png" style="display: block; margin: auto;" width="200"/>
</p>

**MARKDOWN** adalah format penulisan teks yang digunakan untuk menulis dokumen yang dapat dengan mudah diubah menjadi format lain seperti HTML, PDF, atau *Rich Text Format* (RTF). Format ini dirancang untuk memudahkan penulis dalam membuat dokumen dengan cara yang sederhana, intuitif, dan mudah dibaca. Markdown juga digunakan dalam file README untuk memberikan informasi tentang suatu *repository*, memberikan penjelasan code pada Jupyter Notebook dan lain sebagainya. Berikut ini akan dijelaskan mengenai beberapa hal yang dapat dilakukan pada file markdown.

<hr>

## **1. Heading**
Heading digunakan untuk membuat *section* atau bab yang berfungsi untuk memisahkan konten satu dan lainnya. Heading dibuat dengan awalan **'#'**. Terdapat 6 tingkatan pada heading dimana semakin banyak **'#'** maka ukuran heading akan semakin kecil.

```
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```
atau juga dapat ditulis dalam HTML seperti berikut
```
<h1>Heading 1</h1> 
<h2>Heading 2</h2> 
<h3>Heading 3</h3> 
<h4>Heading 4</h4> 
<h5>Heading 5</h5> 
<h6>Heading 6</h6> 
```
Output :
><h1>Heading 1</h1> <h2>Heading 2</h2> <h3>Heading 3</h3> <h4>Heading 4</h4> <h5>Heading 5</h5> <h6>Heading 6</h6>  

Pada VS Code, penggunaan tingkatan heading ini akan terlihat pada bagian outline. Biasanya heading 1 untuk judul, heading 2 untuk bab, heading 3 untuk subbab dan seterusnya sehingga penggunaan heading ini membuat dokumen menjadi lebih terstruktur.
<hr>

## **2. Font Style**
Terdapat beberapa font style yang dapat digunakan seperti **bold**, *italic*, ***bold dan italic*** dan ~~strikethrough~~.

1. **Bold**  
   Untuk membuat tulisan menjadi tebal, tambahkan dua asterisk (**) atau dua underscore(__) di awal dan akhir tulisan yang akan di-bold
   ```
   **This is bold text**
   __This is bold text__
   ```  
   Cara lain, di VS Code, blok tulisan yang akan di-bold kemudian tekan `ctrl+B`

   Output:  
   **This is bold text**
  
2. *Italic*  
   Untuk membuat tulisan menjadi miring, tambahkan satu asterisk (*) atau satu underscore (_) di awal dan akhir tulisan yang akan di-italic
   ```
   *This is italic text*
   _This is italic text_
   ```
   Cara lain, di VS Code, blok tulisan yang akan di-italic kemudian tekan `ctrl+I`

   Output:  
   *This is italic text*  

   
3. ***Bold dan italic***  
      Untuk membuat tulisan menjadi tebal dan miring, lakukan cara yang sama seperti poin 1 dan 2 di atas dengan urutan *italic* terlebih dahulu kemudian **bold**.
   ```
   ***This is bold & italic text***
   ___This is bold & italic text___
   ```
   Output:  
   ***This is bold & italic text***

4. ~~Strikethrough~~  
    Strikethrough digunakan untuk mencoret suatu tulisan. Untuk melakukan strikethrough, tambahkan dua tilde (~) di awal dan akhir tulisan
   ```
   ~~This is strikethrough text~~
   ```
   Output:  
   ~~This is strikethrough text~~

---
## **3. Text Alignment**
Untuk membuat teks menjadi rata kiri, tengah, kanan dan justify, dapat menggunakan format HTML.  
1. Left Align   
   Untuk membuat teks menjadi rata kiri dapat menggunakan
   ```
   <p align="left">This text is aligned to the left.</p>
   ```
   Output:  
    <p align="left">This text is aligned to the left.</p>

2. Center Align  
   Untuk membuat teks menjadi rata tengah dapat menggunakan
   ```
   <p align="center">This text is centered.</p>
   ```
   Output:
   <p align="center">This text is centered.</p>

3. Right align  
   Untuk membuat teks menjadi rata kanan dapat menggunakan
   ```
   <p align="right">This text is aligned to the right.</p>
   ```
   Output:  
   <p align="right">This text is aligned to the right.</p>

4. Justify  
   Untuk membuat teks menjadi rata kanan kiri dapat menggunakan
   ```
   <p align="justify"> Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum ultrices, turpis ac tristique ultricies, quam sapien sagittis sapien, nec bibendum enim libero non diam. Nam elementum velit nec felis finibus vehicula.
   ```
   Output:
   <p align="justify"> Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum ultrices, turpis ac tristique ultricies, quam sapien sagittis sapien, nec bibendum enim libero non diam. Nam elementum velit nec felis finibus vehicula.</p>

---

## **4. Highlight, Font Color and Change Font**
Untuk membuat highlight dan mengganti warna teks dapat menggunakan format HTML.  
   1. Highlight  
      Untuk menandai suatu teks. Biasanya memiliki background kuning.
      ```
      <mark>This text is highlighted</mark>
      ```
      Output:  
      <mark>This text is highlighted</mark>

   2. Font Color
      Untuk mengganti warna teks gunakan
      ```
      <font color="red">This text is red</font>  
      ```
      Output:  
      <font color="red">This text is red</font>  
      Terdapat banyak pilihan warna, misalkan "red","green","blue","cyan","magenta","yellow","black","white","lightgreen","lightblue", dan lainnya  

      Warna teks juga dapat diubah menggunakan *six-digit hex color*. Contohnya
      ```
      <span style="color:#33FFCE;">Your text here</span>
      ```
      Output:  
      <span style="color:#33FFCE;">Your text here</span>
   
   3. Change Font  
      Untuk mengganti jenis font gunakan
      ```
      <span style="font-family:Times New Roman"> Font Tulisan dalam Times New Roman </span>
      ```
      Output:  
      <span style="font-family:Times New Roman"> Font Tulisan dalam Times New Roman </span>
---
## **5. Lists**
Berikut ini cara menggunakan numbered, bulleted, nested, to-do, dan mixed list.  
1. Numbered List
   ```
      1. First item
      2. Second item
      3. Third item
   ```
   Output:  
      1. First item  
      2. Second item  
      3. Third item
   
2. Bulleted List
   ```
      - First item
      - Second item
      - Third item
   ```
   Output:  
   - First item
   - Second item  
   - Third item
  
3. Nested List  
   ```
   - First item
     - Sub-item 1
     - Sub-item 2
   - Second item
     - Sub-item 1
     - Sub-item 2
   ```
   Output:  
   - First item
     - Sub-item 1
     - Sub-item 2
   - Second item
     - Sub-item 1
     - Sub-item 2
 
 4. To-Do List  
    ```
      - [x] Completed task
      - [ ] Incomplete task
      - [ ] Another incomplete task
    ```
      Output:  
      - [x] Completed task
      - [ ] Incomplete task
      - [ ] Another incomplete task


5. Mixed List  
   ```
   1. First item
      - Sub-item 1
      - Sub-item 2
   2. Second item
      1. Sub-item 1
      2. Sub-item 2
         - Sub-sub-item 1
         - Sub-sub-item 2
   3. Third item  
      - [x] Completed task
      - [ ] Incomplete task
      - [ ] Another incomplete task
   ```
   Output:   
   1. First item
      - Sub-item 1
      - Sub-item 2
   2. Second item
      1. Sub-item 1
      2. Sub-item 2
         - Sub-sub-item 1
         - Sub-sub-item 2
   3. Third item  
      - [x] Completed task
      - [ ] Incomplete task
      - [ ] Another incomplete task   

---
## 6. Quote, Inline, Block Code
1. Quote
   Quote digunakan untuk mengutip kalimat atau code. Untuk melakukan quote, tambahkan simbol lebih dari ">" di awal teks
   ```
   > Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum ultrices, turpis ac tristique ultricies, quam sapien sagittis sapien, nec bibendum enim libero non diam. Nam elementum velit nec felis finibus vehicula.
   ```
   Output:  
   > Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum ultrices, turpis ac tristique ultricies, quam sapien sagittis sapien, nec bibendum enim libero non diam. Nam elementum velit nec felis finibus vehicula.

2. `Inline code`  
   Inline code digunakan untuk menampilkan code dalam suatu kalimat. Untuk melakukan inline, tambahkan backtick (`) di awal dan akhir tulisan
   ```
   This is regular text `and this is inline code`
   ```
   Output:  
   This is regular text `and this is inline code`

3. Block Code  
   Block code digunakan untuk menampilkan code tanpa mengeksekusinya. Gunakan tiga backtick (```) di line pertama dan terakhir code.
   ```
   ```                                                                      **This is bold text**                                                       ```
   ```
   Output:  
   ```
   **This is bold text**
   ```
---
## 7. Horizontal Line
Biasanya digunakan untuk pembatas antar section. Untuk menggunkannya dengan cara tiga dash "---" atau dengan `<hr>`.  

---
## 8. Link
Untuk menuliskan link yang dapat diklik (hyperlink), lakukan
```
[Judul link](link)
```
Contoh:  
```
[youtube](https://www.youtube.com/)
```
Output:  
[youtube](https://www.youtube.com/)

---
## 9. Insert Image
Untuk menambahkan sebuah foto lakukan  
```
![alt text](image_file_path "title")
```
`alt text` (alternative text) adalah teks yang akan muncul jika gambar tidak dapat ditampilkan. `image_file_path` adalah path atau URL dari foto. `"title"` adalah judul dari gambar yang akan muncul ketika kursor berada di gambar. Selain itu juga dapat dituliskan dalam format HTML
```
<p><img src="URL"/></p>
```
Contoh:  
```
<p align="center">
  <img src="https://m.media-amazon.com/images/I/61X0g6GveJL._SL1500_.jpg" style="display: block; margin: auto;" width="200"/>
</p>
```
Output:  
<p align="center">
  <img src="https://m.media-amazon.com/images/I/61X0g6GveJL._SL1500_.jpg" style="display: block; margin: auto;" width="200"/>
</p>

---
## 10. Table
Untuk membuat tabel, lakukan
```
|Header 1|Header 2|Header 3|
|----|----|----|
|A|B|C|
|D|E|F|
|G|H|I|
```
Output:  

|Header 1|Header 2|Header 3|
|----|----|----|
|A|B|C|
|D|E|F|
|G|H|I|

---
## 11. Equation
Untuk membuat suatu persamaan dapat dituliskan dalam format Latex. Contohnya
```
$i\hbar\frac{\partial}{\partial t}\psi(r,t)=\left [ \frac{-\hbar^2}{2m}\nabla^2+V(r,t) \right ]\psi(r,t)$
```
Output:  

$i\hbar\frac{\partial}{\partial t}\psi(r,t)=\left [ \frac{-\hbar^2}{2m}\nabla^2+V(r,t) \right ]\psi(r,t)$