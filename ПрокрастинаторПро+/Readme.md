<div align="Left">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTWz36-h1Wbdor8yz_6grnrd6AMDLCnaQgKw3seGC2bNg&s" width="150" />
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ed/Pandas_logo.svg/768px-Pandas_logo.svg.png" width="120" />
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/31/NumPy_logo_2020.svg/179px-NumPy_logo_2020.svg.png" width="120" />
  <img src="https://matplotlib.org/3.1.1/_static/logo2_compressed.svg" width="150" />
  <img src="https://res.cloudinary.com/practicaldev/image/fetch/s--Y4OT-DoX--/c_imagga_scale,f_auto,fl_progressive,h_900,q_auto,w_1600/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/xm36iqima49zxbqsr8ma.jpg" width="70" />
</div>

# Описание проекта

Развлекательное приложения Procrastinate Pro+. Несмотря на огромные вложения в рекламу, последние несколько месяцев компания терпит убытки. Ваша задача — разобраться в причинах и помочь компании выйти в плюс. Есть данные о пользователях, привлечённых с 1 мая по 27 октября 2019 года:

лог сервера с данными об их посещениях,
выгрузка их покупок за этот период,
рекламные расходы.

## Задачи :

откуда приходят пользователи и какими устройствами они пользуются,
сколько стоит привлечение пользователей из различных рекламных каналов;
сколько денег приносит каждый клиент,
когда расходы на привлечение клиента окупаются,
какие факторы мешают привлечению клиентов.

## Описание данных

visits_info_short.csv хранит лог сервера с информацией о посещениях сайта,

orders_info_short.csv — информацию о заказах,

costs_info_short.csv — информацию о расходах на рекламу.

### Структура visits_info_short.csv:

User Id — уникальный идентификатор пользователя,
Region — страна пользователя,
Device — тип устройства пользователя,
Channel — идентификатор источника перехода,
Session Start — дата и время начала сессии,
Session End — дата и время окончания сессии.

### Структура orders_info_short.csv:

User Id — уникальный идентификатор пользователя,
Event Dt — дата и время покупки,
Revenue — сумма заказа.

### Структура costs_info_short.csv:

dt — дата проведения рекламной кампании,
Channel — идентификатор рекламного источника,
costs — расходы на эту кампанию.



## Выводы о проделанной работе 
В исследовании проанализировали данные Procrastinate Pro+

Были обнаруженые пользователи из стран США, Германии, Франции, Великобритании

Деньги на маркетинг были потрачены не целесообразно. Было оплачено 10 каналов рекламы. на 2 канала FaceBoom и TipTop поратили 90% бюджета. 
Оставшиеся 8 каналов получил 10% бюджета. Пересмотреть общий план Маркетинга.

Реклама в Европе окупается в отличии от США.

США самый крупный регион по пользователям. Но не смог окупиться в рекламной компании, слишком дорогой пользователь получился в данной стране. 
Надо пересомтреть план маркетинга на США, чтобы снизись стомость пользователя и выйти в плюс.

Пользователи Mac и iPhone показали самую лучшую конверсию, данные пользователи поценциально самые платящие.
Увеличивать удержание данных пользователей.

Потенциально прибыльный канал RocketSuperAds - показывает хорошую конверсию и удержание, при небольшой бюджете.
6.1  Выделите причины неэффективности привлечения пользователе

Два слишком дорогих канала. FaceBoom Стоисмость пользователя канала TipTop слишком быстро росла.

Общий вывод Маркетинговый план с неправильным распределением средств на рекламу, привело к дорогому привлечению пользователя. 
Который не дал нужной окупаемости на стомость маркетингово плана.
6.2  Сформулируйте рекомендации для отдела маркетинга.

Уменьшить цену пользователя в каналах TipTop.

Отказаться от канала FaceBoom, AdNonSense по причине плохого удержания. FaceBoom - дорогой канал. Топ 2 по цене.

Работать с пользователями Mac и Apple - хорошо конвертируются в платящих.

Поработать над развитием канала RocketSuperAds - при небольших вложениях показывал отлиные результаты.
