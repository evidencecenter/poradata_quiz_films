# ПОРА играть: Арктика в кадре и за кадром

Игра канала [«ПОРА считать»](https://t.me/poradata) по статье [«Арктика в кадре и за кадром»](https://goarctic.ru/kultura/arktika-v-kadre-i-za-kadrom/) на GoArctic.

## Как устроена

Две части, как в названии статьи.

1. **В кадре.** Восемь карточек с описанием фильма или сериала об Арктике. Игрок решает, когда снят фильм: смахивает кадр влево (СССР, 1935–1986) или вправо (XXI век, 2002–2024), либо нажимает кнопку. На последней карточке («Территория») верны оба ответа: роман Куваева экранизировали дважды.
2. **За кадром.** Пять пар билетов о зрителях и деньгах. Игрок выбирает билет, на котором цифра больше; билеты каждый раз встают в случайном порядке.

Каждый верный ответ приносит фильму игрока зрителей. 13 из 13 дают 41,1 млн, как у «Земли Санникова», самого кассового фильма советской подборки. На финальном экране результат сравнивается с «Двумя капитанами», «Следами на снегу» и «Морем студеным».

## Файлы

- `index.html` — игра, шрифты встроены.
- `photos/` — 13 фото мест, о которых идет речь в вопросах.
- `og.png` — картинка для превью ссылки в Telegram и VK.

## Как поменять тексты

Все тексты лежат в блоке `<script type="application/json" id="quiz-data">` внутри `index.html`: вопросы, пояснения, ссылка на статью (`articleUrl`), подписи кнопок и уровни результата (`tiers`).

Мета-тег `og:image` указывает на `https://evidencecenter.github.io/poradata_quiz_films/og.png`. Если игра будет открываться по другому адресу, поменяйте его.

## Фото

Все фото с Wikimedia Commons, в игре они кадрированы до 16:9 и уменьшены. Подпись с автором и лицензией стоит на каждом фото.

| Файл | Что на фото | Автор | Лицензия |
|---|---|---|---|
| `photos/01_vongozero.jpg` | Озеро Вонгозеро, Карелия | [Scaut2002](https://commons.wikimedia.org/wiki/File:%D0%92%D0%BE%D0%BD%D0%B3%D0%BE%D0%B7%D0%B5%D1%80%D0%BE.jpg) | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.ru) |
| `photos/02_khibiny_1979.jpg` | Лыжный поход в Хибины, 1979 год | [Jaan Künnap](https://commons.wikimedia.org/wiki/File:%D0%A5%D0%B8%D0%B1%D0%B8%D0%BD%D1%8B_79_%2832%29.jpg) | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.ru) |
| `photos/03_trawler_yagry.jpg` | Рыболовный траулер «Ягры» | [MarineEngine](https://commons.wikimedia.org/wiki/File:%D0%A1%D1%80%D0%B5%D0%B4%D0%BD%D0%B8%D0%B9_%D1%80%D1%8B%D0%B1%D0%BE%D0%BB%D0%BE%D0%B2%D0%BD%D1%8B%D0%B9_%D1%82%D1%80%D0%B0%D1%83%D0%BB%D0%B5%D1%80_%22%D0%AF%D0%B3%D1%80%D1%8B%22_%D0%BF%D1%80.50010.jpg) | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.ru) |
| `photos/04_lapland.jpg` | Финская Лапландия | [Ximonic (Simo Räsänen)](https://commons.wikimedia.org/wiki/File:%C3%84k%C3%A4slompolo_and_Yll%C3%A4s_in_Kolari%2C_Lapland%2C_Finland%2C_2018_September.jpg) | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/deed.ru) |
| `photos/05_airship_italia_1928.jpg` | Дирижабль «Италия», 1928 год | [автор неизвестен](https://commons.wikimedia.org/wiki/File:Svenska_unds%C3%A4ttningsexpeditionen_1928-_Luftskeppet_Italia-_DIG136344.tif) | общественное достояние |
| `photos/06_mir_mine.jpg` | Алмазный карьер «Мир», Якутия | [Staselnik](https://commons.wikimedia.org/wiki/File:Mirny_in_Yakutia.jpg) | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/deed.ru) |
| `photos/07_teriberka.jpg` | Териберка, Мурманская область | [Dmitry A. Mottl](https://commons.wikimedia.org/wiki/File:Teriberka.jpg) | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.ru) |
| `photos/08_pevek.jpg` | Певек, Чукотка | [Consfone](https://commons.wikimedia.org/wiki/File:The-view-on-pevek-from-paakinay-knoll.jpg) | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.ru) |
| `photos/09_bennett_island.jpg` | Остров Беннетта: в этих местах искали Землю Санникова | [Ansgar Walk](https://commons.wikimedia.org/wiki/File:Bennett-Insel_4_2014-08-25.jpg) | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/deed.ru) |
| `photos/10_yakutsk_cinema.jpg` | Кинотеатр «Центральный», Якутск | [SmallSonMarex](https://commons.wikimedia.org/wiki/File:%D0%9A%D0%B8%D0%BD%D0%BE%D1%82%D0%B5%D0%B0%D1%82%D1%80_%C2%AB%D0%A6%D0%B5%D0%BD%D1%82%D1%80%D0%B0%D0%BB%D1%8C%D0%BD%D1%8B%D0%B9%C2%BB_%28%D0%AF%D0%BA%D1%83%D1%82%D1%81%D0%BA%29_14.09.2025.jpg) | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.ru) |
| `photos/11_sochi_winter_theatre.jpg` | Зимний театр в Сочи, где проходит «Кинотавр» | [Евгений Лодянов](https://commons.wikimedia.org/wiki/File:%D0%90%D1%8D%D1%80%D0%BE%D1%84%D0%BE%D1%82%D0%BE%D1%81%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA_%D0%97%D0%B8%D0%BC%D0%BD%D0%B5%D0%B3%D0%BE_%D1%82%D0%B5%D0%B0%D1%82%D1%80%D0%B0_04_%28cropped%29.jpg) | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.ru) |
| `photos/12_labytnangi.jpg` | Лабытнанги, ЯНАО | [Qweasdqwe](https://commons.wikimedia.org/wiki/File:Labitnangi3.jpg) | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/deed.ru) |
| `photos/13_liinakhamari.jpg` | Лиинахамари, Печенгский округ | [Fastboy](https://commons.wikimedia.org/wiki/File:Liinahamari_harbour.jpg) | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/deed.ru) |

## Шрифты

Inter и Sofia Sans Extra Condensed, обе под лицензией SIL Open Font License 1.1.
