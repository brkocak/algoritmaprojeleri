# Proje 1 - Insertion Short

**[22,27,16,2,18,6]**

## Sorular

## Soru 1: 
Yukarı verilen dizinin insertion sort türüne göre aşamalarını yazınız.

**Cevap:**
1. Adım: [2|27,16,22,18,6]
2. Adım: [2,6|16,22,18,27]
3. Adım: [2,6,16|22,18,27]
4. Adım: [2,6,16,18,22,27]

## Soru 2:
Big-O gösterimini yazınız.

**Cevap:**
Big-0 gösterimi, algoritmanın en kötü durumdaki çalışma süresini ifade eder. Dolayısıyla Insertion short için worst-case bir önceki sorunun cevabının tam tersi sıralı bir dizi olur.

Burada yüm eleman sayılarına n dersek ilk sıralama da n'den başlayarak tüm sıralamalar -1 azalacak ve n + (n-1) + (n-2)... kadar işlem yapılacağından n.(n+1)/2 şeklinde hesaplanır.

Big-O gösterimi için en yüksek dereceli terimi göstermek lazım. Bu nedenle formülden (n^2) geldiği için gösteirmi O(n^2) olur.

## Soru 3:

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer?

**Cevap:**
Sayılar sıralandıktan sonra 18 sayısı dizinin ortasındaki eleman olacağı için cevap "Avarage case"tir.

## Soru 4:

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

**Cevap:**
Selection sort, bir dizi içerisindeki elemanları küçükten büyüğe doğru sıralayan bir algoritmadır. En küçük elemanı bulur ve sıralanmış bölümün sonuna yerleştirir.

Dizi: **[7,3,5,8,2,9,4,15,6]**

1. Adım: Dizideki en küçük sayıyı bulur ve bataki sayı ile yer değiştirir.

    **[2|3,5,8,7,9,4,15,6]**

2. Adım: Kalan sayılar arasından en küçük eleman bulunur ve baştakiyle yer değiştirir.

    **[2,3|5,8,7,9,4,15,6]**

3. Adım: **[2,3,4|8,7,9,5,15,6]**

4. Adım **[2,3,4,5|7,9,8,15,6]**

İlk dört adım bu şekildedir. Dizinin son hâli ise aşağıdaki gibidir:

**[2,3,4,5,6,7,8,9,15]**