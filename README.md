# SQL-practice-commands
anything that can be used for work
1.      Определить 5 самиых дорогих товаров в таблице products Выведите их наименования и цену.

2.      Oпределите товар с самым длинным названием в таблице products.

3.      Cобрать строку используя данные таблицы. 

4.      Выведите id всех курьеров и их годы рождения из таблицы couriers.
        Год рождения необходимо получить из колонки birth_date. Новую колонку с годом назовите birth_year.

5.      Укажите параметры функции так, чтобы вместо NULL значений в результат попадало текстовое значение unknown.

6.      повысить цену всех товаров в таблице products на 5%.
        Выведите id и наименования всех товаров, их старую и новую цену. Колонку с новой ценой назовите — new_price.

7.      Повысьте цену на 5% только на те товары, цена которых превышает 100 рублей. Цену остальных товаров оставьте без изменений. 
        Также не повышайте цену на икру, которая и так стоит 800 рублей.

8.      Вычислите НДС каждого товара в таблице products и рассчитайте цену без учёта НДС. 
        Выведите всю информацию о товарах, включая сумму налога и цену без его учёта. 
        Колонки с суммой налога и ценой без НДС назовите соответственно tax и price_before_tax

9.      Отберите из таблицы user_actions все действия пользователей по созданию заказов, совершенных ими после полуночи 6 сентября 2022 года. 
        Выведите колонки с id пользователей, id созданных заказов и временем их создания.

10.     Назначьте скидку 20% на все товары из таблицы products и отберите те, цена на которые с учётом скидки превышает 100 рублей. 
        Выведите id товаров, их наименования, прежнюю цену и новую цену с учётом скидки.

11.     Отберите из таблицы products все товары, названия которых либо начинаются со слова «чай», либо состоят из пяти символов.

12.     Отберите из таблицы products все товары, содержащие в своём названии последовательность символов «чай» (без кавычек). 

13.     Выберите из таблицы products id и наименования только тех товаров, названия которых начинаются на букву «с» и содержат только одно слово.

14.     Выберите из таблицы products все чаи стоимостью больше 60 рублей и вычислите для них цену со скидкой 25%.
        Скидку в % менеджер попросил указать в отдельном столбце в формате текста «25%».
        Столбцы со скидкой и новой ценой назовите соответственно discount и new_price.
        Также необходимо любым известным способом избавиться от «чайного гриба»: вряд ли менеджер имел в виду и его, когда ставил нам задачу.

15.     За период с 25 августа по 4 сентября 2022 года включительно
        Из таблицы user_actions выведите всю информацию о действиях пользователей с id 170, 200 и 230.

16.     Выведите всю информацию о курьерах из таблицы курьеры, у которых не указан их день рождения.

17.     Определите id и даты рождения 50 самых молодых пользователей мужского пола из таблицы users. 
        Не учитывайте тех пользователей, у которых не указана дата рождения.

18.     Чтобы узнать id заказа и время доставки последних 10 заказов, доставленных курьером с id 100 из таблицы courier_actions.

19.     Получите id всех заказов, сделанных пользователями сервиса в августе 2022 года.

20.     Отберите id всех курьеров, родившихся в период с 1990 по 1995 год включительно.

21.     Получите информацию о всех отменах заказов, которые пользователи совершали в течение августа 2022 года по средам с 12:00 до 15:59.
        Результат отсортируйте по убыванию id отменённых заказов — от самых последних отмен к самым первым.

22.     Вычислите НДС каждого товара в таблице products и рассчитайте цену без учёта НДС.
        Для товаров из списка налог составляет 10%. Для остальных товаров НДС = 20%.
        Выведите всю информацию о товарах, включая сумму налога и цену без его учёта.
        
23.     Посчитайте количество курьеров женского пола в таблице couriers

24.     Посчитайте количество заказов в таблице orders с девятью и более товарами. 
        Для этого воспользуйтесь функцией array_length, отфильтруйте данные по количеству товаров в заказе и проведите агрегацию. 
        Полученный столбец назовите orders_count.
        
