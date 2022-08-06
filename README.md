# K-Средних
### Ваня увлекся машинным обучением и наткнулся на статью об алгоритме K-Средних. 
> K-средних - алгоритм машинного обучения, решающий задачу кластеризации. Кластеризация - задача группировки множества объектов на подмножества (кластеры) таким образом, чтобы объекты из одного кластера были более похожи друг на друга, чем на объекты из других кластеров по какому-либо критерию.
Подробнее - [здесь](https://algowiki-project.org/ru/%D0%90%D0%BB%D0%B3%D0%BE%D1%80%D0%B8%D1%82%D0%BC_k_%D1%81%D1%80%D0%B5%D0%B4%D0%BD%D0%B8%D1%85_(k-means)).

![Иллюстрация к проекту](https://github.com/ValievINC/KMeans/blob/main/images/clusters.png)

### Ваня сразу же задал себе вопрос: "А где этот алгоритм можно использовать?". И почти мгновенно ответил на свой же вопрос: "В Фотообработке!". И Ваня представил это так:
### "На вход подается название изображения и какое-то число N. Необходимо получить N доминантных цветов с изображения, построить пирог с распределением этих цветов по фотографии и перекрасить изображение в эти доминантные цвета!"
### Данные для входа:
> <название файла с расширением> <число N>
* N - желаемое количество доминантных цветов.

### Что должно быть на выходе:
> файлы colors.jpg и newimage.jpg
* colors.jpg - пирог с распределением доминантных цветов на изображении
* newimage.jpg - изображение, перекрашенное в доминантные цвета

### Пример входных данных:
![image](https://github.com/ValievINC/KMeans/blob/main/images/image.jpg)
Команда:
> image.jpg 12

### Пример выходных файлов:
#### colors.jpg
![colors](https://github.com/ValievINC/KMeans/blob/main/images/colors_example.jpg)

#### newimage.jpg
![newimage](https://github.com/ValievINC/KMeans/blob/main/images/newimage_example.jpg)


### Примечания:
#### Для решения можно воспользоваться библиотеками [Numpy](https://numpy.org/doc/stable/), [matplotlib](https://matplotlib.org/stable/index.html), [PIL](https://pillow.readthedocs.io/en/stable/), [collections](https://docs.python.org/3/library/collections.html), [OpenCV](https://docs.opencv.org/4.x/d6/d00/tutorial_py_root.html).
#### Но наиболее полезным будет прочитать статью о K-средних и воспользоваться алгоритмами библиотек Scikit-learn. Подробнее в [этой страничке](https://scikit-learn.org/stable/index.html)
