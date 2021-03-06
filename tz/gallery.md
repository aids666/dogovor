# Галерея
## Назначение модуля
Модуль предназначен для размещения материалов в разделе сайта «Галерея»
## Внешний вид
Каждый объект представлен в двух видах:
- В общем списке объектов
- На странице объекта с полной информацией о нем. Для отображения используется шаблон «Галерея - типовая страница».
## Возможности
Модуль позволет:
- Добавлять материал на сайт в разделе «Галерея»
- Редактировать существующие материалы
- Посмотреть/откатить изменения материала (сохраняются предыдущие версии текста — редакции)
- Страница «Галерея» содержит превью созданных материалов. Если на странице более 10 материалов, то страница разбивается на страницы по 10 материалов на странице
## Добавление страницы. Редактирование страницы.
Список полей:
- Заголовок*. Тип поля: `текст`. Заголовок альбома - обязательное поле
- Вес сортировки. Тип поля: `число`. Предназначен для сортировки на общей странице.
- Обложка. Тип поля: `изображение`. Основное изображение - обложка альбома. Прикрепляемый файл.
- Текст. Тип поля: `текст`. Текстовая область с визуальным редактором. Текст на странице. Используется модуль CKEditor <https://ckeditor.com/>
- Изображения. Тип поля: `изображение`. Изображения в альбоме.

<img src="https://github.com/synapse-studio/helper/blob/master/tz/gallery/gallery.jpg?raw=true">


## Страница Галлерея
На странице представлены опубликованные альбомы с сортировкой по полю “Вес сортировки”. Каждый альбом состоит из изображения, заголовка.

<img src="https://github.com/synapse-studio/helper/blob/master/tz/gallery/gallery2.jpg?raw=true">

## Страница Альбома
<img src="https://github.com/synapse-studio/helper/blob/master/tz/gallery/gallerypage.jpg?raw=true">