25.     Рассчитайте среднюю цену товаров в таблице products, в названиях которых присутствуют слова «чай» или «кофе». 
        Любым известным способом исключите из расчёта «иван-чай» и «чайный гриб». 
        Среднюю цену округлите до двух знаков после запятой.

26.     С помощью функции AGE и агрегирующей функции рассчитайте возраст самого молодого курьера мужского пола в таблице couriers.
        Возраст выразите количеством лет, месяцев и дней (как в примере выше), переведя его в тип VARCHAR. 
        В качестве даты, относительно которой считать возраст курьеров, используйте свою текущую дату.
        
27.     Воспользуйтесь функцией AGE и рассчитайте разницу в возрасте между самым старым и самым молодым пользователями мужского пола
        
28.     Один из пользователей сервиса сделал заказ, в который вошли сухарики, чипсы и энергетический напиток. 
        Посчитайте стоимость такого заказа. Колонку с рассчитанной стоимостью заказа назовите order_price.

29.     Посчитайте стоимость заказа, в котором будут три пачки сухариков, две пачки чипсов и один энергетический напиток. 
        Колонку с рассчитанной стоимостью заказа назовите order_price.

30.     сколько пользователей никогда не отменяли свой заказ. 
        Для этого из общего числа всех уникальных пользователей отнимите число уникальных пользователей, которые хотя бы раз отменяли заказ.

31.     С помощью группировки посчитайте количество курьеров мужского и женского пола  

32.     максимальный возраст пользователей мужского и женского пола в таблице users. Возраст измерьте количеством полных лет. 

33.     Разбейте пользователей из таблицы users на группы по возрасту (возраст измеряем количеством полных лет) и посчитайте число пользователей каждого возраста. 
        Колонку с возрастом назовите age, а колонку с числом пользователей — users_count. 
        Пользователей, у которых вместо возраста будет пропуск, также подсчитаем число пользователей.
        
34.     разбейте пользователей из таблицы users на группы по возрасту (возраст измеряем количеством полных лет) и полу пользователя. 
        Посчитайте количество пользователей по полу и ворасту
            
35.     Посчитайте, сколько заказов было сделано и сколько было отменено в каждом месяце, используя функцию DATE_TRUNC.

36.     Посчитайте количество товаров в каждом заказе из таблицы orders, примените к этим значениям группировку и посчитайте количество заказов в каждой группе. 
        Выведите две колонки: количество товаров в заказе и число заказов с таким количеством.
        
36/2    Отберите только те размеры заказов, общее число которых превышает 5000
         
37.     Отберите id трёх курьеров, доставивших наибольшее количество заказов в августе 2022 года.

38.     Отберите id тех курьеров, которые в сентябре 2022 года успели доставить только по одному заказу.

39.     Отберите пользователей, у которых последний заказ был создан до 8 сентября 2022 года.

40.     посчитайте долю отменённых заказов для каждого пользователя

41.     Посчитайте число пользователей, попавших в каждую возрастную группу. 
        Группы назовите соответственно «19-24», «25-29», «30-35», «36-41» (без кавычек). 
        Выведите наименования групп и число пользователей в них. 
        Колонку с наименованием групп назовите group_age, а колонку с числом пользователей — users_count.

42.     рассчитайте среднее число заказов всех пользователей нашего сервиса. 
        Для этого сначала в подзапросе посчитайте, сколько заказов сделал каждый пользователь, 
        затем обратитесь к результату подзапроса в блоке FROM и уже в основном запросе усредните количество заказов по всем пользователям.

42/2 .  задание 42 с использованием "Табличного выражения"

43.      Выведите из таблицы products информацию о всех товарах кроме самого дешёвого.

44.     Выведите информацию о товарах цена на которые превышает среднюю цену всех товаров на 20 рублей и более. 

45.     количество уникальных клиентов сделавших за последнюю неделю хотя бы один заказ.

46.     возраст самого молодого курьера мужского пола в таблице couriers, (С помощью функции AGE() и агрегирующей функции)
        Чтобы получилась именно дата, перед применением функции AGE() переведите посчитанную последнюю дату в формат DATE 
        Возраст курьера измерьте количеством лет, месяцев и дней и переведите его в тип VARCHAR

