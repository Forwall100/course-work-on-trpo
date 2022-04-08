# Клавиатурный тренажер
## Описание функционала
1) Пользователь может выбрать время тренировки
2) Пользователь вводит слова за выбраное время.
3) При ошибке в введенном слове, пользователь получает сообщение об ошибке.
4) Пользователь может изменять словарь, редактируя текстовый файл в папке с программой.

<hr>

## Описание основных блоков программы
Программа состоит из следующих элементов:
1) Словарь
2) Блок выбора времени 
3) Блок ввода слов (далее Тренировка)
4) Блок статистики

## 1 Словарь
Словарь представляет собой текстовый файл dictionary.txt в папке с программой. Файл состоит из набора слов, каждое слово на новой строке. В словарь можно добавлять новые слова или удалять существующие, слова из словаря выбираются случайно.

## 2 Блок выбора времени
<img src="https://i.imgur.com/aNvs65D.png" alt="images" width="700"/>
Блок выбора времени представляет собой поле ввода, куда пользователь вводит желаемое время тренировки в секундах.

## 3 Тренировка
<img src="https://i.imgur.com/qDgPLvS.png" alt="images" width="700"/>
Тренировка состоит из непрервыного набора слов, которые появляются на экране. Каждое слово состоит из строчных букв русского алфавита. На экран выводится необходимое слово, после его ввода необходимо нажать enter для его проверки. Таймер обновляется при каждом введенном слове.

## 4 Блок статистики
<img src="https://i.imgur.com/I5lcFoC.png" alt="images" width="700"/>
По истечению времени пользователь получает статистику по количеству успешно написанных слов, количеству ошибок, которые были допущены во время печати, среднему количеству слов в минуту. Статистика может быть импортирована в текстовый файл для сохранения или просто удалена при выходе из приложения.
