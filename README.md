## 1.2 Understanding how it works
![alt text](<Screenshot 2024-05-07 143610.png>)
String `Aya's computer: hey hey` berada diluar fungsi main, sehingga fungsi tersebut berjalan terpisah dari String `Aya's computer: howdy!` dan `Aya's computer: done!`.

## 1.3 Multiple spawn and removing drop
![alt text](<Screenshot 2024-05-07 204759.png>)
Banyaknya spawner yang ditambahkan menyebabkan lebih banyak task yang harus dilakukan. Spawner yang tidak di drop menyebabkan program tidak pernah mati. Hal ini karena program berasumsi bahwa masih akan ada data yang dikirim oleh spawner.