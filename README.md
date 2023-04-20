# Markdown Tutorial 

<p align="center">
  <img src="https://www.nicepng.com/png/detail/187-1870373_44191585-markdown-logo.png" style="display: block; margin: auto;" width="200"/>
</p>

**MARKDOWN** is a text writing format used for writing documents that can be easily converted into other formats such as HTML, PDF, or *Rich Text Format* (RTF). It is designed to make it easier for authors to create documents in a simple, intuitive, and readable way. Markdown is also used in README files to provide information about a *repository*, provide code explanations on Jupyter Notebook and so on. The following will explain some of the things that can be done in markdown files.

<hr>

## **1. Heading**
Heading is used to create *sections* or chapters that serve to separate content from one another. Heading is created with the prefix **'#'**. There are 6 levels in the heading where the more **'#'** the smaller the heading size will be.

```
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```
or can also be written in HTML as follows
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

In VS Code, the use of this heading level will be seen in the outline section. Usually, heading 1 is for the title, heading 2 for the chapter, heading 3 for the subchapter and so on so that the use of this heading makes the document more structured.
<hr>

## **2. Font Style**
There are several font styles that can be used such as **bold**, *italic*, ***bold and italic*** and ~~strikethrough~~.

1. **Bold**  
   To make the text bold, add two asterisks (**) or two underscores (__) at the beginning and end of the text to be bolded
   ```
   **This is bold text**
   __This is bold text__
   ```  
   Alternatively, in VS Code, block the text to be bolded and press `ctrl+B`.

   Output:  
   **This is bold text**
  
2. *Italic*  
   To italicize text, add an asterisk (*) or underscore (_) at the beginning and end of the text to be italicized.
   ```
   *This is italic text*
   _This is italic text_
   ```
   Alternatively, in VS Code, block the text to be italicized and press `ctrl+I`.

   Output:  
   *This is italic text*  

   
3. ***Bold and italic***  
      To make the text bold and italic, do the same method as point 1 and 2 above in the order of *italic* first then **bold**.
   ```
   ***This is bold & italic text***
   ___This is bold & italic text___
   ```
   Output:  
   ***This is bold & italic text***

4. ~~Strikethrough~~  
    Strikethrough is used to strikethrough a text. To strikethrough, add two tildes (~) at the beginning and end of the text
   ```
   ~~This is strikethrough text~~
   ```
   Output:  
   ~~This is strikethrough text~~

---
## **3. Text Alignment**
To make text aligned left, center, right and justify, you can use HTML formatting.  
1. Left Align   
   To make the text left aligned, you can use
   ```
   <p align="left">This text is aligned to the left.</p>
   ```
   Output:  
    <p align="left">This text is aligned to the left.</p>

2. Center Align  
   To make text center-aligned you can use
   ```
   <p align="center">This text is centered.</p>
   ```
   Output:
   <p align="center">This text is centered.</p>

3. Right align  
   To make text right-aligned you can use
   ```
   <p align="right">This text is aligned to the right.</p>
   ```
   Output:  
   <p align="right">This text is aligned to the right.</p>

4. Justify  
   To make text left-right aligned you can use
   ```
   <p align="justify">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum ultrices, turpis ac tristique ultricies, quam sapien sagittis sapien, nec bibendum enim libero non diam. Nam elementum velit nec felis finibus vehicula.
   ```
   Output:
   <p align="justify">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum ultrices, turpis ac tristique ultricies, quam sapien sagittis sapien, nec bibendum enim libero non diam. Nam elementum velit nec felis finibus vehicula.</p>

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