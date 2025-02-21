# README

## Теоретическое занятие №2

### Тема:

Репозитарий содержит материалы по теоретическому занятию №2, посвященному повторению работы с `@reduxjs/toolkit`.

### Цели занятия
- повторение и закрепление знаний;
- решение задач.

### Задачи занятия
Сегодня реализуем функциональность корзины для нашего приложения.

1. Добавляем кнопку "Добавить в корзину" на карточку товара.
2. Корзину предполагается хранить в отдельном слайсе состояния, `cartSlice`. Нужно, чтобы в ней хранились:
 - товары (с количеством, добавленным в корзину)
 - общее количество товаров, добавленных в корзину
 - общая стоимость товаров в корзине

 При этом, нужно реализовать функциональность добавления и удаления товара в/из корзины.
3. Реализуем работу с количеством товаров в корзине. Нужно предусмотреть экшны увеличения и уменьшения количества товаров на 1.
4. Делаем компонент `Cart`, в котором мы будем показывать нашу корзину. Для этого, нам понадобится определить еще один компонент, `CartItem`, где будут название товара, его цена, количество этого товара в корзине, и кнопки "+1", "-1", для добавления/удаления единицы товара из корзины.