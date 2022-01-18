# bioinformatics-data-skills

## A1.1. 
First of all, I called two libraries. *numpy and seaborn*.
The codes I used for this:     ```import numpy as np
                                  import seaborn as sns```
I created a numpy array of random integers. I set a size for it (100X100 matris). This index of integers ranges from [0, 100].
The code I use for this is:```array= np.random.randint(0,101, size=(100,100))```
I named this array I created "array". And I included 100. The code also passes 'int' to be integers.
To run the code I typed ```array``` and run the code.
There are dots in between because I chose a very long string of numbers. But I can see a few of them here. burada ki output için Final MBG6133- Şeyma YILDIZ-Copy1 dosyasına gidip out[4]'e bakabilirsiniz.

## A1.2.

Daha önce oluşturduğum array için bir headmap oluşturdum. bunu yaparken kullandığım kod: ```sns.heatmap(array)```.
Bu kodu çalıştırdığımda headmap üzerinde * < axessubplot :> * yazısı çıktı. bu yazıyı silmek için bir kod daha kullandım. kod: ```plt.show()```
oluşturduğum headmap'i "poster" kodu ile göstermek için bir kütüphane daha çağırmam gerekti. bunun için kullandığım kod: ```import matplotlib.pylab as plt```
bu kütüphaneyi çağırdıktan sonra poster haline getirmek için kullandığım kod: ```sns.set_context("poster")```. burada ki output için Final MBG6133- Şeyma YILDIZ-Copy1 dosyasına gidip In[5]'e bakabilirsiniz.

## A2.1. 

```array %2!=0``` kodu ile oluşturduğum dizideki sayılardan tek sayı olanları ayırmak istedim. buradaki kod ile dizideki sayılar 2'ye bölündüğünde sonuç 0 çıkanları alma demiş oldum. ! işareti olumsuzlamak için kullanılıyor. burada ki output için Final MBG6133- Şeyma YILDIZ-Copy1 dosyasına gidip Out[6]'e bakabilirsiniz. 
burada output True, False şeklinde çıktı. bunu [0,1] şeklinde değiştirmek istedim. bunun için kullandığım kod: ```new_array.astype(int)``` python da 0 yanlış anlamına geliyor. 1 de doğru anlamına geliyor. bu  kullandığım kod ile oluşturduğum diziye yeni bir isim verdim. new_array.  ```.astype(int)``` bu komut da array içinde ki vektörleri, matrisleri ve sütunları dönüştürmek için kullanılabilir. However, int() is a Python function that can only be applied to scalar values. burada ki output için Final MBG6133- Şeyma YILDIZ-Copy1 dosyasına gidip Out[9]'e bakabilirsiniz.


## A2.2. 

A1.2 de olduğu gibi burda da bir headmap oluşturdum. A2.1 de yeni bir array oluşturmuştum. ismi new_array. bunun için bir headmap oluşturdum. burada ```sns.headmap()``` komutunun içine daha önce kullandığım ```new_array.astype(int)``` kodunu kullandım. kod şu şekilde ```sns.heatmap(new_array.astype(int))``` oldu. Bu kodu çalıştırdığımda headmap üzerinde * < axessubplot :> * yazısı çıktı. bu yazıyı silmek için bir kod daha kullandım. kod: ```plt.show()``` oluşturduğum headmap'i "poster" kodu ile göstermek için daha önce kütüphane çağırmıştım. tekrar çağırmama gerek yok. yine burada poster haline getirdim. ```sns.set_context("poster")``` kodunu kullandım. burada ki output için Final MBG6133- Şeyma YILDIZ-Copy1 dosyasına gidip In[14]'e bakabilirsiniz.




