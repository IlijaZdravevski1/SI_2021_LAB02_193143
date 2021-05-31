ВТОРА ЛАБАРАТОРИСКА ВЕЖБА ПО СОФТВЕРСКО ИНЖЕНЕРСТВО

Илија Здравевски, Број на индекс:193143

Control Flow Graph
![LAB2](https://user-images.githubusercontent.com/82412147/120199778-e49bed00-c223-11eb-9f6c-1619132c6add.png)

1. Цикломатска комплексност:<br>
Цикломтската комплексност на дадениот код е 9 и таа е добиена со Цикломатската комплексност може да ја одкриеме преку бројот на региони или број на предикатни јазли. предикатни јазли во нашиот код се:D; I; E; J; L; D; W; Y. во нашиот случај бројот на предикатни јазли е 8, Р=8+1=9.

2.Тест случаи според критериумот Every statement:
Оваа метода налага да се генерираат test case-ови кои ќе овозможат
тестирање на секоја наредба односно секој statement од кодот.
A  read hr,min,sec<br>               
B  type=''scalene''<br>
C  if (hr < 0 || hr > 24)<br>
D  type=''throw new RuntimeException("The hours are grater than E  the maximum")''<br>
F  if (min < 0 || min > 59)<br>
G  type=''throw new RuntimeException("The minutes are not H  valid!''<br>
I  if (sec >= 0 && sec <= 59)<br>
J  type='' result.add(hr * 3600 + min * 60 + sec)''<br>
ТЕСТ ПРИМЕРИ<br>
1. 1,10,0
2. 2,20,1
3. 3hr,30min,2sec
4. 4hr,40min,3sec
5. 5hr,41min,4sec
6. 6hr,42min,5sec
7. 7hr,43min,6sec
8. 8hr,44min,7sec
9. 9hr,45min,8sec
10. 10hr,46min,9sec
11. 11hr,47min,10sec
12. 12hr,48min,11sec
13. 13hr,49min,12sec
14. 14hr,50min,13sec
15. 15hr,51min,14sec
16. 16hr,52min,15sec
17. 17hr,53min,20sec
18. 18hr,54min,30sec
19. 19hr,55min,40sec
20. 20hr,56min,50sec
21. 21hr,57min,55sec
22. 22hr,31min,58sec
23. 23hr,58min,59sec

4.Тест случаи според критериумот Every path:<br>
претставува единствена секвенца од програмски јазли кои
се извршуваат од даден test case.
1,10,0<br>
2,20,1<br>
3hr,30min,2sec<br>
4hr,40min,3sec<br>
5hr,41min,4sec<br>
6hr,42min,5sec<br>
7hr,43min,6sec<br>
8hr,44min,7sec<br>
9hr,45min,8sec<br>
10hr,46min,9sec<br>
11hr,47min,10sec<br>
12hr,48min,11sec<br>
13hr,49min,12sec<br>
14hr,50min,13sec<br>
15hr,51min,14sec<br>
16hr,52min,15sec<br>
17hr,53min,20sec<br>
18hr,54min,30sec<br>
19hr,55min,40sec<br>
20hr,56min,50sec<br>
21hr,57min,55sec<br>
22hr,31min,58sec<br>
23hr,58min,59sec<br>







