# Selection Sort

- [22,27,16,2,18,6]  Dizisinin Sort Aşamaları 
---
    1. Aşama = [2,27,16,22,18,6] (n)
    2. Aşama = [2,6,16,22,18,27] (n-1)
    3. Aşama = [2,6,16,18,22,27] (n-2)

- Big-O gösterimi

```
n.(n-1)+(n-2)....+(1) = n^2+n/2
O(n^2)
````

- Time Complexity
---

| Avarege Case | Worst Case | Best Case |
|:---:|:---:|:---:|
|Listenin karışık olması|Listenin tersten sıralı olması|Listenin sıralı olması|
| O(n^2)	| O(n^2) |	O(n^2) |
---

## [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımı
    - [2,3,5,8,7,9,4,15,6]
    - [2,3,5,8,7,9,4,15,6]
    - [2,3,4,8,7,9,5,15,6]
    - [2,3,4,5,7,9,8,15,6]


	