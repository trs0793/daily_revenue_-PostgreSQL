# daily_revenue_-PostgreSQL (English)
### Goal and Task Conditions:
Based on the information in the orders and products tables, calculate the daily revenue of the service and reflect it in the daily_revenue column. Then, using window functions and lag functions, calculate the daily revenue growth. Reflect the revenue growth both in absolute values and as a percentage relative to the previous day. Name the column with absolute growth revenue_growth_abs and the column with relative growth revenue_growth_percentage.

For the very first day, set the growth to 0 in both columns. When performing the calculations, do not consider canceled orders.

### Result:
Based on the information in the orders and products tables, I calculated the daily revenue of the service and reflected it in the daily_revenue column. Then, using window functions and lag functions, I calculated the daily revenue growth. I reflected the revenue growth both in absolute values and as a percentage relative to the previous day.

# daily_revenue_-PostgreSQL (Russian)
### Цель и условие задачи :

На основе информации в таблицах orders и products рассчитать ежедневную выручку сервиса и отразить её в колонке daily_revenue. Затем с помощью оконных функций и функций смещения посчитать ежедневный прирост выручки. Прирост выручки отразить как в абсолютных значениях, так и в % относительно предыдущего дня. Колонку с абсолютным приростом назвать revenue_growth_abs, а колонку с относительным — revenue_growth_percentage.

Для самого первого дня указать прирост равным 0 в обеих колонках. При проведении расчётов отменённые заказы не учитывать.

### Результат:
На основе информации в таблицах orders и products рассчитал ежедневную выручку сервиса и отразил её в колонке daily_revenue. Затем с помощью оконных функций и функций смещения посчитал ежедневный прирост выручки. Прирост выручки отразил как в абсолютных значениях, так и в % относительно предыдущего дня.
