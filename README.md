# Видеоплеер

Реализация видеоплеера и минимального набора кнопок.

![Видео плеер](static/gif/video-player.gif)

[Пример сайта с плеером](https://alex-men-vl.github.io/video-player/).

## Как запустить

- Скачайте код:
```shell
$ git clone https://github.com/Alex-Men-VL/video-player.git
```
- Перейдите в каталог проекта:
```shell
$ cd video-player
```
- Для внесения изменений в код подключите `livereload` (для автоматического обновления страницы):
```shell
$ python -m venv env
$ source env/bin/activate
$ pip install -r requirements.txt
$ livereload .
```
- Чтобы выбрать другое видео, добавьте следующее код:
    - В файле `index.html` найди блок с тегом `script`
    - Измените его следующем образом:
```html
<script type="text/javascript">
  createPlayer({
    elementId: 'player',
    src: 'ссылка на видео, заканчивающееся расширением файла'  
  });
</script>
```

## Цели проекта

Код написан в учебных целях — это урок в курсе по Python и веб-разработке на сайте [Devman](https://dvmn.org/). 