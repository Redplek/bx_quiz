# bx_quiz

## Задачи
1. Установка Битрикса. 
 - Редакция "Бизнес". 
 - Кодировка UTF-8. 
 - Установка готового решения "Интернет магазин"(bitrix.eshop) - Зеленая тема
2. Пользователь git. 
 - Клонировать репозиторий bx_squiz (https://github.com/damianua/bx_quiz.git) в папку с установленным Битриксом
3. Установить модуль aniart.main. Ознакомиться с функционалом модуля aniart.main 
4. Рефакторинг + Модульность Битрикса. 
 - На основе существующего функционала для установки и вывода SEO мета данных(перенести и подключить в модуле все что связанно с SEO сейчас в aniart.main)
 (SeoParamsCollector, SmartSeo) написать устанавливаемый модуль d7(aniart.seo).
 
   --модуль должен автоматически создавать Highload таблицу для ввода и хранения метаданных для страниц
   --модуль должен регистрировать обработку события OnEpilog во время установки (см. функцию onEpilog в BitrixObserver)
   --поля для highload блока: http://joxi.ru/Rmz9JR1i0WKkOr
   
 - Установить и подключить написанный модуль. 
 - Проверить, что старая функциональность сохранилась. 
 - Вычистить старый функционал из модуля aniart.main
5. Написание компонента d7. 
 - Дописать компонент, который бы выводил список недавно-просматриваемых товаров (5 последних). 
 - Компонент уже создан (local/components/aniart/catalog.recent_viewed/) с разработанным шаблоном и функциональными заглушками.
 - Дописать функционал удаления товара из недавно просматриваемых. JS-контроллер уже частично написан (script.js) в папке с шаблоном.
 - Вывести компонент на детальной странице товара(тут http://joxi.ru/5mddPl4IkvLlzm) и главной странице сайта (http://joxi.ru/12MWPLETM4QJgr).
6. Пользователь git. 
 - сделать pull-request для своих наработок в удаленном репозитории (https://github.com/damianua/bx_quiz.git)
 

## Что выполнено 
Пункты 1,2,3,6.
Пунтк 4. Добавлен модуль который расширяет возможности модуля aniart.main и создает HL с необходимыми полями для SEO. Детальнее смотрите сам модуль.
Пункт 5. Выполнен полностью.