## Данные

Используя данные сервиса Яндекс.Недвижимость, определить рыночную стоимость объектов недвижимости и типичные параметры квартиры.

* total_images — число фотографий квартиры в объявлении
* last_price — цена на момент снятия с публикации
* total_area — площадь квартиры (м²)
* first_day_exposition - дата публикации
* rooms - число комнат
* ceiling_height - высота потолков (м)
* floors_total - всего этажей в доме
* living_area - жилая площадь в квадратных метрах (м²)
* floor - этаж
* is_apartment -  является ли апартаментами  
* studio - является ли студией
* open_plan - имеет ли свободную планировку
* kitchen_area - площадь кухни (м²)    
* balcony - число балконов           
* locality_name - название населённого пункта         
* airports_nearest -  расстояние до ближайшего аэропорта (м)     
* cityCenters_nearest - расстояние до центра города (м)     
* parks_around3000 - число парков в радиусе 3 км        
* parks_nearest - расстояние до ближайшего парка (м)  
* ponds_around3000 - число водоёмов в радиусе 3 км   
* ponds_nearest -  расстояние до ближайшего водоёма (м)        
* days_exposition - сколько дней было размещено объявление

---
## Задача

Предоставлены данные сервиса Яндекс.Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет. Необходимо проанализировать, какие параметры в основном определяют рыночную стоимость объектов недвижимости. 

---
## Библиотеки для установки:

`pip install seaborn`