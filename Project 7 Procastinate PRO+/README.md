#### Анализ убытков приложения ProcrastinatePRO+
# ProcrastinatePRO+
## Описание   
Проведен анализ данных от ProcrastinatePRO+.  
Рассчитаны различные метрики, использован когортный анализ: LTV, CAC, Retention rate, DAU, WAU, MAU и т.д. Использованы уже написанные ранее функции расчёта метрик. Сделаны правильные выводы по полученным данным.  
## Задача
- Задача для маркетингового аналитика развлекательного приложения Procrastinate Pro+. Несмотря на огромные вложения в рекламу, последние несколько месяцев компания терпит убытки. Ваша задача — разобраться в причинах и помочь компании выйти в плюс.
## Данные, используемые в проекте из приложения ProcrastinatePRO+
Файл ***visits_info_short.csv*** хранит лог сервера с информацией о посещениях сайта,   

***orders_info_short.csv*** — информацию о заказах,     
а ***costs_info_short.csv*** — информацию о расходах на рекламу.   

Структура ***visits_info_short.csv***:    

***User Id*** — уникальный идентификатор пользователя,  
***Region*** — страна пользователя,    
***Device*** — тип устройства пользователя,   
***Channel*** — идентификатор источника перехода,   
***Session Start*** — дата и время начала сессии,   
***Session End ***— дата и время окончания сессии.    

Структура ***orders_info_short.csv***:  

***User Id*** — уникальный идентификатор пользователя,   
***Event Dt*** — дата и время покупки,   
***Revenue*** — сумма заказа.   

Структура ***costs_info_short.csv***:   

***dt*** — дата проведения рекламной кампании,   
***Channel*** — идентификатор рекламного источника,   
***costs*** — расходы на эту кампанию.   
## Инструменты Python
библиотека Pandas, matplotlib, когортный анализ, юнит экономика, продуктовые метрики, seaborn  
## Выводы (проект завершен)  
Оценив окупаемость рекламы, можно сделать такие **выводы**:   
•	В целом реклама, направленная на привлечение пользователей, не окупается из-за слишком больших трат на привлечение клиентов. Поэтому **рекламный бюджет  надо оптимизировать**.  
•	**Расходы** на рекламу для пользователей **Mac и iPhone можно уменьшить**, эти устройства и так эффективно приводят в сервис пользователей, но **надо обратить внимание на конверсию пользователей в покупателей на этих девайсах и увеличить удержание** (рекомендуется выяснить причину слабого удержания). Также крайне **негативное влияние на эффективномть привлечения оказали рекламные компании в США и реклама в канале TipTop**. Вложения не окупились продажами. Расходы на эти рекламные компании также **рекомендуется сократить** или при подаче рекламы выбирать регион не только США.  
•	- Для повышения эффективности можно провести **мероприятия по увеличению удержания пользователей проживающих в США и приходящих через рекламные компании в FaceBoom и AdNonSense**: выяснить проблемы, с которым сталкиваются пользователи при использовании сервиса.  
•	- Также для привлечения большего количества пользователей можно **увеличить количество рекламных компаний в маленьких каналах например YRabbit**, т.к. в рассмотренном периоде он оказался самым прибыльным в расчете на одного пользователя, при этом привлек относительно небольшое число клиентов. Также рекомендуется давать рекламу в **RocketSuperAds, MediaTornado, LeapBob** так как они весьма эффективны при малых вложениях.   
