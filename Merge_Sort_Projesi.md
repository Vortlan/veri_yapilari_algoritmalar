### Proje 2

## [16,21,11,8,12,22] -> Merge Sort

# Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

- Diziyi 2 ye böl
  - [16,21,11] ve [8,12,22]
- Oluşan dizileri tek veri kalana kadar 2'ye bölmeye devam et
  - İlk dizideki veriler [16,21] ve [11] olur
  - İkinci dizideki veriler [8,12] ve [22] olur
  - Tek veri kalana kadar devam edeceğimizden
  - İlk dizideki veriler [16], [21] ve [11] olur
  - İkinci dizideki veriler [8], [12] ve [22] olur
- Bölme islemi bittiğinde verileri karşılaştırıp kücükten büyüğe sıralacağız
- İlk dizideki verilerden [11,16,21] dizisi gelir
- İkinci dizideki verilerden [8,12,22] dizisi gelir
- Her iki dizide sıralı geldiği için en kücük veriler karsılastrılmaya baslanır.
- ilk dizi ile ikinci dizideki 1. sıradaki veriler karsılaştırılır.
- Kücük olan değeri ilk sıraya yazılır.
- Hangi dizedeki veri yazıdıysa onun index değerini 1 artırıp karşılastırma işlemi bitene kadar devam eder.

- [8,11,12,16,21,22] dizisi elde edilir.

# Big-O gösterimini yazınız.

- O(n log<sub>n</sub>)
