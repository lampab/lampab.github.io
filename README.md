## Технический репозиторий для [плагина Статистика](https://github.com/and7ey/lampa/blob/main/README.md#%D1%81%D1%82%D0%B0%D1%82%D0%B8%D1%81%D1%82%D0%B8%D0%BA%D0%B0-statsjs) для приложения Лампа


### Как это работает?
1. Плагин Статистика создает json с результатами просмотра фильмов
2. JSON сохраняется в Gist ([пример](https://gist.github.com/lampab/86fd94b5e689041706a3bcdd5968340b))
3. При открытии lampab.github.io в URL передается id Gist'a ([пример](https://lampab.github.io/#86fd94b5e689041706a3bcdd5968340b))
4. Код ([index.html](https://github.com/lampab/lampab.github.io/blob/main/index.html#L308)) забирает данные из Gist'a для формирования страницы "Итоги года"
