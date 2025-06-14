# Бодлого 38


> HackerRank - Data Structures 
> Difficulty: Hard   

Тоон Цувааны Медиан Олох
Бүхэл тоонуудын багцын медиан нь өгөгдлийн багцын дундаж утга бөгөөд түүнээс бага болон их ижил тооны бүхэл тоо байдаг. Медианыг олохын тулд, та эхлээд бүхэл тоонуудын багцаа өсөх эрэмбээр ангилж, дараа нь:

Хэрэв таны багц сондгой тооны элементүүд агуулж байвал, медиан нь ангилагдсан дээжийн дундах элемент юм. Жишээ нь, эрэмбэлсэн багц [1,2,3,4,5] -д 3 нь медиан юм.
Хэрэв таны багц тэгш тооны элементүүд агуулж байвал, медиан нь ангилагдсан дээжийн дундах хоёр элементийн дундаж юм. Жишээ нь, эрэмбэлсэн багц [1,2,3,4,5,6] -д (3+4)/2=3.5 нь медиан юм.
Даалгавар:
N бүхэл тооны оролтын цуваа өгөгдсөн үед, i бүхэл тоо тус бүрт дараах үйлдлийг гүйцэтгэнэ:

i дэх бүхэл тоог одоогийн жагсаалтад нэмнэ.
Шинэчлэгдсэн жагсаалтын медианыг олно (ө.х., эхний элементээс i дэх элемент хүртэл).
Шинэчлэгдсэн медианыг шинэ мөрөнд хэвлэнэ. Хэвлэгдсэн утга нь давхар нарийвчлалтай тоо (double-precision number) байх бөгөөд нэг аравтын оронтой (жишээ нь, X.X формат) байна.
Жишээ:

Sorted (Эрэмбэлэгдсэн)	Median (Медиан)
[7]	7.0
[3,7]	5.0
[3,5,7]	5.0
[2,3,5,7]	4.0

Экспортировать в Таблицы
Медиан утга бүрийг массив дотор хадгалж, тэр массивыг үндсэн функцэд буцаана.

Тэмдэглэл: Хэвлэх мэдэгдэлд форматчиллыг нэмнэ үү.

Функцийн Тодорхойлолт
Засварлагч дахь runningMedian функцийг гүйцэтгэнэ үү.

runningMedian нь дараах параметрүүдтэй:

int a[n]: Бүхэл тоонуудын массив.
Буцаах утга:

float[n]: Оролт бүрийн дараа массивын медиан. Үндсэн функцэд зөв форматтай хэвлэхийн тулд хэвлэх мэдэгдлийг өөрчилнө үү.
Оролтын Формат
Эхний мөрөнд нэг бүхэл тоо N байна, энэ нь өгөгдлийн цуваан дахь бүхэл тоонуудын тоо юм.
Дараагийн N мөр тус бүр нь нэг бүхэл тоо val-ийг агуулна.

Хязгаарлалт:

1≤N≤10**5
 
0≤val≤10**5
 
Жишээ Оролт
6
12
4
5
3
8
7
Оролтын тайлбар:

N=6, a массив нь [12,4,5,3,8,7]
Жишээ Гаралт
12.0
8.0
5.0
4.5
5.0
6.0
![alt text](<Screenshot 2025-06-10 164047.png>)


<p align="center">
  <img src="../image/bodlogo1.png" alt="Bodlogo22" width="100%"/>
</p>

