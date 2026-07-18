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

Подиум с постепенной заменной пикселей на случайные пиксели из предустановленной картинки работает только в +x а по -x не работает.

[The endless art gallery of the Backrooms(Makarov’s version 9-With a preset image and replacing its pixels with random) | Babylon.js Playground](https://playground.babylonjs.com/#QJ28PQ#1)

Теперь сделаем вместо замены случайных пикселей на случайные просто случайно пермешанные пиксели без повторов.

[The endless art gallery (Makarov’s version 10 - Shuffled ONE art endless gallery) | Babylon.js Playground](https://playground.babylonjs.com/#ZRJP8W)

Тоже самое что и предыдущая только в процетном соотношение каждый чанк имеет свой процент перемешивания (1%, 2%, ..., 100%, затем снова 1%). Внутри каждого процента перемешивание детерминированное от seed..

[The endless art gallery (Makarov’s version 11 - Shuffled ONE art endless gallery as a percentage) | Babylon.js Playground](https://playground.babylonjs.com/#Q5KQFM)

Теперь сделаем множество картинок и перестановку пикселей в них случайно смешивая. Это так странно... Будто-бы ты играешь в майнкрафт, и гонки одновременно... Ну это не то что я хотел.

[The endless art gallery (Makarov’s version 12 - Shuffled MORE art endless gallery as a percentage) | Babylon.js Playground](https://playground.babylonjs.com/#VKOWY3#2)

Мне нужно последовательная замена пикселей с одной картинки на другую.

[The endless art gallery (Makarov’s version 13 - Shuffled MORE art endless gallery as a % with random pixel swapping) | Babylon.js Playground](https://playground.babylonjs.com/)

Может у кого-то есть какие-то ещё идеи пишите в дискусии...
