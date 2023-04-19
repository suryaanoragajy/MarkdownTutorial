# Tutorial Markdown

<p align="center">
  <img src="https://www.nicepng.com/png/detail/187-1870373_44191585-markdown-logo.png" style="display: block; margin: auto;" width="200"/>
</p>

**MARKDOWN** adalah format penulisan teks yang digunakan untuk menulis dokumen yang dapat dengan mudah diubah menjadi format lain seperti HTML, PDF, atau *Rich Text Format* (RTF). Format ini dirancang untuk memudahkan penulis dalam membuat dokumen dengan cara yang sederhana, intuitif, dan mudah dibaca. Markdown juga digunakan dalam file README untuk memberikan informasi tentang suatu *repository*, memberikan penjelasan code pada Jupyter Notebook dan lain sebagainya. Berikut ini akan dijelaskan mengenai beberapa hal yang dapat dilakukan pada file markdown.
<hr>

## **Heading**
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

## **Font Style**
Terdapat beberapa font style yang dapat digunakan seperti **bold**, *italic*, ***bold dan italic***, `monospace`, dan ~~strikethrough~~.

1. **Bold**  
   Untuk membuat tulisan menjadi bold, tambahkan dua asterisk (**) atau dua underscore(__) di awal dan akhir tulisan yang akan di-bold
   ```
   **Tulisan ini di-bold**
   __Tulisan ini di-bold__
   ```  
   Cara lain, di VS Code, blok tulisan yang akan di-bold kemudian tekan `ctrl+B`

   Output:  
   **Tulisan ini di-bold**
  
2. *Italic*  
   Untuk membuat tulisan menjadi *italic*, tambahkan satu asterisk (*) atau satu underscore (_) di awal dan akhir tulisan yang akan di-italic
   ```
   *Tulisan ini di-italic*
   _Tulisan ini di-italic_
   ```
   Cara lain, di VS Code, blok tulisan yang akan di-italic kemudian tekan `ctrl+I`

   Output:  
   *Tulisan ini di-italic*  

   
3. ***Bold dan italic***  
      Untuk membuat tulisan menjadi ***bold dan italic***, lakukan cara yang sama seperti poin 1 dan 2 di atas dengan urutan *italic* terlebih dahulu kemudian **bold**.
   ```
   ***Tulisan ini di-italic***
   ___Tulisan ini di-italic___
   ```
   Output:  
   ***Tulisan ini di-bold dan italic***

4. `Monospace`
5. ~~Strikethrough~~