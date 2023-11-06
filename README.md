# Оглавление
Этот проект парсит [музыкальный сайт](https://rur.hitmotop.com/)
____
# Что именно парсит?
1. [Рейтинговые треки](https://rur.hitmotop.com/songs/top-rated) выбирая количество треков (но <= 48)
2. Тоже [рейтиновые треки](https://rur.hitmotop.com/songs/top-rated) но можно выбрать количество страниц, с которых будет произведен парсинг
3. Треки введеные пользователем. Парсит от 1 трека до конечной страницы (на одной старнице 48 треков)
____
## Как использовать модуль *entered_tracks*
```
from pars_hitmotop.entered_tracks import EnteredTrack
result=EnteredTrack('linkin park',10)
```
1 аргументом (musci_name) передается название пенси или автора. 2 Аргументом (count) передается количество треков
____
## Как использовать модуль *rating_tracks_count*
```
from pars_hitmotop.rating_tracks_count import RatingCount
result=RatingCount(10)
```
1 аргументом (count) передается количество песен
____
## Как использовать модуль *rating_tracks_page*
```
from pars_hitmotop.rating_tracks_page import RatingPage
result=RatingPage(10)
```
1 аргументом (count) передается количество страниц (max 11)
____
