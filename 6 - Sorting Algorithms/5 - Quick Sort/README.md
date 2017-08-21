# Quick Sort / H�zl� S�ralama

-> Dizinin ilk indisi pivot olarak se�ilir.(Rastgele de se�ilebilir.) Sonras�nda 2.eleman **sol**, dizimizin en sonundaki eleman ise **sa�** de�i�keniyle tutulur. Sonra pivot de�erimiz sol-sa� de�i�kenleri ile kar��la�t�r�l�r. E�er soldaki tutulan eleman pivot de�erimizden **k���k** ise ve sa� de�i�keninde tutulan say� pivottan **b�y�k** ise de�i�tirme i�lemi uygulan�r. Ve Ard�ndan **sol** 1 ad�m sa�a, **sa�** bir ad�m sol'a kayd�r�larak tekrar kar��la�t�rmaya devam edilir. E�er ki �art sa�lanmaz ise(sa� tutulan eleman i�i bozdu mesela) sa�'� bir ad�m sola kayd�rarak devam ediyoruz.

-> Olay�n sonunda elimizde ilk ba�ta se�ti�imiz(pivot) de�erimizden k���kler solda b�y�kler sa�da s�ralanm�� bir yap� olu�uyor. Bizde pivot de�erimizi bu 2 listenin aras�na(ortas�na) koyuyoruz. Ayn� i�lemler olu�an sol dizi ve sa� dizi i�in tekrarlan�yor.


-> A�a��daki diyagramda pivot **ortadaki** eleman se�ilmi� ve i **sa�** de�i�keni j ise **sol** de�i�kenini temsil ediyor :) 
[![](http://www.farukgenc.com/Sorting-Animation/quick-sort.png)](http://www.farukgenc.com/Sorting-Animation/quick-sort.png)


##### Daha iyi anlamak ad�na �u animasyonu izleyebilirsiniz.

[![](http://www.farukgenc.com/Sorting-Animation/Quicksort-Animasyon.gif)](http://www.farukgenc.com/Sorting-Animation/Quicksort-Animasyon.gif)