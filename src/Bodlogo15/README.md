# # Бодлого 15
Цион улс нь хоёр талт замуудаар холбогдсон хотуудтай. Аливаа хоёр хотын хооронд өвөрмөц зам байдаг. Морфейус машинууд бүх хаант улсыг устгах төлөвлөгөөтэй байгааг олж мэджээ. Хэрэв хоёр машин хүчээ нэгтгэж чадвал, тэд дайрна. Нео хүчээ нэгтгэхээс сэргийлэхийн тулд машинуудтай хотуудыг холбосон замуудыг устгах ёстой. Хоёр машиныг холбосон ямар ч зам үлдэх ёсгүй.

Зам бүрийг устгахад тодорхой хэмжээний хугацаа шаардагдах бөгөөд нэг удаад зөвхөн нэг замыг л устгах боломжтой. Замууд болон хугацааны жагсаалтыг өгөгдсөн тохиолдолд халдлагыг зогсооход шаардагдах хамгийн бага хугацааг тодорхойлно уу.

Жишээлбэл, 0-ээс 4 дугаартай n=5 хот байна. Тэдгээрийн гурав нь машинтай бөгөөд улаан өнгөтэй байна. Зам бүрийг устгахад шаардагдах хугацааг хажууд нь харуулсан байна. Хэрэв бид хоёр ногоон замыг огтолвол, ямар ч хоёр машины хооронд зам байхгүй болно.
Шаардагдах хугацаа нь 3+2=5.

Жак уралдааныг аль болох хурдан эхлүүлэхэд шаардагдах хугацааны квадратыг мэдэхийг хүсэж байна.

Функцийн тодорхойлолт:

Доорх засварлагчид minTime функцийг гүйцэтгэнэ үү. Энэ нь машинуудын хоорондох холболтыг таслахад шаардагдах хамгийн бага хугацааг илэрхийлэх бүхэл тоог буцаах ёстой.

minTime нь дараах параметртэй:

roads: бүхэл тоонуудын хоёр хэмжээст массив, roads[i]=[city1,city2,time] бөгөөд хотууд time хугацаагаар устгах замтай холбогдсон байна.
machines: машинуудтай хотуудыг илэрхийлэх бүхэл тоонуудын массив.
Оролтын формат:

Оролтын эхний мөр нь зайгаар тусгаарлагдсан хоёр бүхэл тоо, хотын тоо n, болон машинуудын тоо k-г агуулна.
Дараах n−1 мөр тус бүр нь зайгаар тусгаарлагдсан гурван бүхэл тоо city1, city2, болон time-г агуулна. city1 ба city2-г холбосон хоёр талт зам байх бөгөөд энэ замыг устгахад time нэгж хугацаа шаардагдана.
Сүүлийн k мөр тус бүр нь machine[i] бүхэл тоог агуулна, энэ нь машинтай хотын нэр юм.

Хязгаарлалт:

2≤n≤10 
5
 
2≤k≤n
1≤time[i]≤10 
6
 
Гаралтын формат:

Бүх машинуудын хоорондох холболтыг таслахад шаардагдах хамгийн бага хугацааг илэрхийлэх бүхэл тоог буцаана.

Жишээ оролт:

5 3
2 1 8
1 0 5
2 4 5
1 3 4
2
4
0
Жишээ гаралт:

10
Тайлбар:

Машинууд 0, 2, 4-р хотуудад байрладаг. Нео ногоон замуудыг устгаснаар 5+5=10 хугацаанд гүйцэтгэнэ. 1 ба 0-ийн оронд 2 ба 1-р хотуудын хоорондох замыг устгах нь ажиллах боловч хамгийн бага биш юм.

<p align="center">
  <img src="../image/bodlogo1.png" alt="Bodlogo15" width="100%"/>
</p>