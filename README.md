# my_sql_geekbrains


В папке Base_real_estate представлена полностью самостоятельная работа по написанию базы данных.
Подобная база данных может быть полезной компании тесно связанной с рынком коммерческой недвижимости, например
оказывающей оценочные, консалтинговые и риелторские услуги.

База данных соединяет сведения о конкретных объектах недвижимости и их собственников (агентов)
с видами услуг, которые могут быть оказаны им компанией-владельцем данной базы данных.

Также данная база позволяет анализировать рынок недвижимости и проводить его исследования, например с
помощью представленных в Base_real_estate_part_2.sql запросов.

Base_real_estate_part_1.sql включает:

1. Тщательное описание расположения объектов недвижимости, физических характеристик, ценообразующих факторов, собственника, источника информации и др.
   (название таблиц: First_data, Place, Fisic_charact, OPEX)
2. Перечень взаимодействующих с компанией участников рынка недвижимости: собственников / агентов (имя, название компании, телефон, статус на рынке)
   (название таблицы: Agent)
3. Перечень оказываемых услуг (название, стоимость)
   (название таблицы: Services)
4. Заказы (заказчик, описание заказываемой услуги, стоимость)
   (название таблицы: Orders)
4. Звонки клиентам (включая описание того кому осуществлялся звонок, время звонка, вид обсуждаемой услуги, описание итога разговора)
   (название таблицы: Calls)

Base_real_estate.mwb содержит наглядную схему построенной базы данных.

Объекты недвижимости и сведения об агентах трудолюбиво собиралась из реальных источников и тшательно проверялась в течении нескольких месяцев.