47.     Oтберите все заказы, которые не были отменены пользователями.

48.     сколько заказов сделал каждый пользователь
        укажите среднее число заказов всех пользователей (AVERAGE)
        отклонение числа заказов от среднего значения. Отклонение считайте так: число заказов «минус» округлённое среднее значение.

49.     Выведите id и содержимое 100 последних доставленных заказов из таблицы orders

50.     Выведите всю информацию о курьерах, которые в сентябре 2022 года доставили 30 и более заказов.

51.     Назначьте скидку 15% на товары, цена которых превышает среднюю цену товаров на 50 и более рублей, 
        назначьте скидку 10% на товары, цена которых ниже средней на 50 и более рублей. 
        Цену остальных товаров внутри диапазона (среднее - 50; среднее + 50) оставьте без изменений. 
--------------------------------------------------------------------------------------------------------------------------------------
-------1-------
SELECT name,
       price
FROM   products
ORDER BY price desc limit 5;

-------2-------     
SELECT name,
       length(name) as name_length,
       price
FROM   products
ORDER BY name_length desc limit 1

-------3-------
SELECT concat ('Заказ № ', order_id, ' создан ', date(creation_time)) as order_info
FROM   orders

-------4-------
SELECT courier_id,
       date_part('year', birth_date) as birth_year
FROM   couriers

-------5-------
SELECT courier_id,
       coalesce(date_part('year', birth_date)::varchar, 'unknown') as birth_year
FROM   couriers

-------6-------
SELECT name,
       price,
       price*1.05 as new_price
FROM   products

-------7-------
SELECT product_id,
       name,
       price,
       case when price <= 100 or
                 name = 'икра' then price
            when price > 100 then price*1.05
            else 0 end new_price
FROM   products

-------8-------
SELECT product_id,
       name,
       price,
       round(price/120*20, 2) as tax,
       round(price - price/120*20, 2) as price_before_tax
FROM   products

-------9-------
SELECT user_id,
       order_id,
       time
FROM   user_actions
WHERE  action = 'create_order'
   and time > '2022-09-06'

-------10-------
SELECT product_id,
       name,
       price as old_price,
       price*0.8 as new_price
FROM   products
WHERE  price*0.8 > 100

-------11-------
SELECT product_id,
       name
FROM   products
WHERE  split_part(name, ' ', 1) = 'чай'    // поделит длинное слово на части по знаку указаному в ковычках и вернет первую часть до первого разделителя
    or length(name) = 5                    // например "чай зеленый в пакетиках" = первая часть "чай"

-------12--------
SELECT product_id,
       name
FROM   products
WHERE  name like '%чай%'

-------13--------
SELECT product_id,
       name
FROM   products
WHERE  name not like '% %'
   and name like 'с%'

-------14--------
SELECT product_id,
       name,
       price,
       '25%' as discount,
       price*0.75 as price_discounted
FROM   products
WHERE  name like '%чай %'
   and price > 60
   
------15---------
SELECT user_id,
       order_id,
       action,
       time
FROM   user_actions
WHERE  user_id in (170, 200, 230)
   and time between '2022-08-25'
   and '2022-09-05'

------16---------
SELECT birth_date,
       courier_id,
       sex
FROM   couriers
WHERE  birth_date is null

------17---------
SELECT user_id,
       birth_date
FROM   users
WHERE  sex = 'male'
   and birth_date is not null
ORDER BY birth_date desc limit 50

------18----------
SELECT order_id,
       time
FROM   courier_actions
WHERE  courier_id = 100
   and action = 'deliver_order'
ORDER BY time desc limit 10

------19---------
SELECT order_id
FROM   user_actions
WHERE  action = 'create_order'
   and date_part('month', time) = 8
ORDER BY order_id

------20--------
SELECT courier_id
FROM   couriers
WHERE  date_part('year', birth_date) between 1990
   and 1995

------21--------
SELECT user_id,
       order_id,
       action,
       time
FROM   user_actions
WHERE  date_part('month', time) = 8
   and date_part('dow', time) = 3
   and date_part('hour', time) >= 12
   and date_part('hour', time) < 16
   and action = 'cancel_order'
