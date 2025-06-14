# Бодлого 30

> HackerRank - Data Structures 
> Difficulty: Medium  


Энгийн текст засварлагчийг хэрэгжүүл. Засварлагч нь эхэндээ хоосон мөр S-ийг агуулна. Дараах 4 төрлийн Q үйлдлийг гүйцэтгэнэ:

1 W: append - W мөрийг S-ийн төгсгөлд нэмнэ.
2 k: delete - S-ийн сүүлийн k тэмдэгтийг устгана.
3 k: print - S-ийн k-р тэмдэгтийг хэвлэнэ.
4: undo - Сүүлийн (өмнө нь буцаагаагүй) төрөл 1 эсвэл 2 үйлдлийг буцаана, S-ийг тухайн үйлдлийн өмнөх төлөвт нь буцаана.
Жишээ

index	S	ops[index]	тайлбар
0		1 abcde	"abcde" мөрийг нэмнэ
1	abcde	1 fg	"fg" мөрийг нэмнэ
2	abcdefg	3 6	6 дахь үсгийг хэвлэнэ - f
3	abcdefg	2 5	сүүлийн 5 үсгийг устгана
4	ab	4	сүүлийн үйлдлийг буцаана (индекс 3)
5	abcdefg	3 7	7 дахь тэмдэгтийг хэвлэнэ - g
6	abcdefg	4	сүүлийн үйлдлийг буцаана (индекс 1)
7	abcde	3 4	4 дэх тэмдэгтийг хэвлэнэ - d

Экспортировать в Таблицы
Үр дүнг дараах байдлаар хэвлэх ёстой:

f
g
d
Оролтын формат

Эхний мөрөнд Q (үйлдлийн тоо) гэсэн бүхэл тоо байна.
Дараагийн Q мөр тус бүр (энд 0≤i<Q) гүйцэтгэх үйлдлийг тодорхойлно. Үйлдэл бүр нь T (энд 1≤T≤4) гэсэн ганц бүхэл тоогоор эхэлдэг бөгөөд энэ нь дээрх Асуудлын тайлбарт заасан үйлдлийн төрлийг илэрхийлнэ. Хэрэв үйлдлийн аргумент шаардлагатай бол T-ийн дараа зайгаар тусгаарлагдсан аргумент байна. Жишээлбэл, хэрэв T=1 ба W=abcd бол i-р мөр нь 1 abcd байна.

Хязгаарлалт

1≤Q≤10**5
 
1≤k≤∣S∣
Оролтын бүх W-ийн уртын нийлбэр 10**6
 -аас ихгүй байна.
Бүх устгах үйлдлийн k-ийн нийлбэр 10**6
 -аас ихгүй байна.
Бүх оролтын тэмдэгтүүд нь жижиг англи үсгүүд байна.
Оролтоор өгөгдсөн үйлдлүүдийн дараалал гүйцэтгэх боломжтой нь баталгаатай.

Гаралтын формат

Төрөл 3 үйлдэл бүр нь k-р тэмдэгтийг шинэ мөрөнд хэвлэх ёстой.

Жишээ оролт

STDIN   Функц
-----   --------
8       Q = 8
1 abc   ops[0] = '1 abc'
3 3     ops[1] = '3 3'
2 3     ...
1 xy
3 2
4
4
3 1
Жишээ гаралт

c
y
a
Тайлбар

Эхэндээ S хоосон байна. Дараах Q үйлдлийн дараалал доор тайлбарлагдсан байна:

1 abc. Бид abc-г S-д нэмнэ, ингэснээр S=abc.
3 3. Шинэ мөрөнд 3 дахь тэмдэгтийг хэвлэнэ. Одоогийн байдлаар 3 дахь тэмдэгт нь c.
2 3. S-ийн сүүлийн 3 тэмдэгтийг устгана (abc), ингэснээр S="".
1 xy. xy-г S-д нэмнэ, ингэснээр S=xy.
3 2. Шинэ мөрөнд 2 дахь тэмдэгтийг хэвлэнэ. Одоогийн байдлаар 2 дахь тэмдэгт нь y.
4. S-д хийсэн сүүлийн өөрчлөлтийг буцаана, S-ийг дахин хоосон болгоно (өөрөөр хэлбэл S="").
4. S-д хийсэн сүүлийн өөрчлөлтийг буцаана (сүүлийн 3 тэмдэгтийг устгасан үйлдлийг), ингэснээр S=abc.
3 1. Шинэ мөрөнд 1 дэх тэмдэгтийг хэвлэнэ. Одоогийн байдлаар 1 дэх тэмдэгт нь a.
![alt text](<Screenshot 2025-06-10 143902.png>)

<p align="center">
  <img src="../image/bodlogo1.png" alt="Bodlogo22" width="100%"/>
</p>