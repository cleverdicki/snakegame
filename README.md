# SNAKE GAME

Game ini hampir sama dengan snake game pada umumnya, dimana gameplay nya adalah ada seekor ular yang memakan sebuah objek, kemudian setelah objek tersebut dimakan, maka panjang ular akan bertambah. Pada game ini, objek yang dimakan adalah sebuah aple merah biasa, dan ada golden apple untuk power up (Bersifat sementara). Game ini dibagi dalam 2 mode:

1. Normal Mode, dimana dalam mode ini player diharuskan untuk mendapatkan score setinggi mungkin, dengan adanya tantangan health serta obstacle. Setiap pergerakan snake akan mengurangi snake health. Setiap snake memakan buah apple merah biasa atau golden apple akan menambah snake health, dan memberikan score dengan nilai yang berbeda pula. Terdapat obstacle yang akan dirandom lokasinya setiap kali memakan buah.

2. Time Attack Mode, dimana dalam mode ini player diharuskan untuk mendapatkan score maksimal dengan waktu secepat mungkin. Dengan kata lain, dalam mode ini player ditantang untuk mencari jalan seefektif mungkin dalam mendapatkan score. Obstacle pada mode ini sudah ada secara default, dengan kata lain dalam mode ini sudah ada map yang dimana obstaclenya bersifat statis.

Setiap mode dalam game ini terdapat obstacle dan masing-masing memiliki objek yang dimakan snake berupa red apple dan golden apple. Jika snake memakan golden apple, maka kecepatan snake akan bertambah. Jika kemudian snake memakan red apple kembali, kecepatannya akan kembali normal. Dalam game ini, sama halnya dengan snake game pada umumnya, jika snake bertabrakan dengan obstacle, maka snake akan mati dan game over.

### Tampilan Menu
![Menu](https://user-images.githubusercontent.com/48941105/70649880-989c6780-1c80-11ea-9425-61868411972e.png)

Pada game ini, tampilan awal ketika  program dijalankan adalah tampilan menu. Pada tampilan menu akan ditampilkan tiga pilihan, yaitu:

1. ```START```, adalah normal mode dari game ini.

2. ```TIME ATTACK```, adalah time attack mode dari game ini.

3. ```HIGHSCORE```, adalah list highscore yang pernah diraih dalam game ini.


### Normal Mode
![In Game - Normal Mode](https://user-images.githubusercontent.com/48941105/70650372-8bcc4380-1c81-11ea-9775-d497da4a1b36.png)

Ketika player memilih ```START```, maka player akan dibawa kedalam in game dari normal mode game ini. Seperti yang sudah dijelaskan sebelumnya, dalam mode normal terdapat score sebagai penghitung score yang diraih didalam game, Healthbar sebagai snake health, dan snake serta red apple sebagai inisialisasi game. Setiap pergerakan snake akan mengurangi snake healthbar.

![In Game - Normal Mode obs](https://user-images.githubusercontent.com/48941105/70650824-5e33ca00-1c82-11ea-8461-d0e4cdaaf8ec.png)

Ketika snake memakan red apple, snake healthbar akan bertambah dan score juga akan bertambah. red apple bernilai 1 score dan golden apple bernilai 10 score. Jika memakan golden apple, maka kecepatan snake akan bertambah cepat. Jika memakan red apple setelah sebelumnya memakan golden apple, maka kecepatan snake akan kembali normal. Setelah memakan red apple pertama, maka akan muncul obstacle dengan posisi random. Setiap snake memakan apple, lokasi obstacle akan dirandom. 

![Game Over - Normal Mode](https://user-images.githubusercontent.com/48941105/70651316-25482500-1c83-11ea-83a4-0779a6606b26.png)

Ketika snake menabrak obstacle ataupun snake menabrak dirinya sendiri, game berakhir. Maka akan ditampilkan nilai score yang didapatkan ketika bermain, bersamaan dengan ditampilkannya nilai highscore yang pernah diraih player lainnya. Jika ingin bermain dari lagi, tekan ```SPACEBAR``` pada keyboard untuk memulai game lagi.


### Time Attack Mode
![In Game - Time Attack mode](https://user-images.githubusercontent.com/48941105/70651584-ad2e2f00-1c83-11ea-9c1d-11b190d46795.png)

Ketika player memilih ```TIME ATTACK```, maka player akan dibawa kedalam in game dari time attack mode game ini. Terdapat score sebagai penghitung score yang diraih dalam game, time sebagai penghitung waktu yang sudah dilalui player, snake, serta red apple dan obstacle default sebagai inisialisasi game. Pada mode ini, obstacle tidak akan berpindah posisi. Posisinya akan tetap (Statis). Pada mode ini, player dituntut untuk mendapatkan score tinggi dengan waktu yang cepat. Jika memakan red apple, score akan bertambah 1 score, dan jika memakan golden apple akan menambah score 2 score dan akan mempercepat movement snake. Sama seperti Normal Mode, jika memakan red apple setelah sebelumnya memakan golden apple, maka movement snake akan kembali normal.

![Game Over - Time Attack Mode](https://user-images.githubusercontent.com/48941105/70652022-7ad10180-1c84-11ea-913a-b1a6137f5322.png)

Ketika snake menabrak obstacle ataupun snake menabrak dirinya sendiri, game berakhir. Maka akan ditampilkan nilai score yang didapatkan ketika bermain dan catatan waktu yang didapat, bersamaan dengan ditampilkannya nilai highscore yang pernah diraih player lainnya. Jika ingin bermain dari lagi, tekan ```SPACEBAR``` pada keyboard untuk memulai game lagi.


### High Score
![High Score - Normal Mode](https://user-images.githubusercontent.com/48941105/70652162-b5d33500-1c84-11ea-9663-82fa7378a90e.png)

Ketika player memilih ```HIGHSCORE``` pada tampilan awal menu, maka akan ditampilkan list high score dari player-player lainnya yang pernah memainkan game ini. Ada dua list high score, yaitu normal mode high score dan time attack mode high score

![High Score - Time Attack Mode](https://user-images.githubusercontent.com/48941105/70652171-b8358f00-1c84-11ea-917e-8aec3f88e8ed.png)
