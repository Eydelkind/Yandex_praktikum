Задачи исследования: приоритизация гипотез об оптимизации выручки интернет-магазина для проведения A/B теста по наиболее приоритетной гипотезе и последующий анализ его результатов. Исследование отвечает на вопрос, стоит ли продолжать тест или принять положительный либо отрицательный его результат.

Основные этапы исследования:

Часть 1. Приоритизация гипотез
  1. ICE
  2. RICE
  3. Сравнение ICE и RICE. Выводы по первой части
  
Часть 2. Анализ результатов A/B теста
  1. Кумулятивные данные
  2. Графики дохода, конверсий среднего чека
  3. Точечные гафики и перцентили - вычисление аномалий
  4. Вычисление статистической значимости различий для сырых данных
  5. Вычисление статистической значимости различий для очищенных данных
  6. Принятие решения

Использовались библиотеки: pandas, numpy, matplotlib, scipy, seaborn.

Данные: таблица гипотез (9), таблица количества покупателей в день с разбивкой по группам (всего 31 день, тестовая и контрольная группы), таблица заказов (1197 транзакций с указанием id покупателя, датой, суммой выручки с транзакции и группы).
