# Вёрстка видеоплеера

Вёрстка видеоплеера сделана в учебных целях.

К видео добавлены кнопки управления, время продолжительности и полоса прокрутки. Проигрываемое видео заранее задано, видео можно поменять.

Демо вёрски доступно по [ссылке](https://rs0x069.github.io/video-player/).

![screenshot](https://raw.githubusercontent.com/rs0x069/video-player/main/.github/images/screenshot.png)

В проекте изпользуется библиотека [video-player-jslib](https://github.com/devmanorg/video-player-jslib).

Видео играет по [этой ссылке](https://dvmn.org/media/filer_public/78/db/78db3456-3fd3-4504-9ed9-d2d1fd843c0b/highest_peak.mp4).

Если хочется выбрать другое видео, с помощью аргумента `src` плееру можно указать, какое видео проигрывать (ссылки обязаны заканчиваться расширением файла):
```html
<script type="text/javascript">
  createPlayer({
    elementId: 'player',
    src: 'https://dvmn.org/media/filer_public/d0/16/d016d9b8-4180-4bb9-ad83-0241f61627b8/samsung_demo_-_alive_in_color.mp4'
});
</script>
```

## Цели проекта

Учебный проект для курсов web-разработчиков [dvmn](https://dvmn.org).
