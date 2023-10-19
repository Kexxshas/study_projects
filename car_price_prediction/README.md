## Данные

В распоряжении имеются данные сервиса по продаже автомобилей:

* DateCrawled — дата скачивания анкеты из базы
* VehicleType — тип автомобильного кузова
* RegistrationYear — год регистрации автомобиля
* Gearbox — тип коробки передач
* Power — мощность (л.с.)
* Model — модель автомобиля
* Kilometer — пробег (км)
* RegistrationMonth — месяц регистрации автомобиля
* FuelType — тип топлива
* Brand — марка автомобиля
* Repaired — была машина в ремонте или нет
* DateCreated — дата создания анкеты
* NumberOfPictures — количество фотографий автомобиля
* PostalCode — почтовый индекс владельца анкеты (пользователя)
* LastSeen — дата последней активности пользователя
* Price — цена (евро)

---
## Задача

Разработать модель для предсказания рыночной стоимости автомобиля с пробегом на основе его характеристик.  
Сравнить результаты работы нескольких моделей машинного обучения.
Основные требования:
- качество предсказания (значение метрика)
- время обучения модели

---
## Библиотеки для установки:

`pip install catboost`, `pip install lightgbm`, `pip install seaborn`