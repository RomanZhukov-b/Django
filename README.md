# Курс по основам Django

### Home Work 1

Создайте пару представлений в вашем первом приложении:
- главная
- о себе.

> Внутри каждого представления должна быть переменная html — многострочный текст с HTML-вёрсткой и данными о вашем первом Django-сайте и о вас. Сохраняйте в логи данные о посещении страниц.

___



### Home Work 2

1. Создайте три модели Django: 

- клиент
- товар
- заказ.

> Клиент может иметь несколько заказов. Заказ может содержать несколько товаров. Товар может входить в несколько заказов.

Поля модели «Клиент»:
- имя клиента
- электронная почта клиента
- номер телефона клиента
- адрес клиента
- дата регистрации клиента

Поля модели «Товар»:
- название товара
- описание товара
- цена товара
- количество товара
- дата добавления товара

Поля модели «Заказ»:
- связь с моделью «Клиент», указывает на клиента, сделавшего заказ
- связь с моделью «Товар», указывает на товары, входящие в заказ
- общая сумма заказа
- дата оформления заказа

> Допишите несколько функций CRUD для работы с моделями по желанию.

___



### Home Work 3

Продолжаем работать с товарами и заказами.

Создайте шаблон, который выводит список заказанных клиентом товаров из всех его заказов с сортировкой по времени:
- за последние 7 дней (неделю)
- за последние 30 дней (месяц)
- за последние 365 дней (год)

Товары в списке не должны повторятся.

> Перед запуском обязательно применить все миграции! Базу заполнять тестовыми данными на основе консольных команд по примеру hw2

___



### Home Work 4
Измените модель продукта
- добавьте поле для хранения фотографии продукта.
- cоздайте форму, которая позволит сохранять фото.

___



### Home Work 5

Настройте под свои нужды вывод информации о клиентах, товарах и заказах на страницах вывода информации об объекте и вывода списка объектов.

> Перед запуском обязательно применить все миграции!