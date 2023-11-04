# rep_dipolm
Задача — разработать модель прогнозирования
стоимости жилья для агентства недвижимости, которая позволила бы агентству
недвижимости обойти конкурентов по скорости и качеству совершения
сделок.
 
* Описание данных:
* ➔ 'status' — статус продажи;
* ➔ 'private pool' и 'PrivatePool' — наличие собственного бассейна;
* ➔ 'propertyType' — тип объекта недвижимости;
* ➔ 'street' — адрес объекта;
* ➔ 'baths' — количество ванных комнат;
* ➔ 'homeFacts' — сведения о строительстве объекта (содержит несколько
типов сведений, влияющих на оценку объекта);
* ➔ 'fireplace' — наличие камина;
* ➔ 'city' — город;
* ➔ 'schools' — сведения о школах в районе;
* ➔ 'sqft' — площадь в футах;
* ➔ 'zipcode' — почтовый индекс;
* ➔ 'beds' — количество спален;
* ➔ 'state' — штат;
* ➔ 'stories' — количество этажей;
* ➔ 'mls-id' и 'MlsId' — идентификатор MLS (Multiple Listing Service, система
мультилистинга);
* ➔ 'target' — цена объекта недвижимости (целевой признак, который
необходимо спрогнозировать).

Работа разбита на этапы:
# 1. Постановка задачи
# 2. Знакомство с данными, базовый анализ и расширение данных
# 3. Разведывательный анализ данных (EDA)
# 4. Отбор и преобразование признаков
# 5. Решение задачи регрессии
# 6. Сериализация и запись результата в файл формата pkl
