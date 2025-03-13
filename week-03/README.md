# Pertemuan 03 - Representasi Teks dalam VSM: TF-IDF, N-Gram, dan Word Embedding

## Apa itu VSM?
Dikutip dari [towardsdatascience.com](https://towardsdatascience.com/vector-space-models-48b42a15d86d/), VSM (Vector Space Model) adalah sebuah metode yang umum digunakan untuk merepresentasikan teks sebagai sebuah vektor berupa angka. Karena tidak seperti manusia yang mampu memahami bahasa secara alami, komputer hanya bisa memahami angka. Dengan memanfaatkan VSM, komputer bisa mengenali apakah sebuah teks yang berbeda memiliki makna yang sama, maupun sebaliknya. Agar lebih jelas, perhatikan contoh berikut

![contoh1](https://towardsdatascience.com/wp-content/uploads/2020/10/1du39S6mHqlOs9GP8gBkHDw.png)

Kedua kalimat di sebelah kiri memiliki 3 kata yang sama: "Where", "are", dan "you". Tetapi kata selanjutnya yang akan membuat makna keseluruhan kalimat berubah, menjadi "Dari mana kamu?" dan "Ke mana kamu pergi?"

Sedangkan pada 2 kalimat di sebelah kanan, seluruh kata pada kedua kalimat tidak ada yang sama. Tetapi makna keduanya sama, yang intinya menanyakan "Berapa umurmu?"

