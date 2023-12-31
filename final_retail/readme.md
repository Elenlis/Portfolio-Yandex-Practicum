#### Ритейл: Анализ результатов внедрения программы лояльности в сети строительных магазинов "Мы строили, строили и наконец построили"
# Ритейл финальный проект
## Описание
В сети строительных магазинов "Мы строили, строили и наконец построили" 3 месяца назад была введена программа лояльности, в нескольких магазинах клиенты могли приобрести карту лояльности по цене 200р и воспользоваться всеми скидками, бонусами и акциями которые предусматривала эта программа лояльности. С точки зрения собственников сети строительных магазинов - данных вполне достаточно.
## Задача 
**оценить результаты** введения программы лояльности **и решить: продолжать, приостановить или ее каким-то образом скорректировать**.    

## Данные, используемые в проекте Ритейл финальный проект 
- **Файл moscow_places.csv:**  
- purchaseid - идентификационный номер чека  
- item_ID - идентификационный номер товара    
- Quantity - количество товара в чеке    
- purchasedate - дата чека (совершения покупки и денежной трансакции)  
- CustomerID - идентификационный  номер покупателя   
- ShopID - идентификационный номер магазина   
- loyalty_program - маркер программы лояльности (1 - клиент имеет карту программы лояльности, 0 - клиент не участвует в программе лояльности)   
  **Файл product_codes.csv:**
- productID - идентификационный номер товара   
- price_per_one - цена за единицу товара в рублях    
## Инструменты Python
библиотека Pandas, matplotlib.pyplot, seaborn, plotly.express, scipy stats, numpy, math, plotly.graph_objs
## Вывод (проект завершен)  
Программа лояльности снижает средний чек, удержание клиентов, количество товара в чеке и количество покупок на человека. Кроме того количество проданных карт лояльности от месяца к месяцу становится меньше. Также большое количество проданного товара по программе лояльности привело к остановке работы одного из магазинов.   
Следовательно, **программа лояльности не дала ожидаемого результата**, только подсветила аудиторию (скорее всего профессионалы строительного бизнеса). Программу лояльности нужно либо отменить, либо пересмотреть ее условия.
