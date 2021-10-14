# Отчет  о лабораторных  работах 
# Студент группы  ИДБ-18-06 Аминова А.А.

## Лабораторная 1

Предложение: Заказать продукцию
## IDEF0
![none](https://github.com/Amina108/Amina108.github.io/blob/main/IDEF0.png)
Предложение: вечером менеджер заказывает продукцию из бланка остатков в 1С
## Диаграмма классов
![none](https://github.com/Amina108/Amina108.github.io/blob/main/%D0%94%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B0%20%D0%BA%D0%BB%D0%B0%D1%81%D1%81%D0%BE%D0%B2.png)
## Диаграмма использования
![none](https://github.com/Amina108/Amina108.github.io/blob/main/%D0%94%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B0%20%D0%BF%D1%80%D0%B5%D1%86%D0%B5%D0%B4%D0%B5%D0%BD%D1%82%D0%BE%D0%B2.png)

##  Лабораторная  2
## Диаграмма  IDEF0
![none](https://github.com/Amina108/Amina108.github.io/blob/main/%D0%9A%D0%BE%D0%BD%D1%82%D0%B5%D0%BA%D1%81%D1%82%D0%BD%D0%B0%D1%8F%20%D0%BC%D0%BE%D0%B4%D0%B5%D0%BB%D1%8C.png)
На диаграмме изображен процесс деятельноси размещения заказов продукции поставщикам
## PDC-диаграмма
![none](https://github.com/Amina108/Amina108.github.io/blob/main/%D0%A1%D1%80%D0%B5%D0%B4%D0%BD%D0%B8%D0%B9%20%D1%83%D1%80%D0%BE%D0%B2%D0%B5%D0%BD%D1%8C.png)
А1 - Рабочий на основании остатков, необходимой продукции, бланка заказов и внесенных изменений пишет актуальный заказ

А2 - На основе полученного составленного заказа, графика размещений заказов, необходимой продукции и остатков менеджер/управляющий в 1С: УР оформляет заказ в соответствии с предоставленным бланком заказов. В результате получаем внесенный в 1С заказ. В случае неверно составленного заказа происходит внесение изменений в написанный заказ

А3 - Менеджер/управляющий в 1С: УР подтверждает отправку внесенного заказа на основании графика размещения заказов. В результате поставщик получает заказ, в систему заносятся данные о заказе
## DFD-диаграмма: Оформить заказ
![none](https://github.com/Amina108/Amina108.github.io/blob/main/DFD.png)
1 - Менеджер/управляющий с использованием составленного заказа и данных о необходимой продукции, остатках,а также возможных изменениях в бланке заказов заполняет форму заказов в 1С. В результате менеджер формирует конкретный заказ

2 - Менеджер/управляющий оформляет конкретный заказ на основании графика размещения размещения заказов. В результате получаем правильно оформленный заказ, либо выдается ошибка

3 - Форма ошибки возникает в случае неправлено оформленного заказа (сместился коридор поставки, неправильная дата, позиции не оказалось на складе)

4 - Менеджер/управляющий подтверждает отправку заказа опираясь на актуальный график размещения заказов. Отправленный заказ заносится в список оформленных заказов.  
## Диаграмма прецедентов
![none](https://github.com/Amina108/Amina108.github.io/blob/main/%D0%94%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B0%20%D0%BF%D1%80%D0%B5%D1%86%D0%B5%D0%B4%D0%B5%D0%BD%D1%82%D0%BE%D0%B2_%D0%BB%D0%B0%D0%B1%D0%B02.png)
