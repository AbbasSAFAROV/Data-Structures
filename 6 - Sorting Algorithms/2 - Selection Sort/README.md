# Selection Sort / Se�meli S�ralama

Dizimizdeki en k���k eleman bulunur ve ba�a al�n�r bu t�m listenin gezilmesi ile sa�lan�r. �lk indisten ba�lay�p dizinin sonuna kadar gidip, kar��la�t�rmalar yap�l�p daha k���k bir say� bulunduysa yer de�i�tirilip bu sefer d�ng�m�z bir sonraki indisten ba�lay�p devam etmelidir.(optimize)

```
Dizimiz => {5,7,2,9,6,1,3}

- 1.ad�m  => {1,7,2,9,6,5,3}

 - 2.ad�m  => {1,2,7,9,6,5,3}
 
  - 3.ad�m  => {1,2,3,9,6,5,7}
  
   - 4.ad�m  => {1,2,3,5,6,9,7}
   
    - 5.ad�m  => {1,2,3,5,6,7,9}
```

Dizimiz ilk indisten ba�lay�p t�m elemanlarla ilk indisteki eleman�m�z� kar��la�t�r�yoruz.Sonras�nda yer de�i�tirme(swap) i�lemi uygulan�r. E�er listedeki hi� bir eleman k���k de�ilse yer de�i�tirme i�lemi yap�lmaz.

Daha iyi anlamak ad�na �u animasyonu izleyebilirsiniz.

[![](http://www.farukgenc.com/Sorting-Animation/Selection-Sort-Animation.gif)](http://www.farukgenc.com/Sorting-Animation/Selection-Sort-Animation.gif)