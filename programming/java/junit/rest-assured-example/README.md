Мой первый опыт использования  [Rest-Assured](http://rest-assured.io/) для автоматизации RESTfull API. В 2017 году я был тестировщиком в стартапе, идея которого была в организации b2b2b & b2b2c агентурной сети для продажи всевозможных туристических услуг.

Мы интегрировали всех доступных онлайн провайдеров позволяющих бронировать, отели, трансферы, авиа перелеты и проч. Проблема заключалась в том, чтобы с нашего фронта послать в сторонний сервис правильный код населенного пункта, отеля, вокзала или аэропорта. Была БД, где производился мапинг "нашего" кода на его варианты у внешних провайдеров. Приведенный здесь пример тестов автоматизировал взаимодействие этой БД с внутренними сервисами - фронтом и бэком. 