API Data Wilayah Indonesia
==========================

Repository ini berisi source code untuk generate (REST) API statis berisi data wilayah Indonesia
serta perintah untuk mendeploynya ke _static hosting_ [Github Page](https://pages.github.com/).

Demo: [https://ftlgymdev.github.io/api-wilayah-indonesia/](https://ftlgymdev.github.io/api-wilayah-indonesia/)

## LIMITASI

Karena API ini dihosting di Github Page, Github Page sendiri memberikan batasan bandwith 100GB/bulan. Rata-rata endpoint disini memiliki ukuran 1KB/endpoint, jadi kurang lebih request yang dapat digunakan adalah 100.000.000 request per bulan, atau sekitar 3.000.000 request/hari.

Karena limitasi ini, disarankan untuk hosting API ini di github kamu sendiri.

Untuk lebih detail tentang limitasi Github Page, bisa dilihat [disini](https://help.github.com/en/articles/about-github-pages#usage-limits).