ORDER BY time desc

------22-------
SELECT product_id,
       name,
       price,
       case when name in ('сахар', 'сухарики', 'сушки', 'семечки', 'масло льняное', 'виноград', 'масло оливковое', 'арбуз', 'батон', 'йогурт', 'сливки', 'гречка', 'овсянка', 'макароны', 'баранина', 'апельсины', 'бублики', 'хлеб', 'горох', 'сметана', 'рыба копченая', 'мука', 'шпроты', 'сосиски', 'свинина', 'рис', 'масло кунжутное', 'сгущенка', 'ананас', 'говядина', 'соль', 'рыба вяленая', 'масло подсолнечное', 'яблоки', 'груши', 'лепешка', 'молоко', 'курица', 'лаваш', 'вафли', 'мандарины') then round(price/110*10,
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         2)
            else round(price/120*20, 2) end as tax,
       case when name in ('сахар', 'сухарики', 'сушки', 'семечки', 'масло льняное', 'виноград', 'масло оливковое', 'арбуз', 'батон', 'йогурт', 'сливки', 'гречка', 'овсянка', 'макароны', 'баранина', 'апельсины', 'бублики', 'хлеб', 'горох', 'сметана', 'рыба копченая', 'мука', 'шпроты', 'сосиски', 'свинина', 'рис', 'масло кунжутное', 'сгущенка', 'ананас', 'говядина', 'соль', 'рыба вяленая', 'масло подсолнечное', 'яблоки', 'груши', 'лепешка', 'молоко', 'курица', 'лаваш', 'вафли', 'мандарины') then round(price - price/110*10,
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         2)
            else round(price - price/120*20, 2) end as price_before_tax
FROM   products
ORDER BY price_before_tax desc, product_id

-------23--------
SELECT count(courier_id) as couriers_count
FROM   couriers
WHERE  sex = 'female'

------24--------
SELECT count(order_id) as orders_count
FROM   orders
WHERE  array_length(product_ids, 1) >= 9

------25--------
SELECT round(avg(price), 2) as avg_price
FROM   products
WHERE  (name like '%чай %'
    or name like '%кофе%')
   and name not like '%иван-чай%'
   
-------26-------
SELECT min(age(birth_date))::varchar as min_age
FROM   couriers
WHERE  sex = 'male'

-------27------
SELECT age(max(birth_date), min(birth_date)) as age_diff
FROM   users
WHERE  sex = 'male'

-------28---------
SELECT sum(price) as order_price
FROM   products
WHERE  name in ('сухарики', 'чипсы', 'энергетический напиток')

-------29-------
SELECT sum(case when name = 'сухарики' then price * 3
                when name = 'чипсы' then price * 2
                when name = 'энергетический напиток' then price
                else 0 end) as order_price
FROM   products

-------30-------
SELECT count(distinct user_id) - count(distinct user_id) filter (WHERE action = 'cancel_order') as users_count
FROM   user_actions

------31--------
SELECT sex,
       count(courier_id) as couriers_count
FROM   couriers
GROUP BY sex
ORDER BY couriers_count

------32--------
SELECT sex,
       date_part('year', max(age(birth_date))) as max_age
FROM   users
GROUP BY sex
ORDER BY max_age

------33------
SELECT date_part('year', age(birth_date)) as age,
       count(user_id) as users_count
FROM   users
GROUP BY age
ORDER BY age

------34------
SELECT date_part('year', age(birth_date)) as age,
       sex,
       count(user_id) as users_count
FROM   users
WHERE  birth_date is not null
GROUP BY age, sex
ORDER BY age, sex

-------35------
SELECT date_trunc('month', time) as month,
       action,
       count(order_id) as orders_count
FROM   user_actions
GROUP BY month, action
ORDER BY month, action

------36-------
SELECT array_length(product_ids, 1) as order_size,
       count(order_id) as orders_count
FROM   orders
GROUP BY order_size
ORDER BY order_size

-------36/2-------отберите только те размеры заказов, общее число которых превышает 5000

SELECT array_length(product_ids, 1) as order_size,
       count(order_id) as orders_count
