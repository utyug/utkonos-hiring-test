## Тестовое задание для кандидатов в DS команду компании Утконос

**Задание** 

Предлагаем попробовать себя в решении следующей боевой задачи. 
Необходимо помочь коллегам, занимающимся заведением ассортимента, и разработать алгоритм машинного обучения для заполнения поля "тип товара". 
Есть товары в которых уже проставилен тип товара, а есть где не простален, соответственно нужно проставить. 
Вот и все ;) 

Данные можно скачать здесь.

**Описание данных**

В качестве фичей есть следующие данные, представленные в колонках:
* good_id - псевдо id товара
* node3_id - псевдо id категории 3-го уровня
* name - полное наименование товара
* desc - описание товара

А в колонке 'product_type' записан как раз тот самый тип товара, который необходимо научиться определять.

То есть, как вы наверное уже догадались, необходимо решить классическую задачу мультиклассовой классификации. 
Метрикой качества для простоты бyдем считать обычную точность (accuracy).

**Чего ждем**

Мы ожидаем что за один-два вечера вам как супер спецу удасться побить наш бэйзлайн на scikit-learn имеющий точность 77% ;)

Как только вам это удастся, присылайте результаты: 
* test.csv с заполненной колонкой product_type  
* jupyter notebook с решением   

Удачи!



