# Merge Sort / Birle�tirmeli S�ralama

Par�ala ve Fethet(Divide & Conquer) algoritmas�d�r. S�ralanacak olan veriler dizinin ortas�ndan itibaren ikiye b�l�nerek, tek bir eleman kalana kadar ayr��t�r�l�r.

```
Dizimiz => {38,27,43,3,9,82,10} 

- 1.ad�m  => {38,27,43,3} - {9,82,10}

 - 2.ad�m  => {38,27} - {43,3} - {9,82} - {10}
 
  - 3.ad�m  => {38} - {27} - {43} - {3} - {9} - {82} - {10}
  
   - 4.ad�m  =>  {27,38} - {3,43} - {9,82} - {10}
   
    - 5.ad�m  => {3,27,38,43} - {9,10,82}
    
     - 6.ad�m  => {3,9,10,27,38,43,82}
```

-> Yukar�da verilen �rne�i �imdi inceleyelim. �lk olarak yap�lan �ey dizi boyutunu 2'ye b�lerek(7/2=3.5 ~= 4) b�l�necek yeri buluyoruz.Sonras�nda ortaya ��kan 2 diziyide tekrar 2 ye b�lerek bu �rnek i�in 4 adet dizi olu�mu� oldu. Bu ad�mlar her bir eleman ayr� bir dizi olu�ana kadar(bknz:**3.ad�m**) devam eder.

-> Sonras�nda ***birle�tirme*** a�amas�na ge�ilir.4.ad�mda g�r�lece�i �zere ilk 2 eleman� kar��la�t�r�r ve s�ralar. Sonras�nda di�er iki eleman� kar��la�t�r�r ve kendi i�inde s�ralar. Bu �ekilde s�ralay�p par�alad�klar�n� tek tek birle�tirecek. Her biri tek elemanken **2.ad�m** daki halini geri alacak ancak fark� __s�ralanm��__ olmas� olacak. Sonras�nda **5.ad�m** 'da ise 1.ad�mdaki halini alacak ancak yine fark� **s�ralanm��** olmas� olacak. __6.ad�m__'da ise t�m listeyi s�ralam�� bir �ekilde olu�turmu� olacak.

**--> Dipnot** : 4.ad�m'da ba�layan s�ralama i�lemlerinde ilk iki dizinin ilk �nce ilk elemanlar�na bak�yor sonras�nda ona g�re birle�tirme yap�yor b�y�kl�k k���kl�k ile yerle�tirme yap�yoruz bir nevi.


    Yukar�da verilen �rne�imizin diyagram�n�da inceleyebilirsiniz

[![](http://www.farukgenc.com/Sorting-Animation/Merge-Sort-Algoritmasi-Diagram.png)](http://www.farukgenc.com/Sorting-Animation/Merge-Sort-Algoritmasi-Diagram.png)

##### Daha iyi anlamak ad�na �u animasyonu izleyebilirsiniz.

[![](http://www.farukgenc.com/Sorting-Animation/Merge-Sort-Animasyon.gif)](http://www.farukgenc.com/Sorting-Animation/Merge-Sort-Animasyon.gif)