FROM   orders
GROUP BY order_size having count(order_id) > 5000
ORDER BY order_size

-------37--------
SELECT courier_id,
       count(distinct order_id) as delivered_orders
FROM   courier_actions
WHERE  action = 'deliver_order'
   and date_part('month', time) = 8
GROUP BY courier_id
ORDER BY delivered_orders desc limit 3

-------38--------
SELECT courier_id,
       count(distinct order_id) as delivered_orders
FROM   courier_actions
WHERE  action = 'deliver_order'
   and date_part('month', time) = 9
   and date_part('year', time) = 2022
GROUP BY courier_id having count(distinct order_id) = 1
ORDER BY courier_id

-------39---------
SELECT user_id
FROM   user_actions
WHERE  action = 'create_order'
GROUP BY user_id having max(time) < '2022-09-08'
ORDER BY user_id

-------40---------
SELECT user_id, count(distinct order_id) filter (WHERE action = 'cancel_order')::decimal / count(distinct order_id)
             as cancel_rate
FROM   user_actions
GROUP BY user_id
ORDER BY user_id

--------41--------
SELECT case when date_part('year', age(birth_date)) between 19 and
                 24 then '19-24'
            when date_part('year', age(birth_date)) between 25 and
                 29 then '25-29'
            when date_part('year', age(birth_date)) between 30 and
                 35 then '30-35'
            when date_part('year', age(birth_date)) between 36 and
                 41 then '36-41' end as group_age,
       count(user_id) as users_count
FROM   users
WHERE  birth_date is not null
GROUP BY group_age
ORDER BY group_age

-------42----------
SELECT avg(orders_count) as orders_avg            // расчитываем среднее число заказов всех пользователей
FROM   (SELECT user_id,                           // используя данные взятые из результат подзапроса
               count(order_id) as orders_count    // (подзапроос)(выбираем user_id, Считаем "количество заказов" как "orders_count"
        FROM   user_actions                       // из таблицы user actions, где действие = "создать заказ"
        WHERE  action = 'create_order'
        GROUP BY user_id) as table
        
--------42/2-------
with table1 as (SELECT user_id,                       // задаем временную таблицу как подзапрос: with Таблица1 как ( выбираем user_id,  
                   count(order_id) as orders_count    // Считаем "количество заказов" как "orders_count"
            FROM   user_actions                       // из таблицы user actions, где действие = "создать заказ"
            WHERE  action = 'create_order'      
            GROUP BY user_id)                         
SELECT avg(orders_count) as orders_avg                //после того как задали временную таблицу - обращаемся к ней за данными и выбираем 
FROM   table1                                         //среднее число заказов всех пользователей из "Таблицы1"

---------43--------
SELECT product_id,                                    //выбрать product_id,name,price
       name,                                          //из таблиц продукты
       price                                          // где цена !=(подзапрос)(показать минимальную цену из таблицы Продукты)
FROM   products                                       
WHERE  price != (SELECT min(price)
                 FROM   products)
ORDER BY product_id desc

---------44--------
SELECT product_id,                                    //(чтобы решить эту задачу нам нужно в подзапросе обратиться к средней цене товаров из таблицы продукты)
       name,                                          //выбираем продукт_ид, name, price из таблицы products где цена больше средней на 20 рублей(=) или более(>)
       price                                          //чем(подзапрос)( выбираем среднюю цену продуктов) + 20
FROM   products
WHERE  price >= (SELECT avg(price)
                 FROM   products) + 20
ORDER BY product_id desc

--------45----------
SELECT count(distinct user_id) as users_count         //выбираем "Подсчитать количество (уникальных пользователей) как "число_пользователей" и показать нам
FROM   user_actions                                   //из таблицы "Действия пользователей" где действие: "Создать заказ"
                                                      // и время > "Время последнего заказа минус одна неделя"
WHERE  action = 'create_order'
   and time > (SELECT max(time)
            FROM   user_actions) - interval '1 week'     

--------46-----------   функция AGE принимает два аргумента как даты и из первого аргумента вычитает второй
                        например дата сегдня и дата рождения покажет интервал возраста
                        например age('2023','1994')покажет 28 (лет)

SELECT min(age((SELECT max(time)::date                                     //выбрать МИНИМУМ из резултата функции AGEдля 
                FROM   courier_actions), birth_date))::varchar as min_age  //как подзапрос с двумя аргументами, первый аргумент - подзапрос(Выбрать актуальное время) 
FROM   couriers.                                                           //второй аргумент -дата рождения) :: перевести в строковый тип данных и назвать min_age
WHERE  sex = 'male'.                                                       // где пол ="Мужчина"

Таким образом мы выбираем минимальное значение из ( Последняя дата минус дата рождения)( запрос функция определяющая возраст)

-------47---------

SELECT order_id                                         //выбрать заказы из таблицы Действия пользователей
FROM   user_actions                                     //где заказ НЕ В ( подзапрос)(показать все заказы где действие = "отменить_заказ") 
WHERE  order_id not in (SELECT order_id
                        FROM   user_actions
                        WHERE  action = 'cancel_order')

-------48-------
with table1 as (SELECT user_id,                           //вводим локальное табличное выражение в котором находим Подсчет количества всех заказов
                   count(order_id) as orders_count        // где действие было "создать заказ" . тобишь количество созданных заказов as 1.orders_count
            FROM   user_actions                           
            WHERE  action = 'create_order'
            GROUP BY user_id)
SELECT user_id,                                           //далее в запросе выбираем user_id, 1.orders_count, 2. (Подзапрос AVG(1.orders_count) из Table1
       orders_count,                                      //второе-среднее значение выбираем как 2.orders_avg
       round((SELECT avg(orders_count)
       FROM   t1), 2) as orders_avg, 
       orders_count - round((SELECT avg(orders_count)     //далее третее; из первого вычитаем подзапрос второго также из Table1
       FROM   t1), 2) as orders_diff                      //третее - "разница между количеством заказов и средним значеним " как orders_diff
FROM   t1
ORDER BY user_id limit 1000

-------49-------
SELECT order_id,                                       //выберем заказ,продукты в заказе
       product_ids
FROM   orders                                           // из таблицы "Заказы"
WHERE  order_id in (SELECT order_id                     // WHERE заказ Есть в списке: (<подзапрос> выбрать заказ из таблицы действия курьера WHERE
                    FROM   courier_actions              // действием было = "Заказ доставлен"
                    WHERE  action = 'deliver_order'     // сортировать по времени по убыванию и показать 100 позиций
                    ORDER BY time desc limit 100)
ORDER BY order_id

------50--------
SELECT courier_id,                               
       birth_date,
       sex
FROM   couriers
WHERE  courier_id in (SELECT courier_id                               //выбрать данные "курьеров" WHERE курьер В списке (<подзапрос> показать курьеров 
                      FROM   courier_actions                        //из таблицы "действия_курьеров" WHERE дата.месяц = 9(сентябрь)
                      WHERE  date_part('month', time) = 9           //дата.год = 2022
                         and date_part('year', time) = 2022.        // и действие = " заказ доставлен"
                         and action = 'deliver_order'               // сгрупировать список курьеров У КОТОРЫХ "подсчет уникальных заказов" больше или равен 30
                      GROUP BY courier_id having count(distinct order_id) >= 30)
ORDER BY courier_id

------51-----------
with avg_price as (SELECT avg(price) as price          //используем табличное выражение avg_price показывающее среднюю цену продуктов 
                   FROM   products)
SELECT product_id, name,  price,                       //выбираем данные которые нам нужны
   case 
   when price >= (SELECT * FROM   avg_price) + 50 then price*0.85         // есил цена больше или равна чем (<подзапрос> показать все
                                                                          // из табличного выражения "Средняя цена") + 50 тогда цену уменьшить на 15%
   when price <= (SELECT * FROM   avg_price) - 50 then price*0.9          // если цена меньше или раван чем (<подзапрос> показать все
                                                                          // из табличного выражения "средняя цена") - 50 тогда цену уменьшить на 10%
   else price                                                             // иначе оставить обычную цену 
   end as new_price
FROM   products
ORDER BY price desc, product_id

-----52------------
