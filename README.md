## Технический репозиторий для [плагина Статистика](https://github.com/and7ey/lampa/blob/main/README.md#%D1%81%D1%82%D0%B0%D1%82%D0%B8%D1%81%D1%82%D0%B8%D0%BA%D0%B0-statsjs) для приложения Лампа


### Как это работает?
1. Плагин Статистика создает json с результатами просмотра фильмов
2. JSON сохраняется в Gist ([пример](https://gist.github.com/lamp-a/b7d3da5157147e4da223d16235ac6398))
3. При открытии lampa-a.github.io в URL передается id Gist'a ([пример](https://lamp-a.github.io/#b7d3da5157147e4da223d16235ac6398))
4. Код ([index.html](https://github.com/lamp-a/lamp-a.github.io/blob/60a573256458bdd2497fb4df78f54eb21f6da37b/index.html#L308)) забирает данные из Gist'a для формирования страницы "Итоги года"
