# Подбор наиболее частный вопросов на собеседования для фронтэнда с ответами, чтобы освежить память

- Можете ли пояснить разницу между progressive enhancement и graceful degradation?
	> graceful degradation будет пониматься как отказоустойчивость клиентских веб-интерфейсов.
	> Постепенная деградация может выражаться в возможности работы при отключённом JavaScript, в достаточно аккуратном отображении интерфейса в браузере, не поддерживающем новые свойства CSS3, в адекватном отображении сайта при отключенных изображениях. В каждом из этих случаев работа пользователя с интерфейсом будет в принципе возможна, хотя и не так удобна.

	> Что же такое progressive enhancement? Чаще всего этот термин переводят, как прогрессивное улучшение. Прогрессивное улучшение предполагает, что веб-интерфейсы должны создаваться поэтапно, циклически, от простого к сложному. На каждом из этапов должен получаться законченный веб-интерфейс, который будет лучше, красивее и удобнее предыдущего. Можно сказать, что сейчас таких этапов четыре:
	- «Старый-добрый-HTML»
	- «CSS»
	- «CSS3»
	- «JavaScript»
	> Источник: https://htmlacademy.ru/blog/7-progressive-enhancement

- Объясните, что означает "Семантическая разметка"
	> Семантическая вёрстка, или семантический HTML-код, — это подход к созданию веб-страниц на языке HTML, основанный на использовании HTML-тегов в соответствии с их семантикой (предназначением)[1], а также предполагающий логичную и последовательную иерархию страницы[2][3]. Он противопоставляется подходу, при котором написание HTML-кода определяется внешним видом веб-страницы. Для оформления веб-страниц, написанных в соответствии с семантикой, используются каскадные таблицы стилей (CSS). Стандарт HTML с самого начала включал в себя ряд семантических тегов[4], но большую популярность семантическая вёрстка получила после начала работ над HTML5.

	> Источник: https://ru.wikipedia.org/wiki/Семантическая_вёрстка

- Как можно оптимизировать загрузку внешних ресурсов на странице?
	1. Уменьшите количество HTTP-запросов
	2. Используйте поддомены для параллельного скачивания
	3. Используйте кэш браузера
	4. Используйте CDN для загрузки популярных JavaScript библиотек
	5. Используйте Gzip- сжатие

	> Подробней по каждому пункту: https://habrahabr.ru/post/137239/

- Каково преимущество в подгрузке внешних ресурсов с нескольких доменов?
	> Cогласно спецификации HTTP/1.1 на браузеры накладываются ограничения на количество одновременно загружаемых компонентов сайта, а именно не более 2-х компонентов с одного хоста. Поэтому если на Вашем сайте много графики, то ее лучше вынести на отдельный поддомен или поддомены. Для Вас это будет один и тот же сервер, а для браузера – разные. Чем больше поддоменов Вы создадите, тем больше файлов браузер сможет одновременно загрузить и тем быстрее загрузится вся страница сайта. Вам остается лишь изменить адрес картинок на новый. Очень простой, но действенный способ.

- Назовите три способа уменьшения времени загрузки страницы (воспринимаемого или реального)
	1. Помещайте CSS файлы в начале страницы
	2. Помещайте javascript в конец страницы
	3. Минимизируйте css и javascript
	4. Оптимизируйте ваши изображения
	5. Не масштабируйте изображения

	> Подробней по каждому пункту: https://habrahabr.ru/post/137239/

- Если Вы присоединились к проекту, где для форматирования используются табы, а Вы привыкли использовать пробелы, как Вы поступите?
	> Не спрашивайте, НИКОГДА!!!