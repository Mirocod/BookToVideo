# Программа для преобразования электронных книг в видео

<img height="300" src="https://pulsdel.ru/KK_Mirocod/BookToVideo/raw/branch/master/img/Logo_White.png"/>

# Состав программы
* Библиотека работы с аргументами
* txt2mp3 - программа для озвучивания текста
* pdf2video - программа для преобразования книг в формате pdf в видео

# Пример работы программы

* Смещение картинки по времени
<iframe src="https://vk.com/video_ext.php?oid=-210998646&id=456239143" width="426" height="240" allow="autoplay; encrypted-media; fullscreen; picture-in-picture;" frameborder="0" allowfullscreen></iframe>

* Страница на весь экран
<iframe src="https://vk.com/video_ext.php?oid=-210998646&id=456239144" width="426" height="240" allow="autoplay; encrypted-media; fullscreen; picture-in-picture;" frameborder="0" allowfullscreen></iframe>

* Деление страницы пополам
<iframe src="https://vk.com/video_ext.php?oid=-210998646&id=456239145" width="426" height="240" allow="autoplay; encrypted-media; fullscreen; picture-in-picture;" frameborder="0" allowfullscreen></iframe>

# Примеры команд

* Озвучивание
    txt2mp3 -i in.txt -o out.mp3

* Преобразование в видео
    pdf2video -i in.pdf -o out.mp4

* Преобразование в видео cо смещением картинки по времени
    pdf2video -i in.pdf -o out.mp4 --split 'time'

* Помощь
    txt2mp3 -h
    pdf2video -h

* В папке test есть два теста.
