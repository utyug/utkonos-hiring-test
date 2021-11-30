## Тестовое задание для кандидатов в DS команду компании Утконос

**Задание** 

Предлагаем попробовать себя в решении следующей боевой задачи. 
Необходимо помочь коллегам, занимающимся заведением ассортимента, и разработать алгоритм машинного обучения для заполнения поля "тип товара". 
Есть товары, в которых уже проставлен тип товара, а есть где не проставлен, соответственно нужно проставить. 
Вот и все ;) 

Данные можно скачать [здесь](https://drive.google.com/drive/folders/12x4lPmuZV1WFHd4J9oKsuJNvokJaBlOk).

**Описание данных**

В качестве фичей есть следующие данные, представленные в колонках:
* good_id - псевдо id товара
* category_id - псевдо id категории товара
* item_name - полное наименование товара
* item_description - описание товара

А в колонке 'product_type' записан как раз тот самый тип товара, который необходимо научиться определять.

То есть, как вы наверное уже догадались, необходимо решить классическую задачу мультиклассовой классификации. 
Метрикой качества для простоты бyдем считать обычную точность (accuracy).

**Чего ждем**

Мы ожидаем, что за один-два вечера вам как супер спецу удастся побить наш бэйзлайн на scikit-learn имеющий точность 77% ;)

Как только вам это удастся, присылайте результаты: 
* test.csv с заполненной колонкой product_type (просьба не менять порядок следования товаров в тесте)
* jupyter notebook с решением   

Удачи!



