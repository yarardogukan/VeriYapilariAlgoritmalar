# Insertion Sorting #1

## [Doğukan Yarar](https://app.patika.dev/iamdyarar)

> [22, 27, 16, 2, 18, 6] sembollerini araya ekleme yöntemine (Insertion Sort) göre tasarlayalım. 

`1. Adım `  [2, 27, 16, 22, 18, 6] <br>
`2. Adım `  [2, 6, 16, 22, 18, 27] <br>
`3. Adım `  [2, 6, 16, 18, 22, 27] <br>

> Insertion Sort'un Big-O gösterimini yazınız.

O (n^2)

>Time Comlexity
- Average case: Aradığımız sayının ortada olması,
- Worst case: Aradığımız sayının sonda olması, 
- Best case: Aradığımız sayının dizinin en başında olması.

> Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? yazınız.

`Sıralama `  [2, 6, 16, 18, 22, 27] <br>
18 sayısı ortada bulunduğundan <b>Average Case</b> kapsamına girer.

> [7, 3, 5, 8, 2, 9, 4, 15, 6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

`1. Adım `  [2, 3, 5, 8, 7, 9, 4, 15, 6] <br>
`2. Adım `  [2, 3, 4, 8, 7, 9, 5, 15, 6] <br>
`3. Adım `  [2, 3, 4, 5, 7, 9, 8, 15, 6] <br>
`4. Adım `  [2, 3, 4, 5, 6, 9, 8, 15, 7]

