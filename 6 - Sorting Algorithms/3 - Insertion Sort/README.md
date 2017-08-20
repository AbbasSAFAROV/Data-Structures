# Insertion Sort / Eklemeli S�ralama

Dizimizin 2.elam�ndan ba�layarak bir �nceki elemanlarla kar��la�t�rma yap�larak ilerler. E�er kar��la�t�rma yapt��� eleman daha b�y�kse **sa�a** do�ru kayd�r�l�r. Kendinide bir nevi araya eklemi� olur.

```
Dizimiz => {33,44,21,45,25,14}

- 1.ad�m  => {33 | 44 - 21 - 45 - 25 - 14}

 - 2.ad�m  => {33 - 44 | - 21 - 45 - 25 - 14}
 
  - 3.ad�m  => {21 - 33 - 44 | 45 - 25 - 14}
  
   - 4.ad�m  => {21 - 33 - 44 - 45 | 25 - 14}
   
    - 5.ad�m  => {21 - 25 - 33 - 44 - 45 | 14}
    
     - 6.ad�m  => {14 - 21 - 25 - 33 - 44 - 45 |}
```

-> Bu algoritmada ***5.ad�mdan -> 6.ad�ma*** ge�ilen k�s�ma dikkatle g�z at�l�rsa en sondaki eleman di�er verilerden k���k oldu�u i�in en ba�a getirelecek. Bu da t�m dizinin 1 birim sa�a kayd�rmam�za sebeb verecek. Insertion Sort'un olumsuz durumlar�ndan birisi.

Daha iyi anlamak ad�na �u animasyonu izleyebilirsiniz.

[![](http://www.farukgenc.com/Sorting-Animation/Insertion-Sort-Animation.gif)](http://www.farukgenc.com/Sorting-Animation/Insertion-Sort-Animation.gif)