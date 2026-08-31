# Endless-procedural-image-generation-on-Babylon.js

За основу взято -> https://playground.babylonjs.com/#HWG227#5

В первой версии я сделал гладкую версию создания всевозможных изображений без повторов всеми возможными способами.

[Endless colored mountain! | Babylon.js Playground](https://playground.babylonjs.com/#QZI176)

Бесконечно-процедурно генерируемых цветных RGB всевозможных картинок подиум вправо, и влево по оси X при движение камеры генерируются.

[The endless art gallery of the Backrooms (Makarov’s version 1 - A podium of various color images) | Babylon.js Playground](https://playground.babylonjs.com/#41F97U#1)

Теперь нужно добавить GUI для того что-бы создать локальную версию цветного шума для переключение по полю вводу картинки на плсокости.

[The endless art gallery of the Backrooms (Makarov’s version 2 - With an input field and one plane) | Babylon.js Playground](https://playground.babylonjs.com/#V05VE8)

Что и предыдущий код только с возможностью случайного переключение на случайные картинки в диапазоне от минимального до максимального значения введеного значение поля ввода.

[The endless art gallery of the Backrooms (Makarov’s version 3 - With an auto-switch button, and auto-switch ranges) | Babylon.js Playground](https://playground.babylonjs.com/#9BAK66)

Перестановка картинок по биективности.

[The endless art gallery (Makarov’s version 4 - With image loading and rearranging all pixels without repetition) | Babylon.js Playground](https://playground.babylonjs.com/#9YK2AG)

Перестановка картинок по биективности но с подгоном размера плоскости под размер картинки. 

[The endless art gallery (Makarov’s version 4 - With image loading and rearranging all pixels without repetition, and scaling the plane to fit the size of the image) | Babylon.js Playground](https://playground.babylonjs.com/#9YK2AG#1)

По пиксельно заменить последовательно все пиксели выбранной картинки на всевозможные случайные пиксели всевозможных цветов всеми всевозможными способами без повторов, и так же перемешать все пиксели выбранной картинки всеми способами без повторов.

[The endless art gallery (Makarov’s version 5 - When uploading an image, there is a step-by-step pixel replacement in it) | Babylon.js Playground](https://playground.babylonjs.com/#02RSGB#2)

Бесконечная библиотека картинок где полки это количество пикселей в высоту, а стеллаж это количество пикселей в ширину.

[The endless art gallery (Makarov’s version 6 - Endless procedural image generation) | Babylon.js Playground](https://playground.babylonjs.com/#3E3EDL)

Всевозможные варианты всевозможных рисунков всевозможных красок но рисование с помощью кисти! 

[The endless art gallery (Makarov’s version 7 - All possible options for drawing all kinds of pictures with a brush) | Babylon.js Playground](https://playground.babylonjs.com/#LFPQMH)

Короче давайте просто возьмём, и сделаем бесконечную случайно процедурно генерируемую цветную плоскость, и добавим табло координат. 

[The endless art gallery (Makarov’s version 8 - Endless color random picture) | Babylon.js Playground](https://playground.babylonjs.com/#FT6RX3)

Подиум с постепенной заменой пикселей на случайные пиксели из предустановленной картинки работает только в +x а по -x не работает.

[The endless art gallery of the Backrooms(Makarov’s version 9-With a preset image and replacing its pixels with random) | Babylon.js Playground](https://playground.babylonjs.com/#QJ28PQ#1)

Теперь сделаем вместо замены случайных пикселей на случайные просто случайно перемешанные пиксели без повторов.

[The endless art gallery (Makarov’s version 10 - Shuffled ONE art endless gallery) | Babylon.js Playground](https://playground.babylonjs.com/#ZRJP8W)

Тоже самое что и предыдущая только в процентном соотношение каждый чанк имеет свой процент перемешивания (1%, 2%, ..., 100%, затем снова 1%). Внутри каждого процента перемешивание детерминированное от seed..

[The endless art gallery (Makarov’s version 11 - Shuffled ONE art endless gallery as a percentage) | Babylon.js Playground](https://playground.babylonjs.com/#Q5KQFM)

Мне нужно последовательная замена пикселей с одной картинки на другую ПОЛОСКАМИ вертикальными.

[The endless art gallery (Makarov’s version 12 - Shuffled MORE art endless gallery as a percentage) | Babylon.js Playground](https://playground.babylonjs.com/#VKOWY3#2)

Теперь сделаем множество картинок, и перестановку пикселей в них случайно смешивая между собой. Это так странно... Будто-бы ты играешь в майнкрафт, и гонки одновременно... Ну это не то что я хотел.

[The endless art gallery (Makarov’s version 13 - Shuffled MORE art endless gallery as a % with random pixel swapping) | Babylon.js Playground](https://playground.babylonjs.com/#3UXDUC)

Просто случайное перемешивание пикселей при каждой последующей итерации.

[The endless art gallery (Makarov’s version 14 - Random Shuffled ONE art endless gallery) | Babylon.js Playground](https://playground.babylonjs.com/#80SX0G)

Но 8 версия бесконечного ковра цветного растянутая какая-то нужно убрать эти кольца растянутости.

[The endless art gallery (Makarov’s version 15 - Endless color random carpet on SIMD-BP128) | Babylon.js Playground](https://playground.babylonjs.com/#M6DA22)

Отлично теперь я хочу совместить квантовую пену, и SIMD-BP128 текстуру в бесконечной генерации ковра.

[The endless art gallery (Makarov’s version 16 - Endless color random carpet on SIMD-BP128 + Quantum foam GUI parameters) | Babylon.js Playground](https://playground.babylonjs.com/#XYULV1#1)

Просто случайно перемешанные пиксели картинки.

[The endless art gallery (Makarov’s version 17 - Random pixel shuffler) | Babylon.js Playground](https://playground.babylonjs.com/#H5ELRP)

Попробуем взять и перемешивать числа из RLE, и LZW.

[The endless art gallery (Makarov’s version 18 - Shuffled LZW and RLE) | Babylon.js Playground](https://playground.babylonjs.com/#TEH4UR)

Теперь сделаем метановые озёра.

[The endless art gallery (Makarov’s version 19 - Endless lakes of methane) | Babylon.js Playground](https://playground.babylonjs.com/#M0EUM9)

Теперь сделаем что-бы пиксели картинки слева сверху брать случайное количество последовательностей пикселей идущих подряд от 1 до 100 случайно на кластеры поделить, и при каждой последующей итерации переставлять их эти кластеры случайно как бы как будто-бы порезали бумагу на ленты в полосочки разной ширины длинг и пытаемся заново собрать эти полоски вместе...

[The endless art gallery (Makarov’s version 20 - Cut into random width ribbons, and randomly connect them) | Babylon.js Playground](https://playground.babylonjs.com/#LS3D0B#1)

Отлично но нужно делать нормально в процентном соотношении первая итерация 1% порезки на ленты второй 2% процент и так далее...

[The endless art gallery (Makarov’s version 21 - Cut into random width ribbons,and randomly connect them but % the ratio) | Babylon.js Playground](https://playground.babylonjs.com/#3UZWHU)

Тоже что и предыдущая только с множеством картинок для каждой собственное перемешивания а не совместное а не одной.

[The endless art gallery (Makarov’s version 22 - 21'th version but more images) | Babylon.js Playground](https://playground.babylonjs.com/#ML95MR)

Нужно что-бы в одной картинки порезанные ленты перемешивались друг с другом.

[The endless art gallery (Makarov’s version 23 - 22'th version but more images in one shuffled lents) | Babylon.js Playground](https://playground.babylonjs.com/#7X63KN)

Короче все эта хрень нужно идти другим путем возьмём и сделаем какой нибудь глюк и при каждой итерации будем изменять этот глюк может выйдет что-то интересное.

[The endless art gallery (Makarov’s version 24 - Endless Glitch Podium One Image Version) | Babylon.js Playground](https://playground.babylonjs.com/#OZ7RJ7#1)

Теперь сделаем для множества картинок а не одной.

[The endless art gallery (Makarov’s version 25 - Endless Glitch Podium More Images Version) | Babylon.js Playground](https://playground.babylonjs.com/#X1BYR3)

Ладно попробуем разделить на целые ленты а не кусочки лент.

[The endless art gallery (Makarov’s version 26 - An endless podium cut into horizontal strips of varying sizes One image) | Babylon.js Playground](https://playground.babylonjs.com/#6WOC9S)

Теперь мы порежем картинку на вертикальные глитч ленты а не горизонтальные.

[The endless art gallery(Makarov’s version 27-An endless podium cut into vertical GLITCH strips of varying sizes 1 image) | Babylon.js Playground](https://playground.babylonjs.com/#8OHA1O)

Тоже что и 26 версия только горизонтальная а не вертикальная.

[The endless art gallery (Makarov’s version 28 - An endless podium cut into vertical strips of varying sizes One image) | Babylon.js Playground](https://playground.babylonjs.com/#E1NV7Y)

Херня растянутых вертикальных полос.

[The endless art gallery (Makarov’s version 29 - An endless catwalk made of stretched vertical strips) | Babylon.js Playground](https://playground.babylonjs.com/#Q4Q23M)

Совместим 26 версию, и сделаем ленты вертикальными уже которые были горизонтальными.

[The endless art gallery (Makarov’s version 30 - An endless podium cut into horizontal+vertical strips of varying sizes) | Babylon.js Playground](https://playground.babylonjs.com/#XS58B0)

Тоже что и 30 версия только множество картинок а не одна.

[The endless art gallery (Makarov’s version 31-It’s the same as version 30, only there are many images instead of just 1) | Babylon.js Playground](https://playground.babylonjs.com/#YMKGJM)

Может у кого-то есть какие-то ещё идеи пишите в дискуссии...
