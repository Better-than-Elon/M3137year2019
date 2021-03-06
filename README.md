# Конспекты М3137

Если вы хотите помочь, всё, чего не хватает в конспектах - [тут](https://github.com/Jovvik/M3137year2019/issues/2)

Если нашли ошибку, пишите в [issues](https://github.com/Jovvik/M3137year2019/issues) или мне в телеграм @aeriu.

## 2 семестр

### Матанализ
- [Итоговый конспект](analysis/2sem/final.pdf)

### Линейная алгебра
- [Итоговый конспект](linear%20algebra/2sem/final.pdf)

## 1 семестр

### Линейная алгебра
- [Конспект к экзамену](linear%20algebra/1sem/main.pdf) _(рендер pdf с векторами в github'e не работает, поэтому надо pdf скачивать)_

### Матанализ
- [Опрос #1](analysis/1sem/opros.pdf)
- [Опрос #2](analysis/1sem/opros2.pdf)
- [Конспект к экзамену](analysis/1sem/final.pdf)


## Как компилировать самому

Билд делается через `xelatex`, потому что я ~тупой и не понял сразу, как включить русский в нормальном латехе~ хотел адекватную поддержку русского. Но в `pdflatex` билдится, багов не замечал. Зависимостей тонны, так что проще сразу ставить самый полный набор пакетов, который можете, иначе будет боль с `tlmgr`.

Все, кроме конспектов лекций и первого опроса по матану, писалось с минимизацией копипаста через импорты кусков других файлов с помощью `catchfilebetweentags`, поэтому по отдельности ничего не компилируется.

В 1 семе первые пара лекций написаны в markdown, при этом из-за добавления тегов для импортов они теперь сломанные, но пдфки в оригинальном виде оставлены.
