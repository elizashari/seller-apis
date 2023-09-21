# Скрипты для обновления информации о продаваемых товарах с сайта [timeworld.ru](www.timeworld.ru)  на Yandex.market и Ozon #


## seller.py ##

Скрипт актуализирует информацию о товарах продавца на маркетплейсе Ozon. Скрипт позволяет автоматически получать информацию с артикулами товаров продавца, размещенных на маркетплейсе Ozon и изменять цены и количество этих товаров, исходя из списка остатков товара на сайте [timeworld.ru](www.timeworld.ru).

Для запуска скрипта клиенту необходимо в [личном кабинете Ozon](https://seller.ozon.ru/app/registration/signin?redirect=L2Rhc2hib2FyZC9tYWlu) получить следующие данные:

- `SELLER_TOKEN` — API-ключ Ozon Seller.
- `CLIENT_ID` — Идентификатор клиента Ozon.


## market.py ##

Скрипт актуализирует информацию о товарах продавца на маркетплейсе Yandex.market. Скрипт позволяет автоматически получать информацию с сайта [timeworld.ru](www.timeworld.ru) о количестве и ценнах оставшихся товаров. Программа собирает информацию о товарах, которые обслуживаются по модели доставки FBS и обновляет количество и цену товаров продавца на Yandex.market , исходя из списка остатков товара на сайте [timeworld.ru](www.timeworld.ru). Аналогично скрипт обрабатывает и обновляет информацию о количестве и цене товаров продавца на Yandex.market, которые обслуживаются по модели доставки DBS.

Для запуска скрипта клиенту необходимо по [инструкции yandex](https://yandex.ru/dev/market/partner-api/doc/ru/concepts/authorization) получить следующие данные:

- `MARKET_TOKEN` — API-ключ продавца Яндекс Маркета.
- `FBS_ID` — Идентификатор магазина по FBS модели.
- `DBS_ID` — Идентификатор магазина по DBS модели.
- `WAREHOUSE_FBS_ID` — Идентификатор склада FBS.
- `WAREHOUSE_DBS_ID` — Идентификатор склада DBS.